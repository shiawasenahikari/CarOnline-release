Latest Release
==============
[Download APK](https://raw.githubusercontent.com/shiawasenahikari/CarOnline-release/master/app-release.apk)

Change Log
==========

V1.3.3 (Build 20200812)
-----------------------
* Updated data interfaces according to server.
* Removed the [New Charge Log] function that is no longer used.
* Fixed: When the user manages only a few vehicles, in home page, the online/offline number in the pie chart will be displayed as decimal pattern (not integer).

V1.3.2 (Build 20190823)
-----------------------
* In Location Activity, added a [New Charge Log] function. This function is being tested at present.

V1.3.1 (Build 20190821)
-----------------------
* In Login Activity, added icons to the left of User Name and Password text boxes
* Fixed: Car icon shakes in Track Activity

V1.3.0 (Build 20190701)
-----------------------
* Fixed: In Chinese/Japanese environment, Message Detail Activity, the units of Start Fuel and
  Finish Fuel display incorrectly
* Upgraded network library to OKHttp 4.0

V1.2.5 (Build 20190620)
-----------------------
* Updated data interfaces according to server

V1.2.4 (Build 20190610)
-----------------------
* Fixed: In Chart Activity, when scaling X-axis after changing Start Time, X-axis's time values
  become incorrect
* Compressed the size of info window in Location Activity to improve experiences for small-screen
  mobile phones

V1.2.3 (Build 20190530)
-----------------------
* Added a [FOLLOW] button for the info window in Location Activity
* When following a car, you can finish it at any time

V1.2.2 (Build 20190520)
-----------------------
* Supported English
* Fixed some bugs cause crash
* Use a cooler style for pull-down-to-refresh and pull-up-to-load-more components in Messages &
  Search page

V1.2.1 (Build 20190510)
-----------------------
* Change-Log Activity supported night mode
* Improved the problem that texts in night mode cannot be seen clearly

V1.2.0 (Build 20190430)
-----------------------
* In home page, the drawer covers the title bar after you opened it
* From now you can view the change log (Menu→[About Car Online]→[VIEW CHANGE LOG])
* Added a bottom navigation bar and set up three entries: Home, Location, and Messages

V1.1.6 (Build 20190420)
-----------------------
* Minimum compatibility upgraded to Android 5.0
* Red point in home page displays only when you have new messages
* Added a "Filter by car" option for the message filter in Messages Activity

V1.1.5 (Build 20190410)
-----------------------
* Added message filter function in Messages Activity
* Added a side navigation drawer in home page, can do some quick operation here
* Removed the bottom status bar in Location Activity, and moved vehicle's real-time information to
  info window

Links
=====
* [OKHttp](https://github.com/square/okhttp)
* [Markwon](https://github.com/noties/Markwon)
* [FastJSON](https://github.com/alibaba/fastjson)
* [BubbleLayout](https://github.com/MasayukiSuda/BubbleLayout)
* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)
* [SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)
* [CustomActivityOnCrash](https://github.com/Ereza/CustomActivityOnCrash)

License
=======

    Copyright 2019 Hefei Xieli Instrument Control Tech Co., Ltd.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
