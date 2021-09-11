# Sail Deploy

This is a GitHub Action. If you're looking for Sail, [head over here](https://github.com/kovshenin/sail).

Usage:

```
- uses: kovshenin/sail-deploy@v1
  with:
	passphrase: ${{ secrets.SAIL_PASSPHRASE }}
	encrypted_filename: '.sail.tar.gz.gpg'
```
