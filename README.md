# flutter Android

## Gerar apk 32-bit
flutter build apk --target-platform=android-arm

## Gerar apk 64-bit
flutter build apk --target-platform=android-arm64

## Gerar apk 32-bit e 64bit
flutter build apk --split-per-abi

### Destino
build/app/outputs/apk/release/app-armeabi.apk
build/app/outputs/apk/release/app-arm64.apk