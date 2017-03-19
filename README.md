# BSidesCBR 2017 CTF docker compose files

This repo contains all the docker-compose files that spin up the BSidesCBR 2017 CTF challenges. Each of the challenges listed here was available as part of the CTF, though unfortunately some challenges weren't able to be dockerised and released.

## Running challenges

Each subfolder maps to a challenge. In order to run that particular challenge, simply:

1. `cd` to the folder that contains the challenge you wish to attempt.
1. run `docker-compose up`
1. Read the `README.md` inside the folder for details on where to find the challenge.

At this time, we don't have the scoreboard available, but hopefully that won't stop you from owning it!

## HTTPS Warnings

Each of the web challenges has a certificate for `web.shell.dance` that was generated via Lets Encrypt. Expect to see SSL errors in your browser, but just ignore them.

Should I be pushing images with the SSL certs in them? Probably not, but they'll expire soon anyway.

## FAQ

> Can I produce a write-up for a challenge, or live-stream the process of completing it?

Yes, please do. Let us know when you publish/stream by hitting us up on [Twitter](https://twitter.com/bsidescbr).

> Can I reuse your challenge for my own CTF?

You'll have to contact us to discuss this as we'd like to know the purpose of the CTF.
