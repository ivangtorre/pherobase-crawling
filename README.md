# Crawl Pherobase dataset

Pherobase is the largest and most comprehensive open-access infochemical database. Pherobase contains elaborate and verified infochemical information, making it a very reliable and valuable resource widely used by the scientific community. This repository contains instructions to crawl the database just using linux comandas and apropiate cookies.

## Instructions to crawl Pherobase
1. You need a registered user in Pherobase
2. Install the Chrome extension " cookies.txt" (https://chrome.google.com/webstore/detail/get-cookiestxt/bgaddhkoddajcdgocldbbfleckgcbcid/related) or an equivalent solution to get the login cookies.
3. Login to Pherobase and export cookies using the extension 
4. Use wget in bash to download database:

##  Species
**wget -np -r --load-cookies cookies.txt https://www.pherobase.com/database/species/species-A.php


## Use proper citation to original datase:
El-Sayed AM 2019. The Pherobase: Database of Pheromones and Semiochemicals. <https://www.pherobase.com>
