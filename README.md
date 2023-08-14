# PROJETO RASTREAMENTO

Neste template você encontrará:

- [Expo](https://expo.dev/)
- [Expo Location](https://docs.expo.dev/versions/latest/sdk/location/)
- [MapView](https://docs.expo.dev/versions/latest/sdk/map-view/)

## Expo Location

    npx expo install expo-location

```json
{
  "expo": {
    "plugins": [
      [
        "expo-location",
        {
          "locationAlwaysAndWhenInUsePermission": "Allow $(PRODUCT_NAME) to use your location."
        }
      ]
    ]
  }
}
```

## MapView

Documentação completa [documentação](https://github.com/react-native-maps/react-native-maps)

    npx expo install react-native-maps
