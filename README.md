A [yt-dlp](https://github.com/yt-dlp/yt-dlp) postprocessor [plugin](https://github.com/yt-dlp/yt-dlp#plugins) for [DeArrow](https://dearrow.ajay.app/).

Note: The API has [rate-limiting](https://returnyoutubedislike.com/docs/usage-rights)


## Installation

Requires yt-dlp `2023.01.01` or above.

You can install this package with pip:
```
python3 -m pip install -U https://github.com/mikkovedru/yt-dlp-dearrow/archive/master.zip
```

See [yt-dlp installing plugins](https://github.com/yt-dlp/yt-dlp#installing-plugins) for the many other ways this plugin package can be installed.

## Usage

Pass `--use-postprocessor DeArrow:when=pre_process` to activate the PostProcessor
