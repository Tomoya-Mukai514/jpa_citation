# JPA Publication Manual (revised 2022 edition) for Zotero

## English
This CSL style is based on the *Publication Manual of the Japan Psychological Association* (日本心理学会『投稿・執筆の手びき』) and is intended for use in Zotero when writing Japanese-language psychology papers.
In many respects, this style follows APA 7th edition. In particular, the formatting rules for English references are essentially the same as APA 7th. The main purpose of this style is therefore to adjust the formatting of Japanese references, which differ substantially from standard APA-style output.

### Scope
This style is intended to reproduce the JPA manual as closely as possible within the standard CSL framework used by Zotero.
It modifies the formatting of Japanese references, including matters such as:
- punctuation
- author delimiter style
- title punctuation
- journal formatting
- other Japanese-specific output rules

### Installation
Once this style is available in the Zotero Style Repository, it can be installed from Zotero:
1. Open **Edit** → **Preferences**
2. Go to the **Cite** tab
3. Click **Get additional styles...**
4. Search for **JPA Publication Manual revised 2022 edition**
5. Install the style

### Known limitation
A known limitation remains regarding Japanese personal names.
According to the JPA manual, a half-width space should be inserted between family name and given name in Japanese author names, for example:

`山田 太郎`

However, this behavior cannot be fully implemented through CSL alone under the standard Zotero / citeproc processing behavior. In other words, this CSL style cannot by itself guarantee automatic insertion of a half-width space between family name and given name for Japanese names in all cases.
Therefore, this style should be understood as reproducing the JPA manual as closely as possible within standard CSL and Zotero behavior, while this specific point remains a technical limitation.

### Optional workaround outside the CSL style
It is possible to address the name-spacing issue by modifying Zotero's internal processing files. However, this requires changes outside the CSL style itself and is **not part of the normal installation procedure** for this style.
A separate explanation of that workaround is available [here](https://note.com/preview/ne5d6781d3f46?prev_access_key=107fe677e4c5cb01f88c4b1f8178483b):

Please note that:
- this workaround is optional
- it is not required for ordinary use of this CSL style
- it is outside the scope of the official CSL style itself

### Documentation
- Japan Psychological Association manual: https://psych.or.jp/manual/

### Notes
This style is designed for users who need Japanese reference formatting based on the JPA manual, including cases where both Japanese and English references are cited in the same manuscript.
If behavior differs from the manual in edge cases, priority has generally been given to what can be implemented robustly within standard CSL/Zotero behavior.

---

## 日本語
この CSL スタイルは、日本心理学会『投稿・執筆の手びき』に基づいて作成されたものであり、Zotero で日本語の心理学論文を書く際に利用することを想定しています。
多くの点で、このスタイルは APA 第7版に準拠しています。特に、英語文献の書式は実質的に APA 第7版と同一です。そのため、このスタイルの主な目的は、標準的な APA 出力とは大きく異なる日本語文献の書式を調整することにあります。

### 対応範囲
このスタイルは、Zotero が採用している標準的な CSL の枠組みの中で、日本心理学会『投稿・執筆の手びき』を可能な限り再現することを目的としています。
具体的には、以下のような日本語文献の書式に関わる点を調整しています。
- 句読点
- 著者名の区切り方
- タイトル周辺の句読点
- 雑誌名の表示形式
- その他、日本語文献特有の出力規則

### 導入方法
このスタイルが Zotero の Style Repository に登録されると、Zotero 本体から以下の手順でインストールできます。
1. **編集** → **設定** を開く  
2. **引用** タブを開く  
3. **Get additional styles...** をクリックする  
4. **JPA Publication Manual revised 2022 edition** を検索する  
5. スタイルをインストールする  

### 既知の限界
日本語著者名の表記には、なお既知の限界があります。
JPA の規定では、日本語著者名について、たとえば次のように姓と名の間に半角スペースを入れる必要があります。

`山田 太郎`

しかし、この挙動は、標準的な Zotero / citeproc の処理のもとでは、CSL だけで完全に実装することができません。言い換えると、この CSL スタイル単体では、日本語著者名の姓と名の間に半角スペースを自動的に入れる処理を、すべてのケースで保証することはできません。
したがって、このスタイルは、標準的な CSL / Zotero の挙動の範囲内で JPA の規定を可能な限り再現するものであり、この点については技術的制約が残ることをご理解ください。

### CSL外での追加対応
この姓名間スペースの問題については、Zotero の内部処理ファイルを修正することで対応可能です。ただし、それは CSL スタイル本体の範囲を超える作業であり、このスタイルの通常の導入手順には含まれません。
その追加対応の詳細な手順については、[こちら](https://note.com/preview/ne5d6781d3f46?prev_access_key=107fe677e4c5cb01f88c4b1f8178483b)を参照してください。

この追加対応については、以下の点にご注意ください。
- この対応は任意です  
- 通常の利用にあたって必須ではありません  
- これは公式な CSL スタイル本体の範囲外です  

### 参考情報
- 日本心理学会『投稿・執筆の手びき』  
  https://psych.or.jp/manual/

### 補足
このスタイルは、日本語文献と英語文献を同一原稿内で併用しつつ、日本心理学会『投稿・執筆の手びき』に基づく書式を必要とする利用者を想定して作成されています。
細かな例外事例において手びきと完全一致しない挙動がある場合には、基本的に、標準的な CSL / Zotero の範囲内で安定して実装できることを優先しています。
