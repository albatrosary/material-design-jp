Color
===

Color is inspired by bold color statements juxtaposed with muted environments, taking cues from contemporary architecture, road signs, pavement marking tape, and sports courts. Emphasize bold shadows and highlights. Introduce unexpected and vibrant colors.

参考となる落ち着いた色彩や大胆な文字色と並びなどは、道路標識、路面表示、マーキングテープ、スポーツコートなどの、よくある現代構築の要素よりよりアイディアを受けることができます。

ここでは、重要かつ大胆なシャドウとハイライト、斬新かつ鮮やかな色合いの導入を説明します。


### Color palette

This color palette comprises primary and accent colors that can be used for illustration or to develop your brand colors. They’ve been designed to work harmoniously with each other.

The color palette starts with primary colors and fills in the spectrum to create a complete and usable palette for Android, Web, and iOS. Google suggests using the 500 colors as the primary colors in your app and the other colors as accents colors.

カラーパレットは比較しながら自分自身のブランドカラーを作る為に使う事が出来ます。

それはプライマリとアクセントとなる２つの色合いを持ちます。

この色合いは相互が違和感無く共存するように設計されてきました。

カラーパレットは原色で始まっており、Android、Web、iOSで同じように表示されるスペクトル毎に並べられたパレットです。

これは、Googleが調査した結果のプライマリとアクセントとなる色５００色です。


### UI color application

#### Choose your palette

Limit your selection of colors by choosing three color hues from the primary palette and one accent color from the secondary palette. The accent color may or may not need fallback options.

色の選択は制限されており、メインパレットから３色、セカンダリパレットから１色のアクセントカラーを選びます。

場合によってはアクセントカラーのfallbackオプションが必要ない場合もあります。

#### Use alpha values for grey text, icons, and dividers

To convey a hierarchy of information, you can use different shades for text. The standard alpha value for text on a white background is 87% (#000000). Secondary text, which is lower in the visual hierarchy, should have an alpha value of 54% (#000000). Text hints for users, like those in text fields and labels, have an even lower visual prominence and should have an alpha value of 26% (#000000).

Other elements, such as icons and dividers, also benefit from having an alpha value of black instead of a solid color, to make sure that they work on backgrounds of any color.

標準は、白文字色でアルファ値が87%です。
一つ優先順の低い文字情報は、54%のアルファ値を持ちます。
テキストフィールドやラベルに対するヒントなど、さらに低い優先順の文字情報は26%のアルファ値をもたせます。

アイコンやデバイスなどの要素は、どのような色でも見えるよう、同じような状況下でも純粋な黒色のアルファ値を持つ事で一律で同じに見せます。

#### Toolbars and status bars

Toolbars and larger color blocks should use the primary 500 color, which should be the main color of your app. The status bar should be the darker 700 tint of your primary color.

Bold use of color in large fields in the UI is encouraged. Different elements in the UI can take on different parts of your color theme.

ツールバーと大きなカラーブロックは、作成するアプリケーションのメインカラーとなる５００色から選ぶ必要があります。
ステータスバーには、それよりくらい７００色から選ばなければなりません。

大きなUIエリアには、大胆な色合いが推奨されます。
機能的に異なるUI部分には、最初に選んだカラーテーマとは違う配色を行う事が可能です。

#### Accent color

Use the accent color for your primary action button and components like switches or sliders.

主要機能となるボタンやスイッチ、スライダーなどのコンポーネントにはアクセントカラーを使います。

#### Fallback accent colors

If your accent color is too light or dark for the background color, the general fallback rule is to choose a darker or lighter tint of the accent color. If your accent color doesn’t work at all, use the primary 500 color on white backgrounds. If the background color is the primary 500 color use white 100% or black 54%.

状況によって、選んだアクセントカラーの背景色が明るすぎる、もしくはくらすぎる場合は、一般的なFallbackルールからアクセントカラーの明暗色を選択する事が可能です。

選んだアクセントカラーが不都合となる場合は、白い背景をベースとした主要５００色を使います。

主要５００色の背景色は、白をベースにする場合100%、黒の場合54%を使います。

### Themes

Themes let you apply a consistent tone to an app. The theme specifies the darkness of the surfaces, level of shadow, and appropriate opacity of ink elements.

To promote greater consistency between apps, two themes are available: Light and Dark.

テーマはアプリに一貫性のある色調を適用します。

テーマは表面の暗さ、影のレベル、インクの不透明度(アルファ)を指定します。

アプリ間の一貫性を働きかけるため、２種類のテーマ(光と闇)が用意されています。