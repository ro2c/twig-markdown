CHANGELOG
=========

2.1.0
-----

- **FIX**: Upgrade to Twig 2.7 and namespace, due to [a security issue](https://symfony.com/blog/twig-sandbox-information-disclosure)

2.0.0
-----

- **BC**: Require Twig v1.12, in order to replace deprecated Twig_Filter_Method with Twig_SimpleFilter
- **Added**: Add support for ParsedownEngine

1.2.0
-----

- **Added**: Add support for GitHub's markdown engine

1.1.0
-----

- **Added**: Add support for PHP League CommonMark engine

1.0.0
-----

- **BC**: Remove deprecated dflydev-markdown parser
