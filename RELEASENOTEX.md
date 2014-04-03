<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#  KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->
# Release Note X


### 0.3.0 Mon Jan 27 2014 16:41:49 GMT+0800 (CST)
 *  added releasenotex.md
 *  CB-5719 Updated version and RELEASENOTES.md for release 0.3.0
 *  CB-5592 Add a comment explaining why we set MIME only for file:
 *  CB-5592 Android - Add MIME type to Intent when opening file:/// URLs
 *  CB-5658 Update license comment formatting of doc/index.md
 *  CB-5658 Add doc.index.md for InAppBrowser plugin
 *  CB-5658 Delete stale snapshot of plugin docs
 *  CB-5594 Add disallowoverscroll option.
 *  CB-5595 Rename "toolbarbarpostion" -> "toolbarposition"
 *  CB-5595 Fixed the positioning and autoresizing for certain rotation scenarios.
 *  CB-5595 Add toolbarposition=top option.
 *  Apply CB-5193 to InAppBrowser
 *  CB-5593 iOS: Make InAppBrowser localizable
 *  CB-5591 Change window.escape to encodeURIComponent
 *  sync cordova-mobile-spec test into cordova-plugin-inappbrowser


## 0.3.1 (Fri Feb 28 2014)


 *  CB-5980 Updated version and RELEASENOTES.md for release 0.3.1
 *  Add missing import for previous commit
 *  CB-5756: Android: Use WebView.evaluateJavascript for script injection on Android 4.4+
 *  Didn't test on ICS or lower, getDrawable isn't supported until Jellybean
 *  WTF? ubuntu got automerged twice
 *  add ubuntu platform
 *  Adding CC-A-2.5 Notice for Assets, modifying plugins to use resources
 *  Adding the buttons
 *  Adding drawables to the inAppBrowser.  This doesn't look quite right, but it's a HUGE improvement over the previous settings
 *  CB-5756: Add missing import
 *  CB-5756: Android: Use WebView.evaluateJavascript for script injection on Android 4.4+
 *  Delete stale test/ directory
 *  Remove _alive from InAppBrowser.js since it didn't catch the case where the browser is closed by the user.
 *  CB-5733 Fix IAB.close() not working if called before show() animation is done
 *  CB-5719 Incremented plugin version on dev branch.


## 0.3.2 (Wed Mar 19 2014)


 *  issue 7: Change numExpectedRedirects from 3 to 2 to avoid displaying alerts.
 *  loadstart called multiple times because of 'www.google.com' redirect, so add expectredirect count in test
 *  Incremented plugin version on dev branch to 0.3.2-dev


## 0.3.3 (Thu Apr 03 2014)


 *  [iOS] issue 1:Sync cordova manual tests and update the descriptions of expected test results.
 *  Incremented plugin version on dev branch to 0.3.3-dev
