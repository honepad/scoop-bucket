# honepad Scoop bucket

```powershell
scoop bucket add honepad https://github.com/honepad/scoop-bucket
scoop install honepad/honepad
```

Requires a Scoop `python` install. Each GitHub Release of
[honepad/honepad](https://github.com/honepad/honepad) rewrites
`bucket/honepad.json`. The committed JSON is the source of truth.
`checkver` is a fallback only.

This bucket is not in Scoop Main or Extras. `scoop search` will not
find honepad until you add the bucket.
