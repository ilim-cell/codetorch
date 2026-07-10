# Developer "docs" and links

This collection of links provides information for developers who want to contribute to or extend the functionality of PolyOS 7.

## Core everyday development

### Using the PolyOS 7 SDK
XappWindow is a framework for creating custom applications for PolyOS 7. It uses x-y coordinate math tracking to prevent you from creating redundant clones that are hard to manage and are unoptimized for the enviroment. A full step-by-step guide can be found, a starter app template code and a Figma template downloaded at the [XappWindow 3.0 documentation](https://codetorch.net/en/projects/106363).

### Developer options
Developer mode will enable ugly debugging and probably will crash mobile devices. Aside from that, developer mode will allow unsafe commands to run without any confirmation, install any app through sideloading, unlock a developer menu in the Settings app, and enable cloud-based and root debugging. You should not enable developer mode unless you are a developer or advanced user who understands the risks involved. Enabling developer mode may cause instability or unexpected behavior in your system. To enable developer mode, open the Settings app, navigate to the "System/General" section, and toggle the "Developer Mode" option, then select "OK".

## Boot options

Try these options in this order:

### Using BIOS
Reboot your instance of PolyOS 7 and press the [ENTER] key to enter the BIOS. The BIOS allows you to configure various settings related to your system's hardware and boot process. You can navigate through the BIOS using mouse and keyboard keys and make changes to settings such as boot config, terminal, safe mode, recovery, RAM configuration, and hardware configuration.

### Using safe mode
Safe mode prevents non-essential software from booting, allowing you to troubleshoot issues with your PolyOS 7 installation. To access safe mode, reboot your instance of PolyOS 7 and press the [ENTER] key when prompted. Then, using your mouse, select "Enter safe mode".

### Using PolyOS Recovery
If you encounter issues with your PolyOS 7 installation, you can use the PolyOS Recovery feature to restore your system to a working state. To access PolyOS Recovery, reboot your instance of PolyOS 7 and press the [ENTER] key when prompted. Then, using your mouse, select "Enter recovery mode". This will take you to the recovery options where you can choose to restore your system or perform other recovery actions.

### Driver Settings
Driver Settings is a function accessed from within BIOS that allows you to configure various settings related to your system's hardware drivers. To access Driver Settings, reboot your instance of PolyOS 7 and press the [ENTER] key when prompted. Then, using your mouse, select "Driver Settings". This will take you to the driver configuration options where you can adjust settings for your system's hardware drivers.

> [!CAUTION]
> USING DRIVER SETTINGS WILL REPLACE AND REINSTALL ANY AND ALL OF YOUR EXISTING DRIVERS. DO NOT USE THIS TOOL UNLESS YOU KNOW WHAT YOU ARE DOING.
> The Driver Settings tool allows you to delete, install, or replace system drivers used for booting OSes using BIOS. Additional drivers can add functionality and be referenced by third party code. This tool may also be used to delete and reinstall a non-functional driver, and/or change configuration with existing ones. THIS ~~CAN~~ WILL BREAK YOUR SYSTEM IF YOU DO NOT KNOW WHAT YOU ARE DOING. USE AT YOUR OWN RISK.


## Danger Zone

### Accessing Super-Secret Beta
Super-Secret Beta is a function for users who want the bleeding edge of PolyOS 7 development. To access Super-Secret Beta, first enable developer mode and locate the option in the dev menu. You may have to reboot to BIOS to enable the function.

> [!NOTE]
> The documentation intentionally will not discuss the contents of Super-Secret Beta, as it is intended for advanced users and developers who want to test new features and provide feedback.
> The documentation also will not provide any further detailed instructions on how to enable Super-Secret Beta.
> Note that you shouldn't use a save code when testing Super-Secret Beta.

> [!CAUTION]
> Super-Secret Beta is intended for advanced users and developers who want to test new features and provide feedback. If you are a regular user, DO NOT enable Super-Secret Beta, as it may cause instability or unexpected behavior in your system. Some of the features are intentionally left undocumented and issues that are created on GitHub will be closed as "Won't fix". Use of Super-Secret Beta is at your own risk, and you should be prepared to troubleshoot any issues that may arise.

### PolyScript
PolyScript is an experimental scripting environment currently in beta.

> [!CAUTION]
> **CRITICAL STABILITY WARNING:** PolyScript is highly unstable. Regardless of whether you are a developer or a regular user, DO NOT use PolyScript. For safety reasons, the method to access PolyScript is entirely undocumented and completely unsupported, even moreso than Super-Secret Beta.
> By attempting to locate, access, or execute PolyScript, you assume 100% liability for any resulting system failure, data corruption, or hardware instability. The development team provides zero support, zero documentation, and zero liability for this feature. Proceeding completely voids any expectation of system stability.
