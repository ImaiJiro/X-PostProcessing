#Awesome-Unity-Shader
Unity3D Shaderに関する担当者です。 現時点では、主に私のブログコラム「[Light Ink Unity3D Shader Programming]」で起動したいくつかの Shader コードをまとめたものです。
※シェーダー列アドレス：[https://blog.csdn.net/zhmxy555/category_9264739.html](https://blog.csdn.net/zhmxy555/category_9264739.html)
<br>

## 新しい高品質の Unity シェーダー プロジェクトを推奨する 新しい素晴らしい Unity シェーダー ライブラリを推奨する |

X-PostProcessing Libray (XPL と呼ばれる) は、Unity エンジン用の高品質なオープンソース後処理ライブラリであり、業界で主流となっている高品質の後処理特殊効果のための完全なソリューションを提供することを目的としています。 現在、Unity Post-processing Stack v2 を完全にサポートしており、将来的には Unity エンジン URP/LWRP/HDRP の互換性サポートも提供する予定です。

X-PostProcessing Library (XPL) は、Unity Post Processing Stack v2/LWRP/URP/HDRP 用の高品質な後処理ライブラリです。

![](https://raw.githubusercontent.com/QianMo/X-PostProcessing-Gallery/master/Media/XPL-Title-v2.jpg)
**【詳細については、X-PostProcessing Libray リポジトリをご覧ください:[https://github.com/QianMo/X-PostProcessing-Library](https://github.com/QianMo/X-PostProcessing-Library) )】**



<br>
以下に各シェーダーの図を示します。
<br><br>


## ボリューム 1 バンプ テクスチャ表示 + 独自に選択したエッジの色と強度シェーダー

<br>

### 0.TheFirstShader

![](http://img.blog.csdn.net/20141103021350640?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東）

<br> <br><br> <br><br>


## 第02回 Unity基本Shaderフレームワーク書き方

<br>

### 1. モノクロシェーダー

![](http://img.blog.csdn.net/20141109223715831?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br> <br> <br>

### 2. マテリアルの色と照明シェーダーのオン

![](http://img.blog.csdn.net/20141109224045203?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東）
<br> <br> <br>

### 3. 調整可能な拡散光シェーダー

![](http://img.blog.csdn.net/20141109224100284?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br> <br> <br>

### 4. 完全な照明マテリアル ベータ版 Shader

![](http://img.blog.csdn.net/20141109224312214?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東）
<br> <br> <br>

### 5. 単純なテクスチャ読み込みシェーダー

![](http://img.blog.csdn.net/20141109224434832?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東）
<br> <br> <br>

### 6. 完全な照明マテリアル正式版 Shader

![](http://img.blog.csdn.net/20141109224815432?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東）
<br> <br> <br> <br> <br>

## ボリューム 03 サブシェーダー、チャンネルとラベルの書き込み、テクスチャ ブレンディング

<br>

### 1. アルファ テクスチャ ブレンディング

![](http://img.blog.csdn.net/20141116204632861?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br> <br> <br>

### 2. 自己照明とブレンドされたテクスチャのアルファ チャネル

![](http://img.blog.csdn.net/20141116204751080?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br> <br> <br>

### 3. テクスチャアルファと自己発光混合色バージョン

![](http://img.blog.csdn.net/20141116204937062?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br> <br> <br>

### 4. 頂点ライティング + テクスチャ アルファ自己照明ブレンディング

![](http://img.blog.csdn.net/20141116205146640?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)

<br> <br> <br>

### 5. 頂点ライティング + 自己照明ブレンディング + テクスチャ ブレンディング

![](http://img.blog.csdn.net/20141116205243876?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東）

<br> <br> <br> <br> <br>

## ボリューム 04 カリング、深度テスト、アルファ テスト、および基本的なフォグ エフェクト

<br>

### 1. カリング操作を使用してオブジェクトの背面をレンダリングします。

![](http://img.blog.csdn.net/20141214160445602?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br>

![](http://img.blog.csdn.net/20141214160605390?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br>

![](http://img.blog.csdn.net/20141214160616609?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br> <br> <br>

### 2. カリングを使用したオブジェクトの背面のレンダリング (バージョン 2)

![](http://img.blog.csdn.net/20141214160749125?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br>

![](http://img.blog.csdn.net/20141214160808203?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br>

![](http://img.blog.csdn.net/20141214160827953?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcG9lbV9xaWFubW8=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/South東)
<br> <br> <br>

### 3. カリングを使用してガラス効果を実現する