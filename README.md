# PT-Gen-Database

[简体中文](README_CN.md) | English

The static export of the PT-Gen Database.
If you want to use all archive for other purposes, We recommend you use Download ZIP feature or git clone command to Download It.

```
Download ZIP
```

```
git clone
```

All data comes from Internet and is for learning purposes only!

## Update Status

- Last update at: 2026-06-06 00:05:46 (CST, UTC+08:00)
- Last data summary:

```
2026-06-06 00:05:46
```

- Report: Monthly Create, Daily Update

## Usage

You can use this repo by access the following link:

| Provider     | Status | Link Format                                                     | Note               |
|--------------|--------|-----------------------------------------------------------------|--------------------|
| Local Files  | Static | `./<site>/<sid>.json`                                           | Direct file access |
| GitHub Pages | Static | `https://rabbitwit.github.io/PT-Gen-Database/<site>/<sid>.json` | Web access         |

### Source SiteCount

| Source     | Count  |
|------------|--------|
| bangumi     | 6     |
| douban     | 541     |
| hongguo     | 2     |
| imdb     | 193     |
| melon     | 1     |
| qq_music     | 3     |
| steam     | 29     |
| tmdb     | 116     |
| trakt     | 106     |
| **Total**  | **997** |

### Data Format

The exported JSON format content is basically the same as that provided by the original APIs.

- The fields such as error, copyright, version, format are not provided in the exported file.
- The value format of some fields may vary in the export, This is mainly due to update of scraping and outdated crawling cache.

If there is no corresponding site data in current static export, you may try to access the original APIs as fallback to auto-generate it.

## About

The static export of the PT-Gen Database.
A comprehensive movie and TV database collection from multiple sources including Douban, IMDB, TMDB, and Melon.

## License

This project is licensed under MIT License - see the [LICENSE](LICENSE) file for details.
