# flutter_openssl_crypto (with 16KB page size support)
> [!IMPORTANT]
> This fork is now outdated, as [flutter_vodozemac](https://pub.dev/packages/flutter_vodozemac) contains the same E2EE support
> and comes with 16kb page size support out of the box.
> So, `flutter_openssl_crypto` is now redundant and has been superseded by Vodozemac according to this official changelog: > You no longer need to ship flutter_openssl_crypto. The necessary encryption algorithms now come from the Vodozemac package. This should make the platform integration much easier.


This package provides libcrypto from OpenSSL for Android and iOS
to be used with dart:ffi.

Android Gradle Plugin 4.1 is required for Android.

Currently, OpenSSL is included completely in iOS, but this isn't guaranteed.
