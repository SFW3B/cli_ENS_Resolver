# ensResolver

ensResolver is a PHP CLI tool that allows anyone to access information on the Ethereum Name Service (ENS) using EthDNS(https://eth.link) API. 

## Features

- Lookup a single .eth domain
- lookup multiple .eth domains from input file
- Remove checked domains from file
- Save checked domains and data to csv

## Usage/Examples
Single domain lookup

```php
php ensResolverCLI vitalik.eth
```

Load domains from file

```php
php ensResolverCLI -f list
```

## Authors

- [@SFW3B](https://www.github.com/SFW3B)