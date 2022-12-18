# pokemonSV_scraping
Getting the data below of Pokemon SV from GameWith.
* Base Status
* type(Japanese)
* Move to remember (Japanese)
* Characteristic (Japanese)

And also get Jp -> Eng translation data of:
* Pokemon Name
* Moves
* Characteristics

GameWithからポケモンSVの各種データを取得するコードです。
* 種族値
* タイプ
* 覚える技
* 特性
* 各種翻訳データ

## 上記データ / data above
上記ポケモンデータはdata/0pokemon.jsonにあります（2022/12/18更新)
The pokemon data above is at data/0pokemon.json (2022/12/18)

## 画像/ Pokemon Images
著作権の都合上画像データは載せていませんが、取得したい場合はimagesフォルダを作った上で
7identification.ipynb
→8images.ipynb
→9ridImageLink.ipynb
の順で実行していくと画像を取得できます

If you want image of pokemons, run the jupyter notebook from 7identification.ipynb

## タイプ番号/ typeID
* 0 Normal
* 1 Fire
* 2 Water
* 3 Electric
* 4 Glass
* 5 Ice
* 6 Fighting
* 7 Poison
* 8 Ground
* 9 Flying
* 10 Psychic
* 11 BUg
* 12 Rock
* 13 Ghost
* 14 Dragon
* 15 Dark
* 16 Steel
* 17 Fairy
