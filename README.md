<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <remote  name="aosp"
           fetch=".."
           review="https://android-review.googlesource.com/" />
  <default revision="master"
           remote="aosp"
           sync-j="4" />
  <project path="adk1/board" name="device/google/accessory/arduino" />
  <project path="adk1/app" name="device/google/accessory/demokit" />
  <project path="adk2012/app" name="device/google/accessory/adk2012" />
  <project path="adk2012/board" name="device/google/accessory/adk2012_demo" />
  <project path="external/ide" name="platform/external/arduino-ide" />
  <project path="external/toolchain" name="platform/external/codesourcery" />
</manifest>
