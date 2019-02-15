appengine-static-site
====

AppEngineを使った静的サイトのテンプレートです.
Cloud Buildを使用したCDの設定も用意してあります.

### 注意点
- コーディングは絶対パスではなく相対パスで実装する
- Dos対策のためCDNに10秒ほどキャッシュするようにしています

## Deploy
Cloud Build

or

```bash
gcloud app -q deploy app.yaml --promote
```
