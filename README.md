# ViPER4Android FX

ViPER4Android FX prebuilts and libraries.

* To include ViPER4Android FX, add this Makefile rule into your device tree's `device.mk`.

```Makefile
# ViPER4Android FX
PRODUCT_PACKAGES += \
    ViPER4AndroidFX
```

* And add these entries into your device tree's `audio_effects.xml`.

```Xml
    <library name="v4a_re" path="libv4a_re.so"/>
    <effect name="v4a_standard_re" library="v4a_re" uuid="90380da3-8536-4744-a6a3-5731970e640f"/>
```

## Credits

* [Iscle](https://github.com/iscle) and [Martmists](https://github.com/Martmists-GH) for their reverse engineering work
* [Thomas W.](https://github.com/pittvandewitt) and [Iscle](https://github.com/iscle) for developing the original application
* [Project Material](https://t.me/projectmaterial) for assisting with components used in the redesign
* [Aditya Raj](https://github.com/syntaxticsugr) by the [ViPER4Android Presets](https://github.com/syntaxticsugr/ViPER4Android-Presets) repository, used as a download source in the application
* [WSTxda](https://github.com/WSTxda) for [ViPER4Android FX Redesign (ViperFX RE)](https://github.com/WSTxda/ViperFX-RE-Releases)
