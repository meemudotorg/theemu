# theemu
meemu themes and localizations, for meemu.org!


to use, clone the repo then run

`rsync -av --files-from ./meemu-theme.txt . your/mastodon/dev/code/`

deploy the same way

`rsync -av --files-from ./meemu-theme.txt . yourname@yourServer:/your/mastodon/root`


you probably don't want to change your en.json or en.yml, so remove those from meemu-theme.txt 

if you use them, credit to catgoat@meemu.org would be cool! if you have tweaks or fixes, pull requests are welcome 💜. 

the vaporwave theme is appropriately glitchy, but the purple theme is in good shape (and the default on meemu.org!)
