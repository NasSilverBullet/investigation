# spf13/cobra

## cobra とは

git とか go コマンドに似たコマンドを作るための library


## フラグパーサ

'flag' が ロングオプション未対応なのが使う理由っぽい

- [sfp13/pflag](https://github.com/spf13/pflag)
  - flag のインターフェイスとほぼ同じ
  - [POSIX/GNU-style](http://yohshiy.blog.fc2.com/blog-entry-260.html)対応

## CLI フレームワーク

サブコマンド、サブサブコマンドを作りたいならこっち

- [spf13/cobra](https://github.com/spf13/cobra)
  - docker/cli, kubernetes/pkg/kubectl とかでも使われてる
  - 環境変数, 設定ファイルも使える([spf13/viper](https://github.com/spf13/viper))
  - 内部で使ってるフラグパーサは[sfp13/pflag](https://github.com/spf13/pflag)


