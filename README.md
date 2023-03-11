Anki Add-on for integration with Cambridge Dictionary web site - https://dictionary.cambridge.org/

Create Anki package:
```bash
cd anki_cambridge && zip -r ../anki-cambridge-by-word.ankiaddon *
```
Tools -> Add-ons -> Install from file -> Select anki-cambridge-by-word.ankiaddon

IMPORTANT: This add-on doesn't use official API - only web-scraping.

What it's done (so far):
 - Creating notes from link to a word (word title, definition, gramar, IPA, sound, meanings, examples)
 - Fetching words from your wordlists - if you supply cookie for you account and wordlist IDs
 - Config settings management - save cookie, wordlist IDs

Please, follow these links for quick visual how-to guide.
https://ibb.co/94cq40m
https://ibb.co/WBzw37R

Your own cookie you can extract, for example, from web browser - Chrome - F12 and refresh page on cambridge

To do (contributors are welcome):
 - OpenID authorization - through Google/Facebook
 - Native authentification - through Cambridge account
 - Token management - keeping and renewal
 - Refine UI
