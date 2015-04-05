Demo Template
=============

Android project template I use for all *Demo projects. Has basic gradle configuration for adding
the Android support and app compat libraries as well as having gradle wrapper ready to go.

When using this, I simply add an additional package under src/com/lillicoder/demo and move DemoActivity.java there.
I then edit the AndroidManifest.xml file to have the proper package entry. I also will change the app_name value
in res/values/strings.xml to avoid having 'DemoTemplate' show in the app drawer.

As with my other demos, I modify the .gitignore file to exclude IDE specific files and files that should
be generated locally (e.g. local.properties).

License
-------

Copyright 2014 Scott Weeden-Moody

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this project except in compliance with the License.
You may obtain a copy of the License at
 
    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.