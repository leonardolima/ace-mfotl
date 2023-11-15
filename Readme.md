## Ace MFOTL
This is a fork of [Ace](https://github.com/ajaxorg/ace) that includes [Ace MFOTL Modes](https://github.com/leonardolima/ace-mfotl-modes).

## Usage
First, you need to install `npm`.

Next, you can build this fork using the same instructions for [Ace](https://github.com/ajaxorg/ace):
```
$ npm install
$ node Makefile.dryice.js full
```
from the root folder.

However, you might have ended up here because of [WhyMon](https://github.com/runtime-monitoring/whymon).

To replace the content of `../whymon/vis/node_modules/ace-builds` with the built up version of this fork, you can simply run the script `build_copy`:

```
$ ./build_copy.sh
```
from the root folder.

## License

See [LICENSE](LICENSE) for details.
