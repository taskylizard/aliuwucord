send help im dying oh my god

Note: Do NOT change the json directly, use plugin settings or themer app instead. Also, make your themes in normal dark mode, not the experimental amoled mode. 

### Basic format for themes:

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
##### Manifest
| Manifest ||||
|---------|--------|-------|------|
| Name | JSON key | Value(s)| Required?|
| Author | `"author"`| By default sets to your discord username, can be changed.| Yes.|
| Name | `"name"`| Set when making a new theme, can be changed.| Yes.|
| Updater| `"updater"`| Can only be set to `raw.githubusercontent.com` links. | No.|
| Version | `"version"`| By default sets to `1.0.0` for you, can be changed, needs version bump to update themes for everyone. | Yes.|
| License | `"license"` | Can be set to whatever, see `https://choosealicense.com/`;`https://creativecommons.org/choose/`. this is not legal advice. | No.|

##### Background
|Background||||
|------|----|-----|----|
| Name | JSON Key| Value(s)| Required?|
| Url | `"url"` | A *direct* link to any background, usual phone resolutions are preferred, only supports certain hosts for security reasons. Supported image hosts: | No.|
| Overlay Alpha | `"overlay_alpha"` | Darkens the image, ranges from 0-255. | No. |
| Blur Radius | `"blur_radius"` | Changes the blur radius of the image, ranges from 0-25. `25` makes the transparency fully opaque, `0` for full. | No. |



#### These are unfinished docs, take the L.
