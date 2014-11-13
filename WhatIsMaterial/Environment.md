Environment
===

### 3D world

<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7UXpQYWltVjNPWXc/whatismaterial_environment_3d.png" height="250" ><br />

The material environment is a 3D space, which means all objects have x, y, and z dimensions. The z-axis is perpendicularly aligned to the plane of the display, with the positive z-axis extending towards the viewer. Every sheet of material occupies a single position along the z-axis and has a standard 1dp thickness.

---

materialに存在するすべてのオブジェクトは、x-y-zの3軸を有する三次元空間に表現されます。

z軸はディスプレイの面に垂直で、見ているユーザに対して向かって延びる方向を+z軸としています。

materialの各シートはz軸に対しある位置に存在しており、常に 1dp の厚みがあります。


### Light and shadow

Within the material environment, virtual lights illuminate the scene and allow objects to cast shadows. 
A key light creates directional shadows, while an ambient light creates consistent, soft shadows from all angles.

All shadows in the material environment are cast by these two light sources. 
Shadows are the absence of light resulting from the occlusion of these light sources by sheets of material at various positions along the z-axis.

---
materialの環境では、仮想的な仮想光があり、場面によっては描画されるオブジェクトに影を発生させることができます。
周辺光(ambient light)により、様々な方向に伸びるソフトウェア的な影を描画しつつ、起点となる光（key light） により指向性の影を作り出します。

materialの環境ではすべての影が、これら２つの光源によって生成されます。
z軸に沿う形で、様々な位置のmaterialシートを照らします、閉鎖空間での光源の結果として、影は生じますが、光は描画されません。

<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7aUEtMG1ielNEaEk/whatismaterial_environment_shadow1.png" height="150" >、起点となる光（key light）による影<br />
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7ZlNXZTJFX245YUE/whatismaterial_environment_shadow2.png" height="150" >周辺光(ambient light)による影<br />
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7Z19QQzFJWXhYT0E/whatismaterial_environment_shadow3.png" height="150" >起点となる光（key light）と周辺光(ambient light)による影<br />


