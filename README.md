hello go cli

```sh
mkdir hello-go-cli
cd hello-go-cli

go mod init github.com/oizhaolei/hello-go-cli

go get github.com/spf13/cobra/cobra

cobra init --pkg-name github.com/oizhaolei/hello-go-cli
cobra add serve
cobra add config
cobra add create -p 'configCmd'

go run main.go
```