# furry-guard

[简体中文](/README/README_CN.md) | English

Furry culture discrimination / provocative speech blocklist library

## What it is
A lightweight, standalone Furry-specific blocklist extension.
No code implementation included — this is a pure word list pack,
can be used with a main filtering system or on its own.

## Word list description
- `toxic.txt` - Hard block (explicit insults / sexual content / bestiality)
- `dogwhistle.txt` - Soft tag (provocative dog-whistle phrases)
- `slur_en.txt` - English slurs
- `allowlist.txt` - Whitelisted normal words
- `regex.txt` - Regex rules (reserved)

## Contributing
Feel free to add to the word lists! Just make a PR and add words to the corresponding txt files,
format: one word per line, `#` for comments, empty lines ignored.

## Disclaimer
This word list is provided as-is, without warranty of any kind.
False positives and false negatives are expected.
Always combine with human review or your own filtering layer.
Not a substitute for manual moderation.

## License
MIT License — see [LICENSE](LICENSE) for details.
