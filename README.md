# 2015年10月22日　晩秋の久住

https://jadwigalareve.github.io/around_mt_kujuu_map_2015_10_22/index.html

電子国土地理院の上に2015年10月に久住連山縦走を行ったときの登山ルートを作図します。

登山の記事は

https://jadwigalareve.hatenablog.jp/entry/2020/02/22/182148

にあります。

作図データはスタイル付きGeoJSONです

- スタイルつき GeoJSON 規約  
https://github.com/gsi-cyberjapan/geojson-with-style-spec

## 地図の中心点、ズームの変更

URL末尾に`?longitude=35.858309&latitude=138.989754&zoom=12`のようにパラメータをつけることで変更された状態のものにアクセスできるようになります。

ただし**Internet Explorer 11を含む**古いブラウザでは利用できません(無視されます)。利用できるかは  
[URLSearchParams.get() - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams/get#Browser_compatibility)  
を確認してください。

- `longitude` (default: `35.858309`): 緯度。`-90 <= longitude <= 90`の数値
- `latitude` (default: `138.989754`): 経度。`-180 <= latitude <= 180`の数値
- `zoom` (default: `12`): ズーム。`2 <= zoom <= 18`の整数
