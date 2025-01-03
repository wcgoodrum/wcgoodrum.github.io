Personal hub of my socials and an exercise in web design

Panels to design:
- spotify
- strava
- letterboxd
- goodreads
- steam
- vsco
- nytimes wordle and mini

The general idea is to do this using async webscrape requests to build out the panels myself instead of using the iframes like I have now. This way i can practice and show off my css skills and have more design flexibility. However, it may be difficult to scrape certain sites (*ahem* spotify).

It would be cool to implement a cache for this stuff so that it doesn't directly request everytime I load the page, so I need to research that.

Having my nytimes (wordle and mini) will require me to build out a seperate tool entirely to track that stuff.

---

research:
steam, strava, and goodreads are very easy to scrape, all of the images and text are given in plain html request
letterboxd gives all text in html scrape but images require loading via some javascript
vsco loads no real data
