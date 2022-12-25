# Open Runway Font (日本語 README)

**English version is [here](./README.md)**

**Open Runway Fonts**は滑走路・誘導路の文字を模したオープンソースのフォントパックです。このフォントパックに含まれる全てのフォントデータはCC0ライセンスで提供されており、完全に自由に利用できます。

## 収録フォント

### Open Runway Numbers

![](./img/open-runway-numbers.png)

滑走路番号の文字を模したフォントです。収録文字は以下の通りです。

```
0 1 2 3 4 5 6 7 8 9 C L R
```

アルファベットは大文字の L, C, R のみ収録しています。これらは滑走路が並行している場合に用いられるものです。通常の欧文を組むことはできないのでご注意ください。

文字間隔（カーニング）はICAO Annex 14に準拠しました。

元デザイン: *Figure 5-3 (Form and proportions of numbers and letters for runway designation markings)*  in *ICAO Annex 14 - Aerodromes*

### (Beta) Open Taxiway Mandatory Sign

![](/img/open-taxiway-mandatory-sign.png)

ICAO Annex 14 における *MANDATORY INSTRUCTION MARKINGS* (必須の指示、マーキング) を模したフォントです。

以下の文字を収録しています。一部、ICAO資料には存在しないものの、実際の空港で使われている文字を独自にデザインして追加しています。

```
A B C D E F G H I J K L M N O P Q R S T U V W X Y Z 
0 1 2 3 4 5 6 7 8 9 - /
```

また、矢印とILSのカテゴリ表記用にローマ数字も収録していますが、作成ソフトウェアの都合で本来のコードポイントではなく、以下の記号として収録しています。この問題は将来のバージョンで修正される予定です。

```
Ⅰ:!（半角エクスクラメーションマーク）
Ⅱ:@（半角アットマーク）
Ⅲ:#（半角ハッシュ記号）
←:a（小文字のa）
↑:w
→:d
↓:s
↖:q 
↗:e
```

アルファベットの小文字は収録していませんが、Illustratorなどで入力中にフォントが切り替わるのを防ぐため、小文字は半角スペースと同様の文字を割り当てています。

元デザイン: *APPENDIX 3. MANDATORY INSTRUCTION MARKINGS AND INFORMATION MARKINGS*  in *ICAO Annex 14 - Aerodromes*

### (WIP) Open Taxiway Guidance Sign

ICAO Annex 14 における *TAXIING GUIDANCE SIGNS* を模したフォントです。

近日リリース予定です。

## 利用規約について

これらは CC0 ライセンスで提供されるパブリックドメインのフォントです。Web・印刷物・動画、ソフトウェア・ハードウェアへの組み込みなど、媒体を問わず商用利用が可能です。再配布も可能です。どのような利用形態であれ、作者に連絡を取る必要はありません。

なお、滑走路や誘導路を模したデザインを行うためのフォントであり、実際の航空機の運航に関する用途を想定したものではないことにご留意ください。

## ダウンロード

この GitHub リポジトリの [Releases](https://github.com/ryo-a/Open-Runway-Fonts/releases) ページから最新のものをダウンロードしてください。

## コントリビューター

Open Taxiway Mandatory Signについて、[七色さん](https://at.tumblr.com/7-typ/67d6e4v0g9hk)にメトリクスのチェックと助言を行っていただきました。ここに深謝の意を表します。