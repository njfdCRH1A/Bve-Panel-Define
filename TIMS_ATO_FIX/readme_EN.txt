This plug-in is made by 南局福段CRH1A, using blockyATS code by zbx1425.

Contains:
ATO_enable_x86.dll
ATO_enable_x64.dll
ATO_enable.ini

Instructions for use:
0. This plugin needs to be used with bve-autopilot.
1. Set the values of atoenabled and tascbrake in ATO_enable.ini to be the same as the corresponding values in autopilot.ini
    i.e. 200 = atoenabled in autopilot.ini
    Then ATO_enable.ini is atoenabled =200
    (It is reversed in autopilot.ini, so there is no way to read directly)
2. Delete the XX = break in autopilot.ini
3. In detailmodules.txt, bve-autopilot must be placed after TIMS, and ATO_enable must be placed after bve-autopilot
    Correct format:
    ...
    ...
    ..\..\..\..\TIMS_new\TIMS_new_m.dll
    bve-autopilot.dll
    ATO_enable_x86.dll
    ...
    ...

南局福段CRH1A
Bilbili: https://space.bilibili.com/400513547
GitHub: https://github.com/njfdCRH1A

zbx1425
Bilbili: https://space.bilibili.com/12979372
GitHub: https://github.com/zbx1425
BlocklyAts: https://github.com/zbx1425/BlocklyAts