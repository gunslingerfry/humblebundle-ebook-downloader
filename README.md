# humblebundle-ebook-downloader

An easy way to download ebooks from your humblebundle account

## Installation

```shell
$ npm install -g humblebundle-ebook-downloader
```

## Usage

```shell
$ humblebundle-ebook-downloader --help

  Usage: humblebundle-ebook-downloader [options]

  Options:

    -h, --help                                 output usage information
    -V, --version                              output the version number
    -d, --download-folder <downloader_folder>  Download folder, defaults to ./download
    -l, --download-limit <download_limit>      Parallel download limit, defaults to 1
    -f, --format <format>                      What format to download the ebook in (all, cbz, epub, mobi, pdf, pdf_hd), defaults to epub
    --auth-token <auth-token>                  Optional: If you want to run headless, you can specify your authentication cookie from your browser (_simpleauth_sess)
    -a, --all                                  Download all bundles
```

## Contributors
- [J. Longman](https://github.com/jlongman)
- [Johannes Löthberg](https://github.com/kyrias)

## License
See [LICENSE.md](LICENSE.md)
