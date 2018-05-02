# ethereum_token_handson
Ethereumトークン作成ハンズオンのvagrant boxです

## インストール

zipをダウンロードして解凍して下さい。

githubアカウントをお持ちの方は以下のコマンドでダウンロード可能です。

```bash
git clone git@github.com:shunsukehondo/ethereum_token_handson.git
```

または

```bash
git clone https://github.com/shunsukehondo/ethereum_token_handson.git
```

その後、ターミナルまたはコマンドプロンプトを開き以下のコマンドを実行して下さい。


```bash
cd path/to/ethereum_token_handson
vagrant init ./ethereum_token_handson.box
```

## 起動

```bash
vagrant up
```

## ログイン

```bash
vagrant ssh
```

## ログアウト

仮想マシン上で

```
exit
```

## シャットダウン

```bash
vagrant halt
```

## 仮想マシンの削除

```bash
vagrant destroy
```

## 現状の仮想マシンを保存

```bash
vagrant package
```

## 保存した仮想マシンから初期化

```bash
vagrant init path/to/package.box
```

