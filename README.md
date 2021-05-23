

# JS

```shell
❯ alias vsc-js='code --user-data-dir ~/code-profiles/js/data —-extensions-dir ~/code-profiles/js/extensions'
```

```shell
❯ for ext in `cat ~/code-profiles/js/extensions/extensions.txt `; do
 vsc-js —-install-extension $ext
done
```

# PHP

```shell
❯ alias vsc-php='code --user-data-dir ~/code-profiles/php/data —-extensions-dir ~/code-profiles/php/extensions'
```

```shell
❯ for ext in `cat ~/code-profiles/php/extensions/extensions.txt `; do
 vsc-php —-install-extension $ext
done
```

# PYTHON

```shell
❯ alias vsc-py='code --user-data-dir ~/code-profiles/py/data —-extensions-dir ~/code-profiles/py/extensions'
```

```shell
❯ for ext in `cat ~/code-profiles/py/extensions/extensions.txt `; do
 vsc-py —-install-extension $ext
done
```