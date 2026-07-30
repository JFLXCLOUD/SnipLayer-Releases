# SnipLayer privacy policy

Effective date: July 30, 2026

SnipLayer is designed to process screenshots locally. It does not require an account, upload captured images, run advertising analytics, or send usage telemetry.

## Data processed

SnipLayer reads screen pixels only when the user starts a capture. Selected pixels are held in memory so they can be copied, edited, or saved. Background removal, cropping, masking, PNG encoding, and SVG generation run on the user's PC.

SnipLayer accesses the Windows clipboard when the user chooses Copy or Copy diagnostics. It does not read or retain existing clipboard contents.

## Local files

Preferences are stored in `%LOCALAPPDATA%\SnipLayer\settings.json`. Diagnostic logs are stored in `%LOCALAPPDATA%\SnipLayer\Logs`; logs older than seven days are removed when the app starts. Logs may contain app/version information, Windows error details, and local paths, but never captured pixels or clipboard contents.

Uninstall removes the app and shortcuts but preserves settings and logs. Delete `%LOCALAPPDATA%\SnipLayer` manually after uninstall if you also want those local files removed.

## Network access

SnipLayer makes no automatic network requests. Selecting **Settings > Check for updates** sends an HTTPS request to the GitHub API for this release repository. GitHub may receive normal connection data, such as IP address, request time, the SnipLayer version in the user-agent, and browser data if the download page is opened. GitHub's privacy terms govern that service.

SnipLayer does not sell or share personal data. Images leave the PC only through an action the user takes, such as pasting, saving into a synchronized folder, or sharing an exported file.

Privacy questions can be opened as a public issue only when they contain no sensitive information. A dedicated publisher privacy contact will be added before the final 1.0 release.
