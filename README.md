# Mautic Finder

[![Travis](https://img.shields.io/travis/nickveenhof/mautic-finder.svg)](https://travis-ci.org/nickveenhof/mautic-finder) [![Packagist](https://img.shields.io/packagist/v/nickveenhof/mautic-finder.svg)](https://packagist.org/packages/nickveenhof/mautic-finder)

Mautic Finder provides a class to locate a Mautic installation in a given path.

## Usage

```PHP
$mauticFinder = new \MauticFinder\MauticFinder();
if ($mauticFinder->locateRoot(getcwd())) {
    $mauticRoot = $mauticFinder->getMauticRoot();
    $composerRoot = $mauticFinder->getComposerRoot();
    ...
}
```

## License

GPL-2.0+
