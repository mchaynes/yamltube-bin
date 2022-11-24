# YamlTube's Code

This repo contains the code that parses and synchronizes tube.yaml with your youtube account.
This is kept separate from the yamltube template so that updates can flow to the yamltube template without manual work from users.

If you want to use YamlTube, go to the [YamlTube repo](https://github.com/mchaynes/yamltube)

## Releases

yamltube-bin publishes a release on each push to master. yamltube's github action uses the latest release to run

### What does a YouTube playlist in Yaml look like?

```yaml
youtube:
  playlists:
    - title: Never Gonna Give You Up
      description: Never Gonna Let You Down
      visibility: public # or "private", or "unlisted"
      videos:
        - https://www.youtube.com/watch?v=dQw4w9WgXcQ
```

### Future Work: Spotify Playlists?

```yaml
spotify:
  playlists:
    - title: Walkin Fast
      tracks:
        - link: https://open.spotify.com/track/4w1lzcaoZ1IC2K5TwjalRP
        # or
        - title: A Thousand Miles
          artist: Vanessa Carlton
          album: Be Not Nobody
        # or
        - isrc: USIR10210955 # https://www.isrcfinder.com/
```
