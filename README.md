# IteratorTrait

Often used implementation of the IteratorInterface

## Installation

```bash
composer require org_heigl/trait-iterator
```

## Usage

Add it to a class like this:

```php
use Org_Heigl\IteratorTrait\IteratorTrait;

class MyList implements \Iterator
{
    use IteratorTrait;

    protected $yourArrayToIterateOver = [];

    public function & getIterableElement()
    {
        return $yourArrayToIterateOver
    }
}
```

The rest of the Iterator implementation is andled within the IteratorTrait.

## Issues

Feel free to drop an issue on github when you need help.