# Extremely Long Dog ΓÇö $XLONGDOG
The animated, indefinitely scrolling website for Extremely Long Dog.
Scroll to pan along one impossibly long dachshund while animated landscapes, strange characters, and easter eggs pass by. Includes an auto-pan mode, interactive distance ruler, mobile support, and respect for reduced-motion preferences.
## Run locally
Open index.html in a modern browser. This is a self-contained HTML page without npm dependencies, a build step, or API keys.
## Deployment
The site can be hosted as a static website at any host that serves index.html from the project root (Vercel framework preset Other, Cloudflare Pages, etc.). There is no configured production domain yet.
## Status and safety
This website is a prerelease for XLONGDOG. It is not yet associated with a verified live token contract. The site must not publish a buy link, fabricated contract address, or imply endorsement from the creator of the original dog photograph. Token launches and wallet activities are handled separately.
## Source of truth
Website-only publishing remote: https://github.com/How1337ItIs/xlongdog-website
The website is also part of the private full project at https://github.com/How1337ItIs/xlongdog under website/.
To update the website publishing remote from the full source checkout:
    git subtree split --prefix=website HEAD
    git push website <sha-returned-above>:refs/heads/main
Use the returned split SHA for <sha-returned-above>, not the source repository main commit SHA.