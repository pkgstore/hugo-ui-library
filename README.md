# Hugo UI Library

Base theme for Hugo.

## Install

```
git submodule add https://github.com/pkgstore/hugo-ui-library.git themes/ui-library
```

## Update

```
git submodule update --recursive --remote --merge
```

## Uninstall

```
git submodule deinit -f themes/ui-library; git rm -r --cached themes/ui-library; rm -rf .git/modules/themes/ui-library; rm -rf themes/ui-library
```

## Features / Особенности

- Некоторые категории носят функциональный характер.
  - Если нода в категории `InDev`, то она приобретает плашку **Информация в доработке**.
  - Если нода в категории `Subjectivity`, то она приобретает плашку **Субъективное мнение автора**.
