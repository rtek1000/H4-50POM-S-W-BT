# H4-50POM-S-W-BT
H4-50POM-S/W/BT - IP Camera (Manufactured by EsunStar co., LTD)

![img](https://raw.githubusercontent.com/rtek1000/H4-50POM-S-W-BT/refs/heads/main/Img/IP_Cam1.png)

- Model Number: JH4W-Q-180X
- Brand Name: YUCHENG
- Viewing Angle: 60°
- Power Supply(V): 12Vdc
- Power Consumption(W): 2W
- Connectivity: IP/Network Wireless/Cable
- Sensor: CMOS
- Sensor Brand: Omnivision
- Lens (mm): 3.3-97mm
- Optical Zoom: 30x
- Digital Zoom: 6x
- Megapixels: 4MP
- Video Compression Format: H.264, H.265
- Minimum Illumination(Lux): 0.3
- Certification: CE
- Supported Operating Systems: Windows Vista, Windows 7, Windows 2008

-----

Smart function
- Support intelligent detection functions such as regional intrusion detection, cross-border detection, and motion detection.
- Support the function of resuming transmission after disconnection to ensure that the video is not lost, and cooperate with Smart NVR to realize the secondary intelligent retrieval, analysis and concentrated playback of event video.
- Support timing tasks, one-key to Home position
- Supports H.265 high-efficiency compression algorithm, which can greatly save storage space.

Image related
- Support up to 2560*1440@25fps HD picture output.
- Support starlight level ultra-low illumination, 0.03Lux/F1.8 (color), 0.01Lux/F1.8 (black and white), 0 Lux with IR.
- Support 30X zoom and 6X digital zoom(Gesture or button control).
- Support three-stream technology, each stream can be independently configured with resolution and frame rate.
- Supports wide dynamic range up to 60dB, suitable for backlit environment monitoring.
- Support 3D digital noise reduction, strong light suppression.

-----

How to Turn ON/OFF Tracking
- Button Star Track for Turn on Corridor mode tracking
- Button Stop Track for Turn off Corridor mode tracking

-----

You can use Preset Turn ON/OFF tracking too:
- 254+call for turn on auto zoom tracking
- 254+set for turn off auto zoom tracking

-----

Basic parameters (M-H4W-Y4X)

- Chip solution: Hisilicon

- Minimum illumination: Color:0.03Lux @(F1.8,AGC ON);B/W:0Lux @(F1.8,AGC ON),0 Lux with IR
- Resolution frame rate:
- - Main stream:25fps(2560×1440,2304×1296,1920×1080,1280×960,1280×720)
- - Substream:25fps(800×448,640×360,352×288)
- Video Encoding format: H.265+/H.265/H.264
- Audio Encoding format: G711
- IR night vision: Support
- White balance: Incandescent lamp, warm light, fluorescent lamp, natural light, manual white balance, auto white balance, lock white balance
- Anti-flash mode: 50HZ, 60HZ, OFF
- Aperture type: Manual aperture, auto iris
- Exposure time: Auto, 1/25, 1/35, 1/40, 1/50, 1/60, 1/100, 1/120, 1/240, 1/480, 1/960, 1/1000, 1/2000, 1/4000, 1/8000, 1/10000, 1/100000
- Gain: Auto, 6Db, 12dB, 18dB, 24dB, 30dB, 36dB, 42dB
- 3D noise reduction: Auto, weak, general, strong
- BLC: OFF/ON
- WDR: Auto, weak, general, strong
- IR Image mode: Standard mode, Face without exposure, License plate mode
- Digital ZOOM: Support 6X digital zoom
- Focus mode: Fully automatic, semi-automatic, manual

LENS
- focal length: 3.3-97mm, 30X Optics ZOOM, support 6x digital zoom, Total 180x zoom
- Zoom speed: about 6 seconds (optical, wide-angle-telephoto)
- Horizontal-viewing angle: About 63-2 degrees (wide angle-telephoto)
- Close-up distance: 1.5-100meters (wide angle-telephoto)
- Number of aperture: F1.4-F2.5

Features
- Smart Detect: Face and humaniod detection, area intrusion detection, cross-border detection, entering area detection, fast motion detection, motion detection, video occlusion detection
- Smart record: Motion detection recording, humanoid detection recording, timing recording
- Smart image Enhance: 60DB WDR, Strong light suppression, face overexposure prevention, smart infrared
- Smart code: Smart 265/264,Dynamic code stream, fixed code stream, low code stream
- Proportional zoom: Support
- Power-Off Memory: Support

Network
- Network protocol: IPv4, HTTP, HTTPS, FTP, SMTP, UPnP, SNMP, DNS, DDNS, NTP, RTSP, RTCP, RTP, TCP/IP, DHCP, PPPoE, RTSP
- Application Programming: Support open API for software integration, support standard protocol (ONVIF), support Hikvision protocol and third-party management platform access
- Browser: Support IE8+, Chrome31+, Firefox30+, Safari8.0+ browser
- preview videos: MAX 3 user sametime preview
- Wireless wifi: support wifi6
- Time: time.windows.com, time.nist.gov, time.kriss.re.kr, time.nuri.net etc., Network Time Protocol

Alarm
- Snapshot: Support Remote timing snapshot
- Motion detection: At most 4 respective regions
- Humanoid detection: Support Humanoid detection record, snapshot, alarm ouput, tracking
- Alarm linkage: E-mail Alarm and Send with Picture, Save Picture on the FTP Server(not support video), Relay out, alarm send message to mobile phone APP

Record
- Record: Support computer local record, Browser record, P2P client software record, NVR record
- SD card: Not support

Interface
- Power interface: DC12V
- Network: RJ45 10Base-T/100Base-TX, WIFI
- Audio: Mic Build in camera, and support one 3W speaker
- SD card: MAX support 512GB
- Reset button: one external reset button

General specification
- Power: Max 3W
- Working: -35℃-65℃; humidity is less than 90%
- Protection grade: IP66 (When mounted in the specific cabinet); TVS 4000V lightning protection, anti-surge, anti-surge, in line with GB/T17626.5 level four standards
- Weight: 0.3KG

![img](https://raw.githubusercontent.com/rtek1000/H4-50POM-S-W-BT/refs/heads/main/Img/IP_Cam3.png)

-----

Note: This library is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE
- Information obtained from the public announcement of the product accessed in January 2025:
- - https://www.aliexpress.com/item/1005008201046957.html

-----

# Usage Notes:
- The camera's PTZ setting must be left activated at 57600 baud and Pelco D type (address 1), otherwise the interface board will not recognize the commands and the optical zoom will not work.
- The main board has connectors (CN4, CN5) for 5-wire horizontal and vertical motors (12V positive power derived from the power input after protection diode). These connectors (CN4, CN5) only work when the camera is powered, but after initialization the PTZ controls do not drive these motors.
- Only the Pelco D output (9600 baud) available on the CN9 connector sends signal in TX. The Sony Visca output (9600 baud) does not work.
- Wired connection (RJ45) has priority over wireless connection (Wi-Fi)
- Sometimes the PTZ stop command may not be recognized by the Zoom/Focus controller interface. In this case, it is necessary to press the button again to send a new stop command. 
  
-----

## Pelco D output sample
(Captured using Hercules SETUP utility program)

Note 1: All '{xx}' data is in hexadecimal value.

Note 2: The function command is sent only once when the button is pressed.

Note 3: The stop command is sent when the button is released.

Note 4: Pelco D basic protocol: {Header/Sync: 0xFF} {Addr} {Cmd1} {Cmd2} {Dat1} {Dat2} {Checksum}

Note 5: 'Step' is a parameter of the controller screen

### Data sent when control is done via browser:
(http://'ip_camera_address') [ip_camera_address: 192.168.1.112 etc]

- Stop:
- - {FF}{01}{00}{00}{00}{00}{01}
- Up:
- - {FF}{01}{00}{08}{00}{06}{0F} (step 1)
- - {FF}{01}{00}{08}{00}{0C}{15} (step 2)
- - {FF}{01}{00}{08}{00}{3F}{48} (step 10)
- Down:
- - {FF}{01}{00}{10}{00}{06}{17} (step 1)
- Left:
- - {FF}{01}{00}{04}{06}{00}{0B} (step 1)
Right:
- - {FF}{01}{00}{02}{06}{00}{09} (step 1)
- Zoom+:
- - {FF}{01}{00}{20}{00}{00}{21}
- Zoom-:
- - {FF}{01}{00}{40}{00}{00}{41}
- Focus+:
- - {FF}{01}{01}{00}{00}{00}{02}
- Focus-:
- - {FF}{01}{00}{80}{00}{00}{81}
- Iris+:
- - {FF}{01}{02}{00}{00}{00}{03}
- Iris-:
- - {FF}{01}{04}{00}{00}{00}{05}
- Preset1 (set):
- - {FF}{01}{00}{03}{00}{01}{05}
- Preset1 (goto):
- - {FF}{01}{00}{07}{00}{01}{09}
- Preset1 (erase):
- - {FF}{01}{00}{05}{00}{01}{07}
- Preset2 (set):
- - {FF}{01}{00}{03}{00}{02}{06}
- Preset2 (goto):
- - {FF}{01}{00}{07}{00}{02}{0A}
- Preset2 (erase):
- - {FF}{01}{00}{05}{00}{02}{08}


### Data sent when control is done via VMS program:
(XMEye VMS v2.0.1.18; Windows executable program)

- Stop:
- - {FF}{01}{00}{00}{00}{00}{01}
- Up:
- - {FF}{01}{00}{08}{00}{06}{0F} (step 1)
- - {FF}{01}{00}{08}{00}{32}{3B} (step 8)
- Down:
- - {FF}{01}{00}{10}{00}{06}{17} (step 1)
- Left:
- - {FF}{01}{00}{04}{06}{00}{0B} (step 1)
- Right:
- - {FF}{01}{00}{02}{06}{00}{09} (step 1)
- Up-L:
- - {FF}{01}{00}{04}{06}{00}{0B} (followed by) {FF}{01}{00}{08}{00}{06}{0F} (step 1)
- Up-R:
- - {FF}{01}{00}{02}{06}{00}{09} (followed by) {FF}{01}{00}{08}{00}{06}{0F} (step 1)
- Dn-L:
- - {FF}{01}{00}{04}{06}{00}{0B} (followed by) {FF}{01}{00}{10}{00}{06}{17} (step 1)
- Dn-R:
- - {FF}{01}{00}{02}{06}{00}{09} (followed by) {FF}{01}{00}{10}{00}{06}{17} (step 1)
- Zoom+:
- - {FF}{01}{00}{20}{00}{00}{21}
- Zoom-:
- - {FF}{01}{00}{40}{00}{00}{41}
- Focus+:
- - Does not send command, just sends stop (BUG)
- Focus-:
- - Does not send command, just sends stop (BUG)
- Iris+:
- - Does not send command, just sends stop (BUG)
- Iris-:
- - Does not send command, just sends stop (BUG)
- Preset1 (set):
- - {FF}{01}{00}{03}{00}{01}{05}
- Preset1 (goto):
- - {FF}{01}{00}{07}{00}{01}{09}
- Preset1 (erase):
- - {FF}{01}{00}{05}{00}{01}{07}
- Preset2 (set):
- - {FF}{01}{00}{03}{00}{02}{06}
- Preset2 (goto):
- - {FF}{01}{00}{07}{00}{02}{0A}
- Preset2 (erase):
- - {FF}{01}{00}{05}{00}{02}{08}
