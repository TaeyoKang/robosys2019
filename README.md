# robosys2019

GPIOピンでのPWM制御

Futaba S3003サーボをVcc(5V),GND,PWM(GPIO25)のピンに接続。
GPIO25からDuty_cycleを20msec,Duty_ratioを0.025の信号を入力。
移動後の角度が最大角の-90°になったことを確認した。

制御に使用しているlinux/delay.hのmsleepの正確性がたりないせいか制御位置に来ると振動を起こす問題が未解決。 

実行環境
Raspberrypi 3B+(Raspbian ver.4.19)

Futaba S3003:
https://www.es.co.th/schemetic/pdf/et-servo-s3003.pdf

demo movie:
https://www.youtube.com/watch?v=Gdf1Z545br0&list=PLJoXfeyQnWprGtHGRYL409WqVNBVkjSzu&index=5&t=0s

