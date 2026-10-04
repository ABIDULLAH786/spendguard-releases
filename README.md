# SpendGuard releases

Android builds of SpendGuard, published here so they can be downloaded directly.
The source code lives in a separate, private repository; this one holds only release files.

Download page: https://spenggsurd.vercel.app/download

## Install

1. Download the newest `spendguard-<version>.apk` from [Releases](../../releases).
2. Open it on your phone and allow installs from your browser or file manager when Android asks.
3. Google Play Protect may warn that the app is unknown. SpendGuard is distributed directly
   because Google Play doesn't allow finance apps to read SMS.

## Verify the download

Each release lists the file's SHA-256. On a computer:

```
sha256sum spendguard-0.1.0.apk
```

Every release is signed with the same key. Its certificate SHA-256 is:

```
8a:4b:65:a3:cb:70:e0:93:41:14:4c:b9:70:0b:83:ce:5e:e7:74:91:57:f2:8d:32:c4:46:ec:3a:0d:b4:8f:42
```

An APK signed with any other certificate is not from SpendGuard.
