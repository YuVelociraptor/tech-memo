# pyenv 使い方

- インストール + 環境変数追加
```
brew install pyenv
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
```

- .bash_profileか.zprofileに追加
```
eval "$(pyenv init -)"
```

- インストールできるバージョンの確認
```
pyenv install --list
```

- python指定バージョンインストール
```
pyenv install [version]
```

- 使用端末全体(Global)でのバージョン指定
```
pyenv global [version]
```

- 現在いるディレクトリでのバージョン指定
```
pyenv local [version]
```