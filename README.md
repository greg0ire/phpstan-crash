Crash me with
```shell
composer install --no-scripts
sed -i 's/\.\.\/vendor\/autoload/..\/..\/..\/..\/vendor\/autoload/' vendor/phpstan/phpstan-src/bin/phpstan
vendor/bin/phpstan --ansi analyse --no-progress -c phpstan.neon  -vvv
```
