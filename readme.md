medium client

- v0.1-0.3 : the app-key(cliend_id) is stopped.

[releases](https://github.com/syui/medigo/releases)

If you do not use the releases version, you will need a key. Create an app with [medium](https://github.com/Medium/medium-api-docs/blob/master/README.md).

aur : https://aur.archlinux.org/packages/medigo

```sh
$ yay -S medigo
```

## use

```sh
$ medigo o
paste code

$ medigo h
```

## build

```bash
$ git clone https://github.com/syui/medigo 
$ cd medigo
$ go build -ldflags "-X main.cid=$client_id -X main.secret=$secret_id"
$ ./medigo h
```

