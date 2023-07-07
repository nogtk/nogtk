## generate_summary_cards が失敗したとき
token が expire してないか確認する。
expire していた場合は拡張し、新しいトークンをコピーする。
コピーしたトークンを GitHub Action用の secrets として `CARD_SUMMARY_TOKEN` を更新する。
