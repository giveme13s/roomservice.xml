<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <remote  name="robbie" fetch="https://github.com/RobbieL811/" />
  <remote  name="sm" fetch="https://github.com/SaberMod/" />
	<remote  name="ubertc" fetch="https://bitbucket.org/UBERTC/" />
	
  <project path="prebuilts/gcc/linux-x86/arm/arm-eabi-4.9-sm-robbie" name="Sabermod" remote="robbie" revision="arm-eabi-4.9" />
  <project path="prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.8-sm" name="arm-androideabi-4.8" remote="sm" revision="master" />
  <remove-project name="platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.8" />
  <project path="prebuilts/gcc/linux-x86/arm/arm-eabi-4.8.ORG" name="platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.8" groups="pdk,linux,arm" />
  <remove-project name="platform/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.8" />
  <project path="prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.8.ORG" name="platform/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.8" groups="pdk,linux,arm" />

  <project name="android_vendor_oppo" path="vendor/oppo" remote="du" revision="lollipop-caf" />

  <project name="android_kernel_oneplus_msm8974" path="kernel/du/msm8974" remote="du" revision="lollipop-caf" />
  <project name="android_device_oneplus_bacon" path="device/oneplus/bacon" remote="du" revision="lollipop-caf" />
  <project name="android_device_qcom-common" path="device/qcom/common" remote="du" revision="lollipop-caf" />
  <project name="android_device_oppo_msm8974-common" path="device/oppo/msm8974-common" remote="du" revision="lollipop-caf" />
  <project name="android_device_oppo_common" path="device/oppo/common" remote="du" revision="lollipop-caf" />

  <!-- arm-eabi-* -->
  <project path="prebuilts/gcc/linux-x86/arm/arm-eabi-4.8-uber" name="arm-eabi-4.8" remote="ubertc" revision="master" />
  <project path="prebuilts/gcc/linux-x86/arm/arm-eabi-4.9-uber" name="arm-eabi-4.9" remote="ubertc" revision="master" />
  <project path="prebuilts/gcc/linux-x86/arm/arm-eabi-5.1-uber" name="arm-eabi-5.1" remote="ubertc" revision="master" />
  <project path="prebuilts/gcc/linux-x86/arm/arm-eabi-6.0-uber" name="arm-eabi-6.0" remote="ubertc" revision="master" />

  <!-- arm-linux-androideabi-* -->
  <project path="prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.8-uber" name="arm-linux-androideabi-4.8" remote="ubertc" revision="master" />
  <project path="prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9-uber" name="arm-linux-androideabi-4.9" remote="ubertc" revision="master" />
</manifest>
