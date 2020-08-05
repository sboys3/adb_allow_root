## Allow ADB Root Magisk Module
This module allows you to execute <code>adb root</code> on production builds of android. This module is for arm64 only. It was built from the Android 10 AOSP source with checks for a debugging build removed. Other versions of android will likely work fine, but I have not tested them. It works by replacing adbd with a modified version. All security checks are left in place in adbd, so this module will not make your devices completely insecure.

To install download adb_allow_root.zip from releases and install it using the modules section of the Magisk app.