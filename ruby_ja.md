# CLIアプリケーション作成方法 (Ruby)

[main.rb](app/main.rb)を編集して、CLIアプリを実装してください。  
チャレンジ内でファイルの作成が許可されていれば、可読性等のためにファイルを分割する事も可能です。

## コマンドライン引数の取得方法
[main.rb](app/main.rb)内で定義されている、`main`という関数から、 `argv` の名前で取得可能です。  

``` rb
def main(argv)
  # code to run
end
```

ここでの `argv` は [index.rb](index.rb) から渡されるもので、`ARGV` の内容がそのまま渡されます。

## コマンド実行結果の標準出力への出力
`stdout` への出力は標準の `puts` メソッド等が使用可能です

``` ruby
puts "Hello World"
```

## 外部ライブラリの追加方法
外部ライブラリを使用する場合は以下の手順で実施してください。

- [Gemfile](Gemfile)にライブラリ名を記述
