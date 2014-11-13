Material properties
===
### _materialの性質_

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

コンテンツの振る舞いはマテリアルの振る舞いから切り離すことができます。しかし、マテリアルの境界は、コンテンツの表示を制限することができます。

Material is solid.

マテリアルは固体です。

Input events cannot pass through material.

入力イベントは、マテリアルを通過することができない。

Multiple material elements cannot occupy the same point in space simultaneously.

複数のマテリアル要素は、同時に空間内の同じ点を占有することはできません。

Material cannot pass through other material.

マテリアルは他のマテリアルを通過することはできません。

For example, one sheet of material cannot pass through another sheet of material when changing elevation.

例えば、上下移動する場合、一枚のマテリアル・シートが別のマテリアル・シートを通過することができません。

### Transforming material

Material can change shape.

マテリアルは、形状を変更することができます。

Material grows and shrinks along only its plane.

マテリアルは成長してのみ、その平面に沿って縮む。

Material never bends or folds.

マテリアルは決して曲がったりしない。

Sheets of material can join together to become a single sheet of material.

マテリアル・シートは、マテリアルの単一のシートになるために結合することができる。

When split, material can heal. For example, if you remove a portion of material from a sheet of material, the sheet of material will become a whole sheet again.

分解してもマテリアルは治すことができる。例えば、もしマテリアル・シートからマテリアルの一部を除去した場合、分解マテリアル・シートは再度全体のシートになる。

### Movement of material

Material can be spontaneously generated or destroyed anywhere in the environment.

マテリアルはどのような環境でも自発的に生成されるか破壊することができる。

Material can move along any axis.

マテリアルは任意の軸に沿って移動することができます。

Z-axis motion is typically a result of user interaction with material.

Z軸の動きは、通常マテリアルとユーザとの相互作用の結果です。

