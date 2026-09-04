# QAレポート（自動生成: scripts/qa_check.py）

- 対象: `output/`（1ページ: index.html）
- 結果: **ERROR 3 / WARN 0 / INFO 2**

## ERROR（必ず直す）
- `robots.txt`: 存在しない
- `sitemap.xml`: 存在しない
- `llms.txt`: 存在しない

## WARN（確認して判断）
- なし

## INFO（参考）
- `index.html`: JSON-LD OK: ['GeneralContractor']
- `robots.txt`: 全ページが noindex。検索避けの成果物として扱い、全拒否と Sitemap 無しを正常とみなす

※ ブラウザ実測（PC1440/SP320・360・390、scrollWidth<=clientWidth、固定CTA実測高、デザイン忠実度、アニメーション）は site-qa Skill の手順で別途確認する。