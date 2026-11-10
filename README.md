# Chef Parlay — Official Windows Downloads

This public repository distributes **compiled Chef Parlay Windows installers only**. The application's source code is kept in a separate private repository.

## Installing
1. Open **Releases** on this repository.
2. Download the latest `ChefParlay-Setup-<version>-win-x64.exe`.
3. Run it once to install Chef Parlay.
4. Future versions can be installed from **CHECK UPDATES** inside the app.

The in-app updater checks this repository's latest published release, downloads the installer after your approval, verifies its SHA-256 checksum against `SHA256SUMS.txt`, and then starts the installer.

If there are no Releases yet, there is nothing to download. No installer or auto-update system is active until an installer containing the updater is built, published, and installed.

**Note:** Windows SmartScreen may warn about unsigned applications. Do not bypass warnings for unknown files; publisher code signing is recommended for wider distribution.
