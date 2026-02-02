# @socket-override-override/date

zero dependency replacement for [date](https://npmjs.com/date)

## wai?
@socketregistry/date doesn't include the cache.js file, which isn't even supposed to be requirable, but one 10xly package needs it. and we needed a zero-dependency override instead of just the date package for the lolite-browser package which also doubles as a lightweight one-dependency replacement for normal lolite.