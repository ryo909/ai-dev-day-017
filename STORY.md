# Day017 Story — Incident Response Wizard

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day017専用にテーマをseed固定して再生成時の見た目を安定化
- devtools用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: incident_wizard
- Mechanic: branching_triage
- Input/Output: step_choices -> response_flow
- Audience Promise: faster_incident_response
- Publish Hook: 初動手順を分岐で迷わず確定
- Complexity Tier: small
- Selected components: none
- Complexity hint: Keep the tool single-purpose and stable. Add at most one safe enhancement component.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day017｜Incident Response Wizard
障害初動フローをステップ分岐で確定する運用ウィザード。（話題:HN Frontpage）
