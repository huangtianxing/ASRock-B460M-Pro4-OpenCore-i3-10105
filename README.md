# PC Components

```
Board:    AsRock B460M Pro4
CPU:      Intel® Core™ i3-10105
VGA:      Intel UHD Graphics 630
RAM:      Team Vulcan Z DDR4 8GB 2666MHz
SSD:      Western Digital Blue 500GB SSD WDS500G2B0A
Case:     ValueTop Mania X3
PSU:      Corsair CV450 450W 80+ Bronze certified PSU
```

#Hackintosh

# macOS Big Sur + OpenCore (0.6.9)

- https://dortania.github.io/OpenCore-Desktop-Guide

# Works

- Sleep
- Wake
- Audio
- Ethernet
- DisplayPort + HDMI
- All USB ports (Full 3.0 + 2.0 + type C)

# Result

![Info](/images/info.png)

# Note

Please change MLB, SystemSerialNumber, SystemUUID as your desire.

```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ROM</key>
    <data>xxxxxxxx</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemProductName</key>
    <string>iMac20,1</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```

