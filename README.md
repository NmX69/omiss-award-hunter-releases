# OMISS Award Hunter — Downloads

A Windows desktop app for hunting **OMISS** operating awards, by **N6WWW**.

While you're checked into an OMISS net in NetLogger, a live heads-up display ranks which
checked-in stations to work to advance your awards. A companion offline dashboard renders
~110 awards — with **certificate-level tracking** (each band/tier enhancement counted the
way OMISS issues Cert #s) and an **OMISS sync** that reads your officially-issued awards by
your OM number and shows exactly which certificates you still need to **apply for**.

## Download

Open the **[latest release](../../releases/latest)** and pick one:

- **Installer (recommended):** `OMISS_Award_Hunter_Setup_v<version>.exe` — installs per-user
  (no admin) to `%LOCALAPPDATA%\Programs\OMISS Award Hunter` with a Start-menu shortcut.
  Uninstall any time from Settings → Apps.
- **Portable (no install):** `OMISS_Award_Hunter_v<version>_portable.zip` — unzip anywhere and
  run `OMISS Award Hunter.exe` inside. **Use this if your browser refuses to download the .exe.**

## Trouble downloading or running? (unsigned-app warnings)

The app is **new and not yet code-signed**, so Windows and some browsers flag it as coming
from an "unknown publisher." It is safe — this is a *reputation* warning, not a real threat.
Here's how to get past each one:

**1. Your browser blocks the download** (Edge/Chrome may say the .exe "can't be downloaded
securely" or "was blocked"):
- **Edge:** press **Ctrl+J** (Downloads), find the file, click the **...** menu →
  **Keep** → **Keep anyway**.
- **Chrome:** press **Ctrl+J**, then **Keep** / **Keep anyway** on the file.
- Or simply download the **portable .zip** instead — browsers block bare `.exe` downloads far
  more aggressively than `.zip` files.

**2. "Windows protected your PC" when you run it** (SmartScreen popup):
- Click **More info**, then **Run anyway**.

**3. It downloaded but won't run / seems blocked:**
- Right-click the file → **Properties** → tick **Unblock** (bottom-right) → **OK**, then run it.

**4. Windows Defender deleted/quarantined it** (less common):
- Restore it from Defender's *Protection history*, or report a false positive at
  `microsoft.com/wdsi/filesubmission`. The portable .zip is also less likely to be quarantined.

## Requirements
Windows 10/11. The live check-in features need [NetLogger](https://www.netlogger.org/).

## Credits
By N6WWW. Award rules were validated with help from **K1ALF**'s awards site.

---
*Source code is maintained privately; this repository hosts the public installer downloads only.*
