Try it here: https://topaz.github.io/paste/

This is a no-datastore, client-side paste service.  It turns text into [LZMA](https://en.wikipedia.org/wiki/Lempel%E2%80%93Ziv%E2%80%93Markov_chain_algorithm)-compressed, [Base64](https://en.wikipedia.org/wiki/Base64)-encoded URLs.

For example, here's [the service hosting (a version of) its own HTML](https://topaz.github.io/paste/#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).

Because the entire paste is inside the URL, there's no risk of losing your data because a 3rd-party service vanished or deleted old pastes.  If you have the URL, you have the pasted data.

Uses [LZMA-JS](https://github.com/LZMA-JS/LZMA-JS) (© 2016 Nathan Rugg <nmrugg@gmail.com>).
