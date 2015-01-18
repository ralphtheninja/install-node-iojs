# install-node-iojs

Install scripts for `node` and `iojs`.

## install-node

`install-node [version] [arch] [root]`

Installs different versions of `node` for different *nix architectures.  Takes the following parameters:

* `version` Optional. Defaults to `0.10.35`.
* `arch` Optional. Defaults to `linux-x64`.
* `root` Optional. Defaults to `releases`.

#### examples

Install version `0.10.35` with `linux-x64` architecture in `releases` folder:

```
$ install-node
node-v0.10.35-linux-x64 installed in releases/node/linux-x64/0.10.35
```

Install version `0.10.20` with `sunos-x86` architecture in `/tmp` folder:

```
$ install-node 0.10.20 sunos-x86 /tmp
node-v0.10.20-sunos-x86 installed in /tmp/node/sunos-x86/0.10.20
```

## install-iojs

`install-iojs [version] [arch] [root]`

Installs different versions of `iojs` for different *nix architectures.  Takes the following parameters:

* `version` Optional. Defaults to `1.0.2`.
* `arch` Optional. Defaults to `linux-x64`.
* `root` Optional. Defaults to `releases`.

#### examples

Install version `1.0.2` with `linux-x64` architecture in `releases` folder:

```
$ install-iojs
iojs-v1.0.2-linux-x64 installed in releases/iojs/linux-x64/1.0.2
```

Install version `1.0.0` with `linux-armv7l` architecture in `/tmp` folder:

```
$ install-iojs 1.0.0 linux-armv7l /tmp
iojs-v1.0.0-linux-armv7l installed in /tmp/iojs/linux-armv7l/1.0.0
```

## License
WTFPL