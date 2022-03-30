このプラグインは南局福段CRH1A 作ったものです，zbx1425のblockyATSで作られました。
（Google翻訳を使用してください、いくつかの不正確さのために私を許してください）
含まれています：
ATO_enable_x86.dll
ATO_enable_x64.dll
ATO_enable.ini

使用説明書：
0.このプラグインはbve-autopilotで使用する必要があります。
1. ATO_enable.iniのatoenabledとtascbrakeの値を、autopilot.iniの対応する値と同じになるように設定します
   つまり、200=autopilot.iniでatoenabled
   次に、ATO_enable.iniはatoenabled=200になります
   （autopilot.iniが逆になっているため、直接読み取る方法はありません）
2. autopilot.iniの XX = break を削除してください
3. detailmodules.txtでは、bve-autopilotはTIMSの後に配置する必要があり、ATO_enableはbve-autopilotの後に配置する必要があります
   正しい形式：
   ...
   ...
   ..\..\..\..\TIMS_new\TIMS_new_m.dll
   bve-autopilot.dll
   ATO_enable_x86.dll
   ...
   ...

リンク：
南局福段CRH1A
Bilbili：https://space.bilibili.com/400513547
GitHub：https://github.com/njfdCRH1A

zbx1425
Bilbili：https://space.bilibili.com/12979372
GitHub：https://github.com/zbx1425
BlocklyAts：https://github.com/zbx1425/BlocklyAts