# backup-wiki

This small script allows you to download the [`export.json`](http://about.fed.wiki/view/curl-this-site/view/curl-a-page) of wikis for each domain in a text file provided.
Consider a file `domains` containing

    glossary.asia.wiki.org
    fed.wiki.org
    hello.ward.bay.wiki.org
    about.fed.wiki
    pods.wiki.org

which is then passed to the script like

    ./backup-wiki < domains

## License

MIT, see attached LICENSE file
