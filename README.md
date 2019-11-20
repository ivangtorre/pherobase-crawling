# Crawl Pherobase and RAW data

## Instructions to download
1. You need a registered user in Pherobase
2. Install the Chrome extension " cookies.txt" (https://chrome.google.com/webstore/detail/cookiestxt/njabckikapfpffapmjgojcnbfjonfjfg?hl=es) or an equivalent solution to get the login cookies.
3. Login to Pherobase and export cookies using the extension 
4. Use wget in bash to download database:

##  Species
**wget -np -r --load-cookies cookies.txt https://www.pherobase.com/database/species/species-A.php


## Use proper citation to original datase:
El-Sayed AM 2019. The Pherobase: Database of Pheromones and Semiochemicals. <https://www.pherobase.com>
