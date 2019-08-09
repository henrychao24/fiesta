![浇花](https://user-images.githubusercontent.com/16383391/62771766-8ba01980-bad0-11e9-8d7e-c6ab18482f60.gif)     ![兔子](https://user-images.githubusercontent.com/16383391/62771778-90fd6400-bad0-11e9-9709-7958374777c5.gif)

![程序员看到自己程序运行成功的那一刻](https://user-images.githubusercontent.com/16383391/62771806-a07cad00-bad0-11e9-9c8e-bcfa75be5804.gif)

# Fiesta 📺 (work-in-progress 👷🔧️👷‍♀️⛏)

**This is not an official Google product**

Fiesta is a **work-in-progress** Joking Android app. It is still in its early stages of development and currently
only contains two pieces of UI. It is under heavy development.

## Android development

Fiesta is an app which attempts to use the latest cutting edge libraries and tools. As a summary:

 * Entirely written in [Kotlin](https://kotlinlang.org/)
 * Uses [RxJava](https://github.com/ReactiveX/RxJava) 2
 * Uses all of the [Architecture Components](https://developer.android.com/topic/libraries/architecture/): Room, LiveData and Lifecycle-components
 * Uses [dagger-android](https://google.github.io/dagger/android.html) for dependency injection

## Development setup

First off, you require the latest Android Studio 3.0 (or newer) to be able to build the app.

### Code style

This project uses [ktlint](https://github.com/pinterest/ktlint), provided via
the [spotless](https://github.com/diffplug/spotless) gradle plugin, and the bundled project IntelliJ codestyle.

If you find that one of your pull reviews does not pass the CI server check due to a code style conflict, you can
easily fix it by running: `./gradlew spotlessApply`, or running IntelliJ/Android Studio's code formatter.

## Contributions

If you've found an error in this sample, please file an issue.

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request. Since this project is still in its very early stages,
if your change is substantial, please raise an issue first to discuss it.

## License

```
Copyright 2017 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements. See the NOTICE file distributed with this work for
additional information regarding copyright ownership. The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License. You may obtain a copy of
the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations under
the License.
```
