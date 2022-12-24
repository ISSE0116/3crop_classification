画像をGUI上で指定した座標点を中心に 一辺25,50,100pixelの正方形で切り取ったのち、３枚の画像に対して画像分類を行うスクリプトです。
dataディレクトリ内にはImageNet-1kのクラスを日本語表記に変換するjsonファイルが格納されています。
jasonファイルはスクリプト内から参照するようになっています。
画像分類はImageNetにて事前学習済みのResnext34で行います。

This script performs image classification on three images after cropping images into 25-, 50-, and 100-pixel squares centered at the coordinate points specified in the GUI.
In the data directory, there is a json file that converts ImageNet-1k classes into Japanese notation.
The jason file is referenced from within the script.
Image classification is performed by Resnext34, which has been pre-trained by ImageNet.
