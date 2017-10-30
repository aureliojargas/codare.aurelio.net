# codare.aurelio.net

Sources for the http://codare.aurelio.net website, hosted in GitHub Pages.

## Context

In Oct 2017, the **codare.net** website (WordPress) was retired and archived into plain HTML files. Also, its URL changed to a subdomain to avoid domain registration costs.


## Update all pages in batch

Just use the [replace script](https://github.com/aureliojargas/aurelio.net/blob/master/_scripts/replace) to change all the HTML files locally.

```bash
htmls='*.html */*.html */*/*.html */*/*/*/*.html'
replace -f old-text -t new-text -i $htmls
```
