# FL Practice Diff Maker
simple program for making practice diffs in osu! standard, mainly for FL players

<img src="https://user-images.githubusercontent.com/76718358/125244362-3e7ce180-e2bd-11eb-8619-5a0e575388a8.png" width="555">

### Name Format Templates
Format | Example Result | Description
------------ | ------------- | -------------
`{v} {i}` | Nostalgia 3 |
`{v} ({i}/{n})` | Nostalgia (3/5) | diff index / total diffs (*default format*)
`{v} ({sc}/{mc}x)` | Nostalgia (222/1682x) | combo at start / total combo
`{v} {sc}-{ec}x` | Nostalgia 222-440x | combo at start - combo at end of diff
`{v} {s}-{e}` | Nostalgia 0:45-1:22 | start time - end time

### Shortcut Keys
Shortcut | Function
------------ | -------------
ctrl + shift + z | add practice diff
ctrl + shift + x | set end time of last added diff
ctrl + shift + space | create practice diffs
alt + shift + a | add practice diff (*customizable*)
alt + shift + s | create practice diffs (*customizable*)

### Matching Combo Colors
If you have disabled beatmap skin:
1. Open options and check `Add circles for combo color`
2. Enter the number of combo colors your skin has in `# of skin colors`

If you have enabled beatmap skin, colors will match automatically.

### Matching Combo Number
1. Open options and uncheck `Cap Combo`  
*Note: for large combos, you will need to increase* `Slider duration` *when using sliders and* `Gap duration`*when using spinners*
