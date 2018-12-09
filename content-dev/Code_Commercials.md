## Code Commercials

garyb/purescript-codec: General purpose bi-directional codecs.

```
basicCodec :: forall m a b. (a -> m b) -> (b -> a) -> BasicCodec m a b
encode :: forall m a b c d. Codec m a b c d -> c -> b
decode :: forall m a b c d. Codec m a b c d -> a -> m d
```
