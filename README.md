# 問卷易 APK releases

This public repository is the distribution channel for the 問卷易 Android app.
It contains only signed APK release assets, channel manifests, SHA-256 values,
and release notes. The application source code, Supabase configuration, and
clinical data are not stored here.

- `manifests/stable.json` is the public Stable pointer.
- `manifests/pilot.json` is the separate, invite-only Pilot pointer.
- GitHub Releases retain the immutable APK assets named by version and code.

Consumers must verify the published byte size, SHA-256, package name, version,
and signing certificate before installing an APK.
