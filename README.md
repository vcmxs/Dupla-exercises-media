# Dupla exercises media

Animated demonstrations and thumbnails used by the Dupla exercise library.

- `gif/<id>-<media>.gif` — 180×180 animation shown in the exercise reference dialog.
- `thumb/<id>-<media>.jpg` — 180×180 still used by the pickers.
- `manifest.json` — dataset id → file names + exercise name.

Media © Gym visual — https://gymvisual.com/ (see the upstream
[hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset) licence).

Consumed by the API through jsDelivr with a pinned commit:

```
https://cdn.jsdelivr.net/gh/<user>/Dupla-exercises-media@<commit-sha>
```

Pin the SHA (instead of a branch) so a force-push cannot silently change the
media under a running deployment.
