Material properties
===
## _materialの性質_

Material has certain immutable characteristics and inherent behaviors. Understanding these qualities will help you manipulate material in a way that’s consistent with the vision of material design.

material(素材)には、特定の決まった特性、固有の動作があります。
これらの性質を理解することは、本来のマテリアルデザインの思想と一致しない方法で、material(素材)を扱おうとしたとき役に立ちます。

---

### Physical properties

#### _物理的な性質_

Material has varying x & y dimensions (measured in dps) and a uniform thickness (1dp). Material never has a thickness of 0.

materialには、xとy(dpsで計測する高さと幅)に加えて、均一の厚み(1dp)を有しています。
materialには、必ず厚みがあり、ゼロであることはありません。

---

##### 良い例

 * materialの高さと幅は変えることができる。(The height and width of material can vary.)

<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B8v7jImPsDi-aTBFT1FDVEstenM/whatismaterial_materialproperties_physicalproperties_thickness_01_yes.png" width="250" />

##### ダメな例

 * 材料は常に1DP厚さである。(Material is always 1dp thick.)
 * 厚みを増やしたり、ゼロにしたりは出来ない。
 
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B8v7jImPsDi-Sno0Qy1FY3UtaFk/whatismaterial_materialproperties_physicalproperties_thickness_02_no.png" width="250" />


##### Material casts shadows.

_materialに対する影の描画_

Shadows result naturally from the relative elevation (z-position) between material elements.

影はマテリアル要素間の相対的な標高（z位置）から自然に生じます。

 * 良い例
  * (物質的な)materialの影を描画する(Material casts shadows.)
  * [サンプル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSE9IaUpqYzlpSW8/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007.webm)


 * ダメな例
  * materialに対して、にたような影が描画される。(shadows are never approximated using material.)
  * [サンブル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWYU5lQ1VXQjA3NnM/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Dont_xhdpi_007.webm)
 

---

Content is displayed on material, in any shape and color. 
Content does not add thickness to material.

コンテンツ上に描画されるmaterialには様々な形や色があります。
しかし、コンテンツはmaterialに厚みを持たせません。

[サンブル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWTG41Rk9fT19qUXc/whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005.webm)

---

Content behavior can be decoupled from the behavior of material. However, the bounds of the material can limit the display of the content.

コンテンツとmaterialの性質は切り離して考える事が出来ます。
しかし、materialの範囲内でのみ、コンテンツは表示できます。

[サンブル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWeVBlbExGYjlTeEE/whatismaterial-materialprop-physicalprop-020201_InkBehavior_xhdpi_005.webm)

---

Material is solid.

Input events cannot pass through material.

マテリアルは確実な物です。

入力イベントは、materialを越える事はできません。

良い例
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7Q296SENNTG96RVE/whatismaterial_properties_physical3.png" height="250" />

悪い例
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7WlhmUDRKZWlyUlU/whatismaterial_properties_physical4.png" height="250" />

---

Multiple material elements cannot occupy the same point in space simultaneously.

複数あるmaterialの要素は、一つの空間の中で重なる事はありません。

良い例
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7aVhXV0EtZ29OSU0/whatismaterial_properties_physical5.png" height="250" />

悪い例
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7UFdUMnRKaW5PSXM/whatismaterial_properties_physical6.png" height="250" />

---

Material cannot pass through other material.

For example, one sheet of material cannot pass through another sheet of material when changing elevation.

materialは他のmaterialをすり抜ける事はできません。

例えば、単純に高さを入れ替える場合に、一枚のmaterialシートが別のmaterialシートを通り抜けるような事はできません。

悪い例
<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7Ni14MHdScGx0czA/whatismaterial_properties_physical7.png" height="350" />


---

### Transforming material
### _materialの変形_

Material can change shape.

materialは、形状を変化させることができます。

[サンプル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWd2N5R1lqeUFwWkk/whatismaterial-materialprop-transformingmaterial-020202_PaperShape_xhdpi_004.webm)

---

Material grows and shrinks along only its plane.

materialは平面方向に対してだけ形を変えていきます。

[サンプル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWWFFOVGp2UFVNZzg/whatismaterial-materialprop-transformingmaterial-020202_PaperShapeLinear_xhdpi_004.webm)

---

Material never bends or folds.

materialは決して折れたり曲がったりしません。

[悪い例](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWNktzeE04V0ZGNzg/whatismaterial-materialprop-transformingmaterial-020202_PaperBendFold_xhdpi_005.webm)

----

Sheets of material can join together to become a single sheet of material.

複数のmaterialシートは、単一のmaterialシートに結合する事が出来ます。

[サンプル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWbE1WWExWSURmTDg/whatismaterial-materialprop-transformingmaterial-020202_PaperHeal_xhdpi_003.webm)

---

When split, material can heal. 

For example, if you remove a portion of material from a sheet of material, the sheet of material will become a whole sheet again.

materialは、複数に分けた後、また結合する事が出来る。

もし、materialシートから別のmaterialとして切り出したとき、その切り出したmaterialシートは元のmaterialシートに再結合し、再度一つのmaterialシートとして扱うことができる。

[サンプル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWX0dIVXh2QzlwcVU/whatismaterial-materialprop-transformingmaterial-020202_PaperSplitHeal_xhdpi_004.webm)

---

### Movement of material
### _Materialの動作_

Material can be spontaneously generated or destroyed anywhere in the environment.

materialはどのような場所にでも自然と現れ、消えることが可能です。

[サンプル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWWWhMRFVudjl4bTQ/whatismaterial-materialprop-movementmaterial-020203_PaperPointExpand_xhdpi_004.webm)

---

Material can move along any axis.

materialは任意の軸に沿って移動することができます。

[サンプル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6Y2Z1NUlzMWczaHc/whatismaterial-materialprop-movementmaterial-020203_PaperMove_xhdpi_007.webm)

---

Z-axis motion is typically a result of user interaction with material.

一般的にz軸の振る舞いは、materialの特性とユーザー操作の組み合わせの結果です。

[サンプル](http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWNW5xUERVcEd1bm8/whatismaterial-materialprop-movementmaterial-020203_Material_Response_xhdpi_002.webm)
