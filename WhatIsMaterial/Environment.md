Environment
===

### 3D world

<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7UXpQYWltVjNPWXc/whatismaterial_environment_3d.png" height="250" ><br />
material の環境のすべてのオブジェクトは、x、y、およびzを有する三次元空間である。 z軸は垂直に正のz軸は、観察者に向かって延びるとともに、ディスプレイの平面に整列される。材料の各シートは、z軸に沿った単一の位置を占め、標準として 1dp の厚さを有する。

### Light and shadow

material 環境内で、仮想ライトは、シーンを照らすとオブジェクトが影作ることができます。周囲の光があらゆる角度から一貫して、ソフトシャドウを作成しながら、キーライトは、指向性の影を作成します。

material 環境内のすべての影は、これら2つの光源によって鋳造される。影は、z軸に沿った様々な位置でシート材料によってこれらの光源の閉塞に起因する光の不在である。


<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7aUEtMG1ielNEaEk/whatismaterial_environment_shadow1.png" height="150" >Shadow cast by key light<br />
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7ZlNXZTJFX245YUE/whatismaterial_environment_shadow2.png" height="150" >Shadow cast by ambient light<br />
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7Z19QQzFJWXhYT0E/whatismaterial_environment_shadow3.png" height="150" >Combined shadow from key and ambient lights<br />



####  翻訳内容の補足メモ

 + [dp(Density-independent Pixels)](http://developer.android.com/guide/topics/resources/more-resources.html#Dimension)
    + ディスプレイサイズに依存しないピクセル表現
