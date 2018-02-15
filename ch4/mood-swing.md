```haskell
data Mood = Blah | Woot deriving Show
```

1. `Mood`
2. `Blah` or a `Woot` that derives `Show`
3. Can't change `Blah` into `Woot`
4. ```haskell
changeMood Blah = Woot
changeMood    _ = Blah
```
