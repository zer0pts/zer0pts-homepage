# ![zer0pts](./public/assets/zer0pts.svg)

https://www.zer0pts.com/

## Asset sources

* `🥇.svg` ← https://twemoji.maxcdn.com/v/13.0.1/svg/1f947.svg
* `🥈.svg` ← https://twemoji.maxcdn.com/v/13.0.1/svg/1f948.svg
* `🥉.svg` ← https://twemoji.maxcdn.com/v/13.0.1/svg/1f949.svg
* `ctftime-logo.svg` ← https://ctftime.org/static/images/ct/logo.svg
* `gitlab-logo.svg` ← https://docs.gitlab.com/assets/images/gitlab-logo.svg

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
