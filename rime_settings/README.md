# Rime settings

Personal settings for Rime Squirrel on macOS:

- Natural Code double pinyin as the primary schema
- Simplified full pinyin as a fallback schema
- Raw double-pinyin input in the preedit area
- A larger, horizontal candidate window

## Install

Make sure `double_pinyin.schema.yaml` and `luna_pinyin_simp.schema.yaml` are
available in `~/Library/Rime`, then copy the custom files into that directory.
Merge their `patch` entries if custom files already exist on the target machine.

Deploy the settings with:

```bash
'/Library/Input Methods/Squirrel.app/Contents/MacOS/Squirrel' --build
'/Library/Input Methods/Squirrel.app/Contents/MacOS/Squirrel' --reload
```

Use `Control+grave` or `F4` to switch between the two schemas.
