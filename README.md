# BSidesCBR 2017 CTF docker compose files

This repo contains all the docker-compose files that spin up the BSidesCBR 2017 CTF challenges. Each of the challenges listed here was available as part of the CTF, though unfortunately some challenges weren't able to be dockerised and released.

## Running challenges

### HTTPS stuff

Each of the web challenges has a certificate for `web.shell.dance` that was generated via Lets Encrypt. Expect to see SSL errors in your browser, unless you decide to add an entry to your hosts file that points `web.shell.dance` at `127.0.0.1` (this is recommended). If you don't, the rest of the instructions won't make sense! Skipping this step means using `localhost` instead of `web.shell.dance` wherever you see it.

Should I be pushing images with the SSL certs in them? Probably not, but they'll expire soon anyway.

### Docker container execution

Each subfolder maps to a challenge. In order to run that particular challenge, simply:

1. `cd` to the folder that contains the challenge you wish to attempt.
1. run `docker-compose up`
1. Read the `README.md` inside the folder for details on where to find the challenge.

At this time, we don't have the scoreboard available, but hopefully that won't stop you from owning it!

## FAQ

> Wait.. can't I just attach to the running container and cheat?

Yes, you can. Don't do that. It's lame, it's against the spirit of this release, and you won't learn as much. Do it the proper way!

> Can I produce a write-up for a challenge, or live-stream the process of completing it?

Yes, please do. Let us know when you publish/stream by hitting us up on [Twitter](https://twitter.com/bsidescbr).

> Can I reuse your challenge for my own CTF?

You'll have to contact us to discuss this as we'd like to know the purpose of the CTF.
