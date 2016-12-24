# kissdownloader
Download anime, cartoon, drama and movies from [KissAnime.to](http://kissanime.to), [KissCartoon.me](http://kisscartoon.me) and [KissAsian.com](http://kissasian.com).

# Dependencies
- Python with [cloudflare-scrape](https://github.com/Anorov/cloudflare-scrape) (Needed to bypass CloudFlare)

# Usage
./kissdownloader [--series/-s or --episode/-e] [link] [episodes-numbers-if-link-is-a-series] [-q/--quality quality] ...
You can provide as many links as is technically possible ;) On giving a series, you must follow with at least one episode number.

## UPDATE
The kiss-sites transformed gear and changed urls, video players, and stuff. So, I'll be updating to reflect those changes but now:
1. I'll be using python 3 with a few extra libraries (bs4, cfscrape) so install those (sudo pip3 install ...)
2. I'll write a script specefically for each site because they are becoming quite different in parsing techniques, and to make things a bit more modular.
