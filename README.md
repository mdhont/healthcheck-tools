# healthcheck-tools
Set of Go tools to check different elements of your stack (SSL, SMTP, Permissions...). There is one tool per kind of check.

## Installation

```
$> go get github.com/bitnami-labs/healthcheck-tools/...
```

## Building from source

```
$> git clone https://github.com/bitnami-labs/healthcheck-tools.git
$> make
```

## Basic usage

The tools are located in the *cmd* folder. Each tool has its own README.md with basic instructions.

  - [SSL Checker](https://github.com/bitnami-labs/healthcheck-tools/tree/master/cmd/ssl-checker)
  - [SMTP Checker](https://github.com/bitnami-labs/healthcheck-tools/tree/master/cmd/smtp-checker)
