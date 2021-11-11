## Album Construction
Inside your project create the directory assets/NAME-OF-YOUR-ALBUM. Place all of one album's photos inside that directory.

Inside your project run:
```shell
$ hugo new NAME-OF-YOUR-ALBUM/_index.md
```

It will create an index file for your first album. Open content/NAME-OF-YOUR-ALBUM/_index.md with your text editor. You'll see something like this:

```shell
---
title: "NAME-OF-YOUR-ALBUM"
date: "2020-03-15T00:00:00+00:00"
albumthumb: "NAME-OF-YOUR-ALBUM/photo00.jpg"
draft: false
resources:
- src: "NAME-OF-YOUR-ALBUM/photo00.jpg"
- src: "NAME-OF-YOUR-ALBUM/photo01.jpg"
- src: "NAME-OF-YOUR-ALBUM/photo02.jpg"
---
```

## local preview
```shell
hugo server -D
```


## push and deploy
```shell
sh fast-deploy.sh
```

***quote: https://github.com/kc0bfv/autophugo***