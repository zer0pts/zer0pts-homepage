# ![zer0pts](./public/assets/zer0pts.svg)

https://www.zer0pts.com/

## Asset sources

* `🥇.svg` ← https://twemoji.maxcdn.com/v/13.0.1/svg/1f947.svg
* `🥈.svg` ← https://twemoji.maxcdn.com/v/13.0.1/svg/1f948.svg
* `🥉.svg` ← https://twemoji.maxcdn.com/v/13.0.1/svg/1f949.svg
* `ctftime-logo.svg` ← https://ctftime.org/static/images/ct/logo.svg
* `gitlab-logo.svg` ← https://docs.gitlab.com/assets/images/gitlab-logo.svg
* `fonts.css` ← https://fonts.googleapis.com/css2?family=Nerko+One&family=Open+Sans:wght@400;700&display=swap (modified: latin parts only, edited src, removed unicode-range)
* `fonts.gstatic.com/[...]` ← <https://fonts.gstatic.com/[...]> (see Fonts)

## Scoreboard

The `scoreboard.txt` file is a copy-paste from <https://ctftime.org/team/54599>.

You can find noteworthy CTFs with `grep -P '^\t' scoreboard.txt | awk '$1 <= 3'`.

## Members

[ptr-yudai, st98, theoldmoon0602, yoshiking] → [aventador] → [x0r19x91] → [keymoon] → [mitsu] → [s1r1us] → [S3v3ru5] → [jskim] → [kot]

How to generate random avatars:

```
convert -size 16x16 xc: +noise Random -scale 256x256 -strip public/assets/avatars/${username}.png
```

The `update-avatars.sh` script can be used to automatically pull avatars from GitHub (and potentially other sources).

## Fonts

```
cd public/assets
wget -x https://fonts.gstatic.com/s/nerkoone/v2/m8JQjfZSc7OXlB3ZMOjDd5RA.woff2 https://fonts.gstatic.com/s/opensans/v18/mem8YaGs126MiZpBA-UFVZ0b.woff2 https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN7rgOUuhp.woff2
```
