# Carthage support for [YandexMapKit](https://tech.yandex.ru/maps/mapkit/)

# Usage

Add lines to Cartfile

```
binary "https://raw.githubusercontent.com/alphatroya/yandex-map-carthage/master/YandexRuntime.json"
binary "https://raw.githubusercontent.com/alphatroya/yandex-map-carthage/master/YandexMapKit.json"
binary "https://raw.githubusercontent.com/alphatroya/yandex-map-carthage/master/YandexMapKitPlaces.json"
```

Set `-ObjC` parameter in the `Other linker flags` project phases settings.

Additionally these frameworks are needed to be added to the project:

- "OpenGLES",
- "CoreFoundation",
- "Security",
- "CoreTelephony",
- "CoreLocation",
- "GLKit",
- "CoreGraphics",
- "SystemConfiguration",
- "CoreMotion"
- "resolv",
- "c++"
