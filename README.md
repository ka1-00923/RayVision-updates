# RayVision updates

Public release assets for the RayVision desktop apps. The application source is maintained in a separate private repository.

Stable releases provide `latest.json` (Tauri) and `latest-egui.json` (egui), signed `.app.tar.gz` updater bundles, and macOS `.dmg` installers. The updater verifies each bundle with the public key in `rayvision.key.pub` before installation.

Beta releases are not distributed through the stable `latest` endpoints. Access-controlled Beta delivery will use per-user authentication or an authenticated download gateway.
