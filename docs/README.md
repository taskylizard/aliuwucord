send help im dying oh my god

**Note: Do NOT change the json directly, use plugin settings or themer app instead. Also, make your themes in normal dark mode, not the experimental amoled mode.** 

- [Basic format for themes:](#basic-format-for-themes-)
    + [Supported hosts for fonts/images:](#supported-hosts-for-fonts-images-)
  * [Manifest](#manifest)
  * [Background](#background)
  * [Fonts](#fonts)
  * [Simple Colors](#simple-colors)
- [These are unfinished docs, take the L.](#these-are-unfinished-docs--take-the-l)

#### Basic format for themes:

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

###### Supported hosts for fonts/images:

All of these are direct links, so keep that in mind when adding your own.

- `raw.githubusercontent.com`
- `gitlab.com`
- `cdn.discordapp.com`
- `media.discordapp.net`
- `i.imgur.com`
- `i.ibb.co`


##### Manifest

| Manifest |||
|---------|-------------|----------|
| Options | Description | Required?|
| `author`| By default sets to your discord username, can be changed.| Yes.|
| `name` | Set when making a new theme, can be changed.| Yes.|
| `updater` | Can only be set to `raw.githubusercontent.com` links. | No.|
| `version` | By default sets to `1.0.0` for you, can be changed, needs version bump to update themes for everyone. | Yes.|
| `license` | Can be set to whatever, see `https://choosealicense.com/`;`https://creativecommons.org/choose/`, this is not legal advice. | No.|

##### Background

|Background|||
|---------|-------------|--------|
| Options | Description |Value(s)|
| `url` | A *direct* link to any background, usual phone resolutions are preferred, only supports certain hosts for security reasons. | See [#supported-hosts-for-fonts/images](#supported-hosts-for-fonts-images) for options.|
| `overlay_alpha` | Darkens the image. | 0-255 |
| `blur_radius` | Changes the blur radius of the image,`25` makes the transparency fully opaque, `0` for full. | 0-25 |

##### Fonts

Note: These will require you a direct link to a `.ttf` or `.otf` font.

| Options | Description |
|---------|-------------|
|`*`|Changes everything, pretty much.|
|`ginto_bold`|Changes categories, channel names, user settings headers.|
|`ginto_medium`| Changes channel name in members list, user setting category names.|
|`ginto_regular`| Found none that changed.|
|`roboto_medium_numbers`| Found none that changed. |
|`sourcecodepro_semibold`| Found none that changed. |
|`whitney_bold`| Changes server template names, and invites.|
|`whitney_medium`| Changes message text, channel names, button names. |
|`whitney_semibold`| Changes selected channel name and DM list name.|

##### Simple Colors

| Options  | Description |
|----------|-------------|
| `accent` | Changes loads like bot tags `[BOT]`, the `int(x) messages since int(time)` header at the top, cursor color, `Manage subscription` with the badge color in settings, save/toggled on buttons, reacted reaction border, and color for links or hyperlinked text. | 
|`background`|omegalol come back later dumbass|

#### These are unfinished docs, take the L.
