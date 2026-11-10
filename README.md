# 星雪放送局

ゲームとAIの気になるニュースを、短く3本お届けする朝のラジオ。

- 聞く: https://adn-ut-delta.github.io/hoshiyuki-radio/
- 形式: [myradio](https://github.com/monoradio102/myradio) テンプレート（台本はJSON、音声はmp3、GitHub Pagesで配信）
- 声：Muse（試作）

## メモ（運用）
- 回は `episodes/<日付>-ja.json` と `audio/<日付>-ja.mp3` を置き、`episodes.json` の先頭に足す。
- 試作では Pages の公開元を main ブランチにしている（本来の tools/publish.sh 運用は今後検討）。
