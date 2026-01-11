# proto-plugins

Some additional Moon repo [Proto](https://moonrepo.dev/docs/proto) plugins for tools we use.

## Pulumi

Install [Pulumi](https://www.pulumi.com/) infrastructure as code:

Add the plugin to Proto:

```shell
$ proto plugin add pulumi https://raw.githubusercontent.com/Reclamefolder/proto-plugins/refs/heads/main/toml/pulumi.toml
```

Then install pulumi via Proto!

```shell
$ proto install pulumi --pin
```

## Lychee

Install the [Lychee](https://lychee.cli.rs/) link checker tool:

Add the plugin to Proto:

```shell
$ proto plugin add lychee https://raw.githubusercontent.com/Reclamefolder/proto-plugins/refs/heads/main/toml/lychee.toml
```

Then install lychee via Proto!

```shell
$ proto install lychee --pin
```

## yq

Install [yq](https://github.com/mikefarah/yq) (the go implementation by mikefarah) - a lightweight and portable command-line YAML, JSON and XML processor:

Add the plugin to Proto:

```shell
$ proto plugin add yq https://raw.githubusercontent.com/Reclamefolder/proto-plugins/refs/heads/main/toml/yq.toml
```

Then install yq via Proto!

```shell
$ proto install yq --pin
```
