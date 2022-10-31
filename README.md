# urlshortener for nodejs

A simple npm package to shorten your long urls to short url for nodejs
Fetch function used in this library is currently in experiemental.so you have to run in experimental mode to make the library works fine.

#Installation

`npm i urlshortit`

`yarn add urlshortit`

`pnpm add urlshortit`

```
#Usage 1


const url = require("urlshortit");
async function shortenUrl() {
        const shortenedUrl = await url("https://www.fb.com");
    }

    shortenUrl()



#Usage 2

const url = require("urlshortit");
const shortenedUrl = shortener("https://www.fb.com").then((res) => {
       const shortenedUrl = res;
    });
```

#How to run

```
node --experimental-fetch packagename.js
```
