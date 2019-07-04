参照：https://qiita.com/kyosuke5_20/items/c5f68fc9d89b84c0df09

## 1.nodebrew install
```bash
brew install nodebrew
```

## 2.pathをbash_profileにかく
```.bash_profile
export PATH=$HOME/.nodebrew/current/bin:$PATH
```
## 3.node install
```bash
mkdir -p ~/.nodebrew/src
nodebrew install stable

//nodebrewで使えるnodeのversionを確認
nodebrew ls

nodebrew use v10.xx.x
```

## 4.確認
```bash
node -v
npm -v
```
