# 単眼超解像(SISR:Single Image Super Resolution)

単眼超解像の手法のSRCNN,SRGANを実装しました。

## srcnn_mnist.ipynb

### DEMO

![srcnn demo](https://user-images.githubusercontent.com/53184634/83299303-e312a000-a230-11ea-97a9-ade5663f9b19.png)

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

## srgan_Upsampling.ipynb

### DEMO

### Features

SRGANを実装することができる
120×120の画像を480×480の画像にする

### Requirement

* keras 2.2.4
* tensorflow 1.15.0
* データセット:自作データセットを使用(6000)


### Usage

Google Colabratoryで実行することができます。

google driveに画像データフォルダを作成しpathを通して実行してください。

### Note

upsampling layerにUpsamling2Dを使用した

## srgan_moza.ipynb

### DEMO

![srgan up demo](https://user-images.githubusercontent.com/53184634/83299662-92e80d80-a231-11ea-8b96-b9e5ad95d951.png)

![srgan up suiron](https://user-images.githubusercontent.com/53184634/83299662-92e80d80-a231-11ea-8b96-b9e5ad95d951.png)

### Features

SRGANを実装することができる
120×120の画像を480×480の画像にする

### Requirement

* keras 2.2.4
* tensorflow 1.15.0
* データセット:自作データセットを使用(6000)


### Usage

Google Colabratoryで実行することができます。

google driveに画像データフォルダを作成しpathを通して実行してください。

### Note

upsampling layerにUpsamling2Dを使用した

学習する際、読み込む画像に圧縮モザイクをかけた。

## srgan_pixelshuffl.ipynb

### DEMO

![srgan pix demo](https://user-images.githubusercontent.com/53184634/83299662-92e80d80-a231-11ea-8b96-b9e5ad95d951.png)
![srgan pix suiron](https://user-images.githubusercontent.com/53184634/83299662-92e80d80-a231-11ea-8b96-b9e5ad95d951.png)

### Features

SRGANを実装することができる
120×120の画像を480×480の画像にする
srganの論文で使用されていたpixel shufflerを組み込む

### Requirement

* keras 2.2.4
* tensorflow 1.15.0
* データセット:自作データセットを使用(6000)


### Usage

Google Colabratoryで実行することができます。

google driveに画像データフォルダを作成しpathを通して実行してください。

### Note

upsampling layerにpixel shufflerを使用した

kerasの標準レイヤーになかったので自作した。しかしupsampling2Dでしたほうが綺麗な画像を得ることができた。
