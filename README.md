# amendlog-eu — EU regulations as git history (prototype)

**Unofficial. Not legal advice. Only the Official Journal of the EU is authentic. / 非公式。法律相談ではありません。正文は EU 官報のみです。**

## English
Consolidated versions of selected EU regulations from [EUR-Lex](https://eur-lex.europa.eu/) (Cellar SPARQL + XHTML), one commit per consolidated version.
- Commit date = the date of the consolidated version. The original act is committed on its entry-into-force date.
- `Amending-Act` trailers list the CELEX numbers that the consolidated version incorporates.
- Future-dated consolidated versions are on the `upcoming` branch.
- Acts: GDPR (32016R0679), AI Act (32024R1689), MDR (32017R0745), CRR (32013R0575). English text only.

## 日本語
EUR-Lex の統合版（consolidated version）を版ごとに1コミットにした試作です。未来日付の版は `upcoming` ブランチにあります。

## Source and licence / 出典とライセンス
Source: EUR-Lex, © European Union, https://eur-lex.europa.eu/. Reused under the [Commission reuse policy (Decision 2011/833/EU)](https://eur-lex.europa.eu/eli/dec/2011/833/oj) and [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Changes: converted from XHTML to Markdown, layout simplified.

## Known limitations / 既知の限界
- Consolidated texts are documentation tools; the institutions do not assume liability for their content.
- Tables and annexes are simplified; images are omitted.
- Some Cellar metadata has placeholder entry-into-force dates; the document date is used instead.

## Build / ビルド
See https://github.com/meatless-labs/amendlog-builder: `python3 lawgit/eu.py`.
