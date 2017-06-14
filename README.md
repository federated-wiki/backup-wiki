# backup-wiki

This small script allows you to download the [`export.json`](http://about.fed.wiki/view/curl-this-site/view/curl-a-page) of wikis for each domain in a text file provided.

## Backup whole sites

Consider a file `domains` containing

    glossary.asia.wiki.org
    fed.wiki.org
    hello.ward.bay.wiki.org
    about.fed.wiki
    pods.wiki.org

which is then passed to the script like

    ./backup-wiki < domains

If you invoke this command, a subfolder `sites` is created, where the backups are being placed.

## Backup whole sites with their pages individually

Consider the same `domains` file, but the command

    ./backup-wiki-pages < domains

which will create a subfolder `pages` within each domain is represented separately.

## License

MIT, see attached LICENSE file
