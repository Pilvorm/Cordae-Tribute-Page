# Cordae Tribute Page
This is a tribute page about one of my favorite rappers, Cordae.

## Backstory
After completing the freeCodeCamp's [Responsive Web Design certification](https://www.freecodecamp.org/learn/responsive-web-design/), I decided to remake the required projects again - focusing on improving the design and aesthetics of the page while learning more effective approaches on building the layout of the page. The first required project was making a tribute page, hence I remade it about a young and talented rapper, [Cordae Amari Dunston](https://open.spotify.com/artist/0huGjMyP507tBCARyzSkrv).

## Development
This project was made with:
- HTML
- CSS

With contents taken from:
- [Wikipedia](https://en.wikipedia.org/wiki/Cordae)
- [Spotify](https://open.spotify.com/artist/0huGjMyP507tBCARyzSkrv)
- [Genius](https://genius.com/artists/Cordae)

Challenges:
- Initially, I made the 'About' section using grid and then flex, thinking that both really helps when positioning elements, but then I realized that it created a large blank space on the image's side when resizing the screen to smaller sizes. After trying different approaches, simply using **float** solves the problem - allowing the description to wrap around the image and leaving way less blank space and providing more comfort when reading.
- I wanted to make the albums' title appear when hovering over the album covers. But hovering over the title itself caused the text to flicker. After a short search I came across [this](https://stackoverflow.com/questions/28840644/text-flickers-on-hover-css) and followed one person's answer to put **pointer-events:none;** on the hover state and it solved the problem.

## Go see the page!
See the page [here](https://codepen.io/danielemerald/pen/dyJQrXV).
