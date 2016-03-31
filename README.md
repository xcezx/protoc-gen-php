# protoc-gen-php

## Installation

Add xcezx/protoc-gen-php entry to your global composer.json ($HOME/.composer/composer.json)

```
{
    "minimum-stability": "dev",
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/stanley-cheung/Protobuf-PHP"
        }
    ],
    "require": {
        "xcezx/protoc-gen-php": "dev-master"
    }
}
```

install with composer

```
composer global install
```

set PATH

```
export PATH=$HOME/.composer/vendor/bin:$PATH
```

## How to use

```
protoc-gen-php tutorial.proto
```

See Also: http://drslump.github.io/Protobuf-PHP/
