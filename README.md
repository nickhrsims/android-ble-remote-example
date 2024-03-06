![badge][badge-android]

# Android Remote (Bluetooth Low-Energy Example Project)

A demonstration project intended to work with peripherals based on my ESP32 [utility library].

Projects based on JUUL Labs' [SensorTag] project.

## Android

The App can be built and installed via [Android Studio], or via command line by executing:

```
./gradlew installDebug
```

# License

## Modified & Original Components

```
Copyright 2024 Nicholas H.R. Sims

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

```

## JUUL Labs' Original Work (SensorTag)

```
Copyright 2020 JUUL Labs, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

[Android Studio]: https://developer.android.com/studio
[Kable]: https://github.com/JuulLabs/kable
[SensorTag]: https://github.com/JuulLabs/sensortag
[utility library]: https://github.com/nickhrsims/esp-idf-lib/tree/main/components/neil_ble_gatts
[badge-android]: http://img.shields.io/badge/platform-android-6EDB8D.svg?style=flat
[badge-jvm]: http://img.shields.io/badge/platform-jvm-DB413D.svg?style=flat
[badge-linux]: http://img.shields.io/badge/platform-linux-2D3F6C.svg?style=flat
