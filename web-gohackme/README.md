* This web-based challenge was worth `450` points.
* Run `docker-compose up` and then browse to [https://web.shell.dance:8443/](https://web.shell.dance:8443/).

## NOTE!

Building a challenge like this is hard, and there are issues that we haven't been able to control. It won't take you long to realise that you have to do something with XSS in this challenge. Unfortuanately, `casperjs` isn't honouring the `script-src` CSP header, which changes how this challenge works.

If you're hosting scripts on your own server/machine/etc then you're bypassing an important part of this challenge (ie. you're doing it wrong and losing out on one of the fun parts). Please don't take this approach, look for another way!
