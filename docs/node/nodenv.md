# nodenv 使い方

- インストール + 環境変数追加
```
brew install nodenv
export PATH="$HOME/.nodenv/bin:$PATH"
```

- .bash_profileか.zprofileに追加
```
eval "$(nodenv init -)"
```


- インストールできるバージョンの確認
```
nodenv install --list
```

- バージョンを指定してインストール
```
nodenv install [version]
```

- インストールしてあるバージョン
```
nodenv versions
```

- インストールした後はshimのリハッシュ。
```
nodenv rehash
```

- 使用端末全体(Global)でのバージョン指定
```
nodenv global [version]
```

- 現在いるディレクトリでのバージョン指定
```
nodenv local [version]
```