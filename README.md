# Zohirola for Android

Zohirola is an Android app for browsing and posting on the fediverse (Mastodon-compatible servers).

- Package: `com.zohirola.app`
- Minimum Android: 6.0 (API 23). Works on all phone and tablet CPU types (ARM, ARM64, x86, x86_64), because the app is pure Java.
- Developer: [zohir630](https://github.com/zohir630)

## Build

Use the **Build APK** GitHub Actions workflow, or run:

```
./gradlew assembleRelease
```

The APK is created in `mastodon/build/outputs/apk/release/`. It is signed with the debug key so it can be installed directly. Create your own keystore before publishing to an app store.

## Notes

- Zohirola connects to Mastodon-compatible servers. The server list and sign-in use the standard Mastodon API.
- Donation features of the original project are disabled.

## License

This app is based on the open-source Mastodon for Android project and is distributed under the GNU General Public License v3.0. See [LICENSE](LICENSE). The license and the original copyright notices in the source files must be kept.
