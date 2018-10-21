# keep2scrapbox

Google Keep のデータを Scrapbox の import する JSON 形式にコンバートする

## Usage

### Google Takeout からデータのアーカイブを取得する

https://takeout.google.com/settings/takeout

### 実行ディレクトリに配置し、解凍する

`Takeout/Keep/` ディレクトリができることを確認する

### 実行する

```sh
$ bundle install --path vendor/bundle
$ bundle exec ruby keep2scrapbox.rb
```

### Scrapbox に import する

[Scrapbox の [Settings] > [Page Data]](https://scrapbox.io/projects/<YOUR_PROJECT>/settings/page-data) から生成された `import***.json` ファイルをインポートする
