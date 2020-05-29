# macOSMavericksTheme
A Theme for macOS Mojave/Catalina to make it look like macOS Mavericks


# ATTENTION - READ THIS FIRST
*If you are on macOS 10.15.3+, please note there has been a case reported where the entire finder was bricked afterwards so I EXTREMELY recommend a backup if you still plan to do this, and if problems arise where you can't revert to the backed up files afterwards, please contact me on reddit (u/MoonPadUSer) there are ways using the recovery mode to place those files back which should recover your machine to a working state*

# 
# Preparation
1. Download this repo (green button -> download as zip)
2. Disable SIP
3. open terminal, and type "sudo mount -uw /", (this is you can edit the system files) it will ask you to enter your admin password, please note, when you type it in, the letters won't appear. 
4. Download macOSLucidaGrande (at the time of writing, it's not available for macOS Catalina): https://github.com/LumingYin/macOSLucidaGrande/releases
5. Download LiteIcon: https://freemacsoft.net/liteicon/
6. Download cDock (it's not free tho): https://cdock.macenhance.com/
7. If you downloaded cdock, download this theme: https://www.deviantart.com/jsteweii/art/Mavericks-783845879

# Installation
1. Go into System Preferences -> Accessibility -> Display -> Check "Reduce Transparency"
2. Copy these two files: SystemAppearance.car and Assets.car from "/System/Library/CoreServices/SystemAppearance.bundle/Contents/Resources/" two somewhere you won't lose them
3. Copy the files SystemAppearance.car Assets.car from this repo (you downloaded it earlier) to "/System/Library/CoreServices/SystemAppearance.bundle/Contents/Resources/" (replace the existing ones)
4. open cdock and import the theme you downloaded and use it (just select it in the dropdown menu and then restart dock)
5. now comes the annoying part, replacing the icons, in this repo there are all .icns files (.icns) that I was able to find,
   open LiteIcon and drag the correct .icns from this repo to the coresponding one in LiteIcon, no worries, LiteIcon can reset them
   later easily.
 
If there are any problems, don't hesitate to contact me on Reddit: https://reddit.com/user/MoonPadUSer/


