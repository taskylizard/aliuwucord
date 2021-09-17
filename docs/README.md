no, send help

Note: Do NOT change the json directly, use plugin settings or themer app instead.

Basic format for themes:

```json
{
    "manifest": {
        "author": "taskylizard#0000",
        "name": "Example",
        "updater": "",
        "version": "1.0.0",
        "license": ""
    },
    "background": {},
    "fonts": {},
    "simple_colors": {},
    "colors": {},
    "drawable_tints": {}
}
```

| Manifest ||||
|---------|--------|-------|------|
| Name | JSON key | Value(s)| Required?|
| Author | `"author"`| By default sets to your discord username.| Yes.|
| Name | `"name"`| Set when making a new theme.| Yes.|
| Updater| `"updater"`| Can only be set to `raw.githubusercontent.com` links. | No.|
| Version | `"version"`| By default sets to `1.0.0` for you, can be changed to whatever you desire, needs version bump to update themes for everyone. | Yes.|
| License | `"license"` | Can be set to whatever, see `https://choosealicense.com/`;`https://creativecommons.org/choose/`. this is not legal advice. | No.|

### These are unfinished docs, cry about it.
