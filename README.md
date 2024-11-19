# AirLiftFrame for Bitaxe

![LookBook001](https://github.com/user-attachments/assets/958fb795-c514-4384-9613-e2dcbe5ccbb6)

![LookBook002](https://github.com/user-attachments/assets/3c4bf8c0-1905-4f12-b9bd-7d9485f5ff94)

![HomeView](https://github.com/tko-combinator/BitaxeAirLiftFrame/blob/main/images/HomeView.png)	

## 概要
Bitaxe Supra(401) を基準に設計されています。未検証ではありますが、2024年10月現在に流通しているシングルASICのBitaxeであれば概ね適合すると思われます。   
基板の端子からケースの縁まで距離があるため、USB-CやDC電源のコネクタはある程度長いストレートタイプのものを推奨します。  
しかし、少し苦労をすればL字型や短いコネクタを使用して、コネクタ類が目立たないように取り付ける事も出来ます。
※リリース後にいくつかのモデルを購入検証したので、適合確認済み機種の項目を追加しました。

## 検証済み適合機種
基板の製造上の誤差や3Dプリント時の誤差や歪みなどによって、多少の調整が必要になるかもわかりません。
* Bitaxe Supra(402)
* Bitaxe Ultra(205)
* Bitaxe Gamma(601)

## ファイルの説明

### 1. **AirLiftFrame.stl**  
AirLiftFrameの基本設計ファイルです。
こちら利用を推奨します。

### 2. **AirLiftFrame_InsertNut_3-8mmHoles_test.stl**  
インサートナット用に、ネジ穴を3.8mmに拡張したバージョンです。
本バージョンはテスト中です。

### 3. **AirLiftFrame_BackCooler.stl**  
背面に取り付けられたクーラーを特徴とするバージョンです。 
**適合ファンサイズ：8cm**  
現在、冷却効果を検証中です。

## 必要な部品
* M3のタッピングネジ
(基板とマウンターの厚みが7mmのため、6mmの長さが推奨されます)
* 必要に応じて、インサートナットおよび適合するネジを用意してください。

## 製造情報
私は、AnkerMake M5を使用し、標準の0.4mmノズルと純正のPLA+フィラメントで出力しました。  
スライサーソフトウェアにはAnkerMake Studioを使用しました。
設定は各社3Dプリンタ事に異なると思いますが、参考になるよう情報共有をします。

### 出力時の設定
* 品質設定: 品質優先
* 造形方向: ケース背面から全面へ向かって積層
* 積層ピッチ: 0.16mm
* 充填密度: 60%
* サポート: スナッグ or オーガニック

形状やケースとしての用途を考えると、充填密度はある程度上げた方が安全です。  
ネジ穴は2.5mmとして設計していますが、使用するネジや出力品質によっては、2.5mm程度のドリルで二次加工が必要になる場合があります。  
※頻繁に基板の付け外しを行う場合は、インサートナットの使用を検討してください。  
面取りやバリを削るなどの仕上げをすると、見た目もより良くなります。

## カスタムの楽しみ
デカールを貼ったり、複数色のフィラメントやペイントなどのカスタムを加えて、個性的な仕上げにするのも面白いでしょう。  
では、DIYマイニングをエンジョイしましょう！
改良品や色んなバージョンを見てみたいです！

## ライセンス
このプロジェクトはMITライセンスの下で提供され、自由に使用、変更、配布することができます。
本リポジトリ内のデータ及び、データを元に制作された成果物に対しての一才の保証はございません。
詳細は同封のLICENSEをご覧ください。



## Overview
This case is designed based on the Bitaxe Supra (401). Although unverified, it is expected to be compatible with most single-ASIC Bitaxe models available as of October 2024.  
Since there is a distance between the terminals of the board and the edge of the case, we recommend using a relatively long, straight USB-C or DC power connector.  
However, with some effort, you can use an L-shaped or shorter connector to make the connection points less visible.
I’ve added a list of confirmed compatible models based on our post-release tests. 

## Confirmed Models
Due to manufacturing tolerances in the circuit board or errors and distortions during 3D printing, slight adjustments may be required.
* Bitaxe Supra(402)
* Bitaxe Ultra(205)
* Bitaxe Gamma(601)

## File Descriptions

### 1. **AirLiftFrame.stl**  
This is the standard design file for AirLiftFrame.  
This version is recommended for general use.

### 2. **AirLiftFrame_InsertNut_3-8mmHoles_test.stl**  
This version features screw holes expanded to 3.8mm for insert nuts.  
Please note that this version is currently under testing.

### 3. **AirLiftFrame_BackCooler.stl**  
This variant is designed with a back-mounted cooler.  
**Compatible fan size: 8cm**  
The cooling effect is currently under evaluation.

## Required Parts
M3 tapping screws  
(Since the thickness of the board and the mount is 7mm, screws with a length of 6mm are recommended.)  
Please prepare insert nuts and compatible screws as needed.

## Manufacturing
I used an AnkerMake M5 with a standard 0.4mm nozzle and genuine PLA+ filament to print this case.  
For slicing, I used AnkerMake Studio.  
The settings may vary depending on your 3D printer, but I’m sharing the details for reference.

### Settings
* Quality: Prioritize quality
* Orientation: Layered from the back of the case to the front
* Layer height: 0.16mm
* Infill density: 60%
* Support: Snug or Organic

Considering the shape and function as a case, it is safer to increase the infill density.  
The screw holes are designed to be 2.5mm, but depending on the screws used and the print quality, you may need to use a 2.5mm drill for post-processing.  
※ If you intend to frequently remove and reattach the board, consider using insert nuts.  
Also, finishing touches like chamfering or trimming burrs will also improve the overall appearance.

## Enjoy Customizing!
Adding decals, using multi-colored filaments, or painting can make for a fun, personalized finish.  
Enjoy your DIY mining journey! I can't wait to see how you "Kaizen" it with your own improvements and versions!

## License
This project is provided under the MIT license, allowing free use, modification, and distribution.  
No warranty is provided for any data in this repository or for any products created using the data.  
For more details, please see LICENSE file.








