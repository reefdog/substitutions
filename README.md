# ~Substtitions~ → Substitutions

Useful text substitutions for macOS and iOS. With these installed, typing `/1star` into a native macOS/iOS text field will replace it with `★☆☆☆☆`, and so on.

I strongly encourage you to freely add your own text substitutions, they’re terribly handy!

## Installation

- Download [`substitutions.plist`](./substitutions.plist)
- Open macOS System Preferences
- Go to Keyboard → Text
- Drag `substitutions.plist` into the text-replacement area
  - macOS will merge this with any existing substitutions, although this list will clobber any existing duplicates.

💡 iCloud will synchronize these between your devices, so anything you add on macOS will also be usable on your iOS devices.

## Usage

In any native macOS/iOS text field, type the trigger term and it will be automatically substituted. See the table below for a full list of substitutions.

⚠️ Note that some applications (e.g., Firefox) don’t use native text fields, and so text substitutions won’t work there. My clunky workaround is to open Spotlight (Command-Space by default), type the term there, and copy out the substitution.

Term | Substitution
---- | -------------
`/1star` | ★☆☆☆☆
`/2star` | ★★☆☆☆
`/3star` | ★★★☆☆
`/4star` | ★★★★☆
`/5star` | ★★★★★
`/framed1` | 🎥 🟩 ⬛️ ⬛️ ⬛️ ⬛️ ⬛️
`/framed2` | 🎥 🟥 🟩 ⬛️ ⬛️ ⬛️ ⬛️
`/framed3` | 🎥 🟥 🟥 🟩 ⬛️ ⬛️ ⬛️
`/framed4` | 🎥 🟥 🟥 🟥 🟩 ⬛️ ⬛️
`/framed5` | 🎥 🟥 🟥 🟥 🟥 🟩 ⬛️
`/framed6` | 🎥 🟥 🟥 🟥 🟥 🟥 🟩
`/framed7` | 🎥 🟥 🟥 🟥 🟥 🟥 🟥
`/framedx` | 🎥 🟥 🟥 🟥 🟥 🟥 🟥
`/darr` | ↓
`/larr` | ←
`/rarr` | →
`/uarr` | ↑
`/numero` | №
`/no0` | ⓪
`/no1` | ①
`/no2` | ②
`/no3` | ③
`/no4` | ④
`/no5` | ⑤
`/no6` | ⑥
`/no7` | ⑦
`/no8` | ⑧
`/no9` | ⑨
`/num0` | ⓪
`/num1` | ①
`/num2` | ②
`/num3` | ③
`/num4` | ④
`/num5` | ⑤
`/num6` | ⑥
`/num7` | ⑦
`/num8` | ⑧
`/num9` | ⑨
`/sub1` | ₁
`/sub2` | ₂
`/sub3` | ₃
`/sub4` | ₄
`/sub5` | ₅
`/sub6` | ₆
`/sub7` | ₇
`/sub8` | ₈
`/sub9` | ₉
`/sup1` | ¹
`/sup2` | ²
`/sup3` | ³
`/sup4` | ⁴
`/sup5` | ⁵
`/sup6` | ⁶
`/sup7` | ⁷
`/sup8` | ⁸
`/sup9` | ⁹
`1/2` | ½
`1/3` | ⅓
`1/4` | ¼
`1/5` | ⅕
`1/6` | ⅙
`1/8` | ⅛
`2/3` | ⅔
`2/5` | ⅖
`3/4` | ¾
`3/5` | ⅗
`3/8` | ⅜
`4/5` | ⅘
`5/6` | ⅚
`5/8` | ⅝
`7/8` | ⅞
`x*` | ×
`./.` | ÷
`=/=` | ≠
`!=` | ≠
`+-` | ±
`=>` | ≥
`>=` | ≥
`<=` | ≤
`=>` | ≤
`/deg` | °
`/degc` | ℃
`/degf` | ℉
`co2` | CO₂
`CO2` | CO₂
`h2o` | H₂O
`H2O` | H₂O
`c/o` | ℅
`(c)` | ©
`(p)` | ℗
`(r)` | ®
`/tm` | ™
`<3` | ❤️
`/flip` | `(╯°□°）╯︵ ┻━┻`
`/scowl` | `ಠ_ಠ`
`/shrug` | `¯\_(ツ)_/¯`

## License

This work is made available under the [MIT license](./LICENSE).