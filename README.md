# BalanceFlow Exercise Index

A transport-optimized Chinese index derived from
[`hasaneyldrm/exercises-dataset`](https://github.com/hasaneyldrm/exercises-dataset)
for BalanceFlow's remote exercise-library setting.

Direct JSON:

```text
https://cdn.jsdelivr.net/gh/cth123456/balanceflow-exercise-index@v3/exercises.zh.min.json
```

The file keeps all 1,324 exercise records and Chinese tutorial steps while
removing unused translations. Thumbnail and GIF fields are absolute jsDelivr
URLs, so the JSON can be consumed without a separate media-base setting.

Version 3 keeps the accurately matched, tap-to-play tutorial videos for 34
popular exercises and adds `legacy_ids` for common BalanceFlow movements.
Existing training records can therefore resolve to the selected remote GIF
and tutorial instead of silently falling back to a bundled illustration.
Those videos come from the public wger exercise API and retain their CC BY-SA
4.0 attribution. Other exercises continue to provide an animation GIF and
written steps instead of being matched to the wrong video.

The dataset structure and instruction text follow the upstream MIT license.
Exercise media is © Gym Visual and is not covered by the MIT license. The index
retains the required attribution; obtain separate media rights before
commercial use.
