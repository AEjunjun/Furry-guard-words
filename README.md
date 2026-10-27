# furry-guard

Furry culture discrimination / provocative speech blocklist library

## What it is
A lightweight, standalone Furry-specific blocklist extension library,
can be used with a main filtering system or on its own.

## Word list description
- `toxic.txt` - Hard block (explicit insults / sexual content / bestiality)
- `dogwhistle.txt` - Soft tag (provocative dog-whistle phrases)
- `slur_en.txt` - English slurs
- `allowlist.txt` - Whitelisted normal words
- `regex.txt` - Regex rules (reserved)

## Contributing
Feel free to add to the word lists! Just make a PR and add words to the corresponding txt files,
format: one word per line, lines starting with # are comments.

## License
MIT License
