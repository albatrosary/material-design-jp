Material properties

Material has certain immutable characteristics and inherent behaviors. Understanding these qualities will help you manipulate material in a way that’s consistent with the vision of material design.

マテリアルは、特定の決まった特性や固有の動作があります。これらの性質を理解することは、マテリアルデザインのビジョンと一致しない方法でマテリアルを操作しようとした場合に役立ちます。

### Physical properties

Material has varying x & y dimensions (measured in dps) and a uniform thickness (1dp). Material never has a thickness of 0.

マテリアルは、様々な種類のX-Y寸法（dpsで測定）と均一な厚さ（1dp）を持っています。マテリアルは厚さが 0 であることはありません。

Material casts shadows.

マテリアルは影を投射します。

Shadows result naturally from the relative elevation (z-position) between material elements.

影はマテリアル要素間の相対的な標高（z位置）から自然に生じます。

Content is displayed on material, in any shape and color. Content does not add thickness to material.

コンテンツは、任意の形状および色があり、マテリアル上に表示されます。コンテンツはマテリアルに厚みを追加しません。

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

