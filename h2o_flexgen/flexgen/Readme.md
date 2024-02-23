# What does each variable mean?

`acc` is a holder for attention weights to remember which ones to remove(least heavy hitter.)
`kick_ind` - index of the indices that should be removed from the cache.
`hh_k` - that represents K in the paper. It's the number of recent tokens to keep and at the same time the number of heavy hitters to keep.
