Environment
===

### 3D world

<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7UXpQYWltVjNPWXc/whatismaterial_environment_3d.png" height="250" ><br />

The material environment is a 3D space, which means all objects have x, y, and z dimensions. The z-axis is perpendicularly aligned to the plane of the display, with the positive z-axis extending towards the viewer. Every sheet of material occupies a single position along the z-axis and has a standard 1dp thickness.

---

materialに存在するすべてのオブジェクトは、x-y-zの3軸を有する三次元空間に表現されます。

z軸は見ている人に対して近づきつつも、平面のディスプレイ上に並んでいます。

materialの各シートはz軸に対して一定の位置に存在しており、標準では1dp毎の厚みが表現されます。


### Light and shadow

material 環境内で、仮想ライトは、シーンを照らすとオブジェクトが影作ることができます。周囲の光があらゆる角度から一貫して、ソフトシャドウを作成しながら、キーライトは、指向性の影を作成します。

material 環境内のすべての影は、これら2つの光源によって鋳造される。影は、z軸に沿った様々な位置でシート材料によってこれらの光源の閉塞に起因する光の不在である。


<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7aUEtMG1ielNEaEk/whatismaterial_environment_shadow1.png" height="150" >Shadow cast by key light<br />
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7ZlNXZTJFX245YUE/whatismaterial_environment_shadow2.png" height="150" >Shadow cast by ambient light<br />
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7Z19QQzFJWXhYT0E/whatismaterial_environment_shadow3.png" height="150" >Combined shadow from key and ambient lights<br />



####  翻訳内容の補足メモ

 + [dp(Density-independent Pixels)](http://developer.android.com/guide/topics/resources/more-resources.html#Dimension)
    + ディスプレイサイズに依存しないピクセル表現
