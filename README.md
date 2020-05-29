# 単眼超解像(SISR:Single Image Super Resolution)

単眼超解像の手法のSRCNN,SRGANを実装しました。

## srcnn_mnist

### DEMO

### Features

mnistを使うことで手軽にSRCNNを試してみることができる

### Requirement

* keras 2.2.4
* tensorflow 1.15.0
* データセット:mnist(5を使用)


### Usage

Google Colabratoryで実行することができる

### Note

mnistのすべての数字を学習させたところうまく学習ができなかった

## srgan_Upsampling

### DEMO

### Features

SRGANを実装することができる

### Requirement

* keras 2.2.4
* tensorflow 1.15.0
* データセット:自作データセットを使用(6000)


### Usage

Google Colabratoryで実行することができます。

google driveに画像データフォルダを作成しpathを通して実行してください。

### Note

mnistのすべての数字を学習させたところうまく学習ができませんでした。
