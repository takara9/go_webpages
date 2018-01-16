# Goウェブサーバー テストページ

export GOPATH=`pwd`
go get github.com/takara9/go_webserver2
go get github.com/tools/godep
godep save github.com/takara9/go_webserver2

rm -fr bin pkg src

git init

$ git submodule add https://github.com/takara9/go_util.git  go_util
$ git submodule add https://github.com/takara9/go_webserver2.git  go_webserver2

