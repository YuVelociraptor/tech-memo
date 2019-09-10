# pyenv 使い方

```
brew install pyenv
```

- .bash_profile
```
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
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