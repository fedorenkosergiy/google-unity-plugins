# google-unity-plugins

This repository is created to simplify google plugins integration to a unity project. All the content is copied from the [Google APIs for Unity archive](https://developers.google.com/unity/archive) page

## How does the integration look like

The simpliest way to integrate a plugins is to edit packages.json file.

```json
{
  "dependencies": {
    "com.google.external-dependency-manager": "https://github.com/fedorenkosergiy/google-unity-plugins.git?path=/resolver/com.google.external-dependency-manager-1.2.169",
    "com.google.firebase.analytics": "https://github.com/fedorenkosergiy/google-unity-plugins.git?path=/firebase/com.google.firebase.analytics-8.8.0",
    "com.google.firebase.app": "https://github.com/fedorenkosergiy/google-unity-plugins.git?path=/firebase/com.google.firebase.app-8.8.0",
    "com.google.firebase.crashlytics": "https://github.com/fedorenkosergiy/google-unity-plugins.git?path=/firebase/com.google.firebase.crashlytics-8.8.0",
    "com.google.firebase.remote-config": "https://github.com/fedorenkosergiy/google-unity-plugins.git?path=/firebase/com.google.firebase.remote-config-8.8.0"
  },
  "scopedRegistries": [
  ]
}
```
