# 418 I am a Teapot

This website is only a documentation on what i learn ect ...

# Enable translations

```bash
MDBOOK_OUTPUT='{"xgettext": {}}' mdbook build -d po
msgmerge --update po/fr.po po/messages.pot
```

```bash
MDBOOK_BOOK__LANGUAGE=fr mdbook serve --hostname 0.0.0.0 -d book/fr
```