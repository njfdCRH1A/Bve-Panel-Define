本插件由南局福段CRH1A制作，使用zbx1425的blockyATS制作。

内含：
ATO_enable_x86.dll
ATO_enable_x64.dll
ATO_enable.ini

使用说明：
0. 本插件需要搭配bve-autopilot使用。
1. 将ATO_enable.ini的atoenabled与tascbrake的值设置为与autopilot.ini中对应值相同
   即autopilot.ini中200 = atoenabled
   则ATO_enable.ini中为atoenabled =200
   （autopilot.ini中是反过来的所以没办法直接读取）
2. 将autopilot.ini中的 XX = break 删去
3. 在detailmodules中，bve-autopilot一定要放在TIMS之后，ATO_enable一定要放在bve-autopilot之后
   正确写法：
   ...
   ...
   ..\..\..\..\TIMS_new\TIMS_new_m.dll
   bve-autopilot.dll
   ATO_enable_x86.dll
   ...
   ...

南局福段CRH1A
Bilbili：https://space.bilibili.com/400513547
GitHub：https://github.com/njfdCRH1A

zbx1425
Bilbili：https://space.bilibili.com/12979372
GitHub：https://github.com/zbx1425
BlocklyAts：https://github.com/zbx1425/BlocklyAts