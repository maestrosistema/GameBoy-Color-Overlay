# GameBoy Color Overlay

![My Image](ow.jpg)

This is an updated version of the "Big" version of my GameBoy Color overlay for RetroArch I made back in 2017 (<a href="https://forums.libretro.com/t/gameboy-touch-overlay/12469">Libretro Forums</a>).

I've updated it for modern 21:9 (2400x1080) screen Android devices and added animation to all the buttons.

I'm open to suggestions!

# Installation

<b>1.</b> Download latest release.

<b>2.</b> Extract and copy the <b>gbc</b> folder inside: 
<i>"RetroArch/overlays/misc"</i> (Or any folder you set for overlays in RetroArch settings) and overwrite if asked.

<b>3.</b> Open RetroArch and boot any GB or GBC game (the Gambatte core is recommended), go into the menu and change these settings:

<b>Video:</b>
- Enable fullscreen over notch in Android devices <b>"ON"</b>

<b>Video -> Scaling:</b>
- Integer Scale <b>"OFF"</b>
- Aspect Ratio <b>"Custom"</b>
- Custom Aspect Ratio (X Position) <b>"0"</b>
- Custom Aspect Ratio (Y Position) <b>"825"</b>
- Custom Aspect Ratio (Width) <b>"1080"</b>
- Custom Aspect Ratio (Height) <b>"972"</b>
- Crop Overscan (Restart Required) <b>"ON"</b>

<b>On-Screen Display -> On-Scren Overlay:</b>
- Display Overlay <b>"ON"</b>
- Auto-Scale Overlay <b>"OFF"</b>
- Overlay Preset <b>"gbc"</b> (Select any variant of the <b>gbc.cfg</b> file found in <b>gbc</b> folder)
- Overlay Opacity <b>"1.00"</b>
- (Portrait) Overlay Scale <b>"1.000"</b>
  
<b>4.</b> Go to <b>Quick Menu -> Ovverides</b> and <b>Save Core Overrides</b> then restart RetroArch.
 
<b>5.</b> Play!

<b>NOTE:</b>
<b>THESE SETTINGS ARE OPTIMAL FOR 21:9, 2400x1080 RESOLUTION PHONES, FOR DIFFERENT ASPECT RATIO AND RESOLUTIONS YOU MAY HAVE TO TWEAK: CUSTOM ASPECT RATIO (X POSITION), CUSTOM ASPECT RATIO (Y POSITION), (PORTRAIT) OVERLAY ASPECT ADJUSTMENT SETTINGS AND MAYBE OTHERS.</b>
  
<b>Optional Settings:</b>
  
If you use Gambatte core i reccomend this core options:
- GB Colorization <b>"Internal"</b>
- Internal Palette <b>"GB - DMG"</b>
- Color Correction <b>"GBC Only"</b>
- Color Correction Mode <b>"Accurate"</b>
- Interframe Blending <b>"LCD Ghosting (Accurate)"</b>
- Emulated Hardware (Restart Required) <b>"Auto"</b>
- Use Official Bootloader (Restart Required) <b>"ON"</b> (If you have BIOS files)
  
I also reccomed using a <b>Video Shader</b> like <b>dot.glslp</b> found in <i>"shaders_glsl/handheld/"</i> (Or <i>"shadrs_slang/handheld/dot.slangp"</i> if you use Vulkan video driver)

# Usage

![My Image](usage.png)

..WIP...

<b>NOTE: Rewind and AI Service must be configured in RA settings to make them work in the overlay!</b>

Touch the GameBoy Color (or the Libretro RetroArch logo if you use the alternative background) logo to make all function buttons invisible (they can stil be pressed), touch again to make them visible.

# Donation
If you like my work, please consider a small donation.

You can donate with <a href="https://paypal.me/maestrosistema?country.x=IT&locale.x=it_IT"><b>PayPal</b></a> or <a href="https://ko-fi.com/maestrosistema"><b>Ko-Fi</b></a>.

Thank You!

# Special Thanks
RetroArch Team

# Disclaimer
<b>Nintendo GameBoy</b> is a trademark of <b>Nintendo Co., Ltd</b>

<b>Android</b> is a trademark of <b>Google LLC</b>
