# Switch WebRTC Controller
Switch WebRTCのコントローラーコンポーネント

以下のライブラリを使用
[GitHub - mart1nro/joycontrol](https://github.com/mart1nro/joycontrol)

## 準備
joycontrolで初回接続し、SWITCHのMACアドレスを取得する。


## 使い方
SWITCHのMACアドレスを入力した以下のような```.env```を用意
```
SWITCH_ADDR=***
```
引数にシリアルポートを入力
```sh
$ python3 controller.py /dev/pts/3
```

## 参考
- [GitHub - mart1nro/joycontrol](https://github.com/mart1nro/joycontrol)
