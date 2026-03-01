# Fork of wyhash to pass smhasher3
This repository will contain patches for great wyhash to pass `smhasher3 --extra`.

As of March 2026, these are patches for [wyhash v4.2](https://github.com/wangyi-fudan/wyhash/).

## How to use
```
$ cd
$ git clone https://github.com/tankf33der/dryhash
$ git clone https://github.com/wangyi-fudan/wyhash/
$ cd wyhash
$ patch -p1 < ~/dryhash/wyhash32.h.patch
$ patch -p1 < ~/dryhash/wyhash.h.patch
$
```

License is `public domain` via Unlicense.
