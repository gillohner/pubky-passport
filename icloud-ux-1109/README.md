# Passport iCloud UX — 2026-11-09

Fresh Linux Chromium captures of PR #278, using synthetic Apple/CloudKit pages and synthetic accounts. These are browser screenshots, not mockups. Mobile viewport: 375/390 × 812; desktop: 1280 × 900. Full-page images retain Passport's existing footer and can be taller than the viewport.

The first-step screenshots include focus/cancel recovery. The error images show the second-step retry UI, including Apple's indistinguishable generic error/declined-terms result. The switcher keeps Apple Account as text without the Apple logo. Google rows retain their existing G badge.

| State | 375 | 390 | 1280 |
| --- | --- | --- | --- |
| Sign in | [375px](375-sign-in.png) | [390px](390-sign-in.png) | [1280px](1280-sign-in.png) |
| Google help | [375px](375-google-help.png) | [390px](390-google-help.png) | [1280px](1280-google-help.png) |
| Apple help | [375px](375-apple-help.png) | [390px](390-apple-help.png) | [1280px](1280-apple-help.png) |
| Apple step 1 | [375px](375-apple-step1.png) | [390px](390-apple-step1.png) | [1280px](1280-apple-step1.png) |
| Apple step 1 cancelled | [375px](375-apple-step1-cancelled.png) | [390px](390-apple-step1-cancelled.png) | [1280px](1280-apple-step1-cancelled.png) |
| iCloud step 2 idle | [375px](375-icloud-idle.png) | [390px](390-icloud-idle.png) | [1280px](1280-icloud-idle.png) |
| iCloud step 2 waiting | [375px](375-icloud-waiting.png) | [390px](390-icloud-waiting.png) | [1280px](1280-icloud-waiting.png) |
| Popup closed | [375px](375-icloud-closed.png) | [390px](390-icloud-closed.png) | [1280px](1280-icloud-closed.png) |
| Web access disabled | [375px](375-icloud-web-access-off.png) | [390px](390-icloud-web-access-off.png) | [1280px](1280-icloud-web-access-off.png) |
| Apple error / conditional terms guidance | [375px](375-icloud-apple-error-or-terms-refused.png) | [390px](390-icloud-apple-error-or-terms-refused.png) | [1280px](1280-icloud-apple-error-or-terms-refused.png) |
| Network failure | [375px](375-icloud-network.png) | [390px](390-icloud-network.png) | [1280px](1280-icloud-network.png) |
| Apple preparation unavailable | [375px](375-icloud-unavailable.png) | [390px](390-icloud-unavailable.png) | [1280px](1280-icloud-unavailable.png) |
| Popup blocked | [375px](375-icloud-blocked.png) | [390px](390-icloud-blocked.png) | [1280px](1280-icloud-blocked.png) |
| Timeout | [375px](375-icloud-timeout.png) | [390px](390-icloud-timeout.png) | [1280px](1280-icloud-timeout.png) |
| Account switcher | [375px](375-switcher.png) | [390px](390-switcher.png) | [1280px](1280-switcher.png) |

Additional 1280px regression views (desktop default 720px viewport): [Google retry](1280-google-retry.png), [optional Drive backup](1280-optional-backup-permissions.png), [Drive permission before detachment](1280-detachment-permissions.png).

Real Apple account authentication, passkeys/2FA and native macOS/iOS/in-app Safari remain unverified. See the PR body for the exact tested browser matrix and deployment requirement.
