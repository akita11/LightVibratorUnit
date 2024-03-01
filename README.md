# LightVibratorUnit

<img src="https://github.com/akita11/LightVibratorUnit/blob/main/LightVibratorUnit.jpg" width="320px">

円形振動モータで振動を発生するUnitです。与える制御信号のPWM比で振動の強さを制御できます。※[M5Stack純正の振動モータユニット](https://www.switch-science.com/products/6065)は振動が強すぎるため、UIFlowの"Vibrator"のブロックは強さを20までしか設定できません。そのため本ユニットを使う場合は、UIFlowのPWMブロックを使って制御してください。

## ピン配置

Grove端子の1番から順に「無接続」「振動モータ制御」「VDD(5V/3.3V)」「GND」の順です。


## Author

Junichi Akita (akita@ifdl.jp, @akita11)
