
Android SwipeRefreshListFragment Sample
===================================

A sample which shows how to use `SwipeRefreshLayout` to add
'swipe-to-refresh' gesture to a ListView, enabling the ability to trigger a refresh
from swiping down on that view.

Introduction
------------

A sample which shows how to use
[SwipeRefreshLayout][1] within a `ListFragment` to add the 'swipe-to-refresh'
gesture to a `ListView`. The sample provides this functionality by defining a
re-usable `SwipeRefreshListFragment` class.

The sample displays a list of cheeses. When the user initiates a downward swipe,
that list refreshes with randomly generated items. Selecting the `Refresh`
action from the action bar also refreshes the list.

[1]: https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html

Pre-requisites
--------------

- Android SDK v23
- Android Build Tools v23.0.3
- Android Support Repository

Screenshots
-------------

<img src="screenshots/refresh.png" height="400" alt="Screenshot"/> 

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

- Google+ Community: https://plus.google.com/communities/105153134372062985968
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-SwipeRefreshListFragment

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2014 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
