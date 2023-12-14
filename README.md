1. Added a single argument called `pagesToScrape` to our main `run()` function. Use this to limit how many pages script will scrape.
2. There is one more new variable named `currentPage` which represents the number of the page of results. It’s set to `1` initially. I also wrapped evaluate() function in a while loop, so that it keeps running as long as `currentPage` is less than or equal to `pagesToScrape`.
3. Added the block for moving to a new page and waiting for the page to load before restarting the while `loop`.
