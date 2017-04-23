# Install WordPress test environment

It installs WordPress test environment for PHPUnit.

## How to use

Run following command.

```
$ curl -L https://raw.githubusercontent.com/oppara/install-wp-test-env/args_order/install.sh | bash
```

You can specify wordpress version and DB informations 

```
$ curl -L https://raw.githubusercontent.com/oppara/install-wp-test-env/args_order/install.sh | bash -s <wp-version> [db-name] [db-user] [db-pass] [db-host] 
```

## Requires

* PHPUnit
* WP-CLI

## Running PHPUnit

```
$ wp scaffold plugin <plugin-slug>
$ cd <plugin-slug>
$ phpunit
```
