# kbot
devops application from scratch

t.me/setius1_bot

go mod init github.com/Setiuss/kbot

go install github.com/spf13/cobra-cli@latest

cobra-cli init

cobra-cli add version

cobra-cli add kbot

gofmt -s -w ./

go get

go build -ldflags "-X="github.com/Setiuss/kbot/cmd.appVersion=v1.0.0

read -s TELE_TOKEN

echo $TELE_TOKEN

export TELE_TOKEN

go build -ldflags "-X="github.com/Setiuss/kbot/cmd.appVersion=v1.0.1

./kbot start
