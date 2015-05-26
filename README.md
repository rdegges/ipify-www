# ipify-www

The public facing website for [ipify][]: *A Simple IP Address API*.


## Meta

- Author: Randall Degges
- Email: r@rdegges.com
- Site: http://www.rdegges.com
- Status: maintained, active


## Purpose

[ipify][] is the best IP address lookup service on the internet.  It's fast,
simple, scalable, open source, and well-funded (*by me!*).

In short: if you need a way to pragmatically get your public IP address, ipify
is the best possible choice!

This repository holds the source code for the ipify website.  This is a static
website deployed into an Amazon S3 bucket (*for speed, simplicity, and cost*).


## Testing

To test this website locally, I like using `python`:

```console
$ git clone https://github.com/rdegges/ipify-www.git
$ cd ipify-www
$ python -m SimpleHTTPServer
```

The above commands will clone the repository down locally, then start a local
web server at [http://localhost:8000][]  Once this web server is started, you
can visit it in your browser to test things out =)


## Contributing

This project is only possible due to the amazing contributors who work on it!

If you'd like to improve this website, please send me a pull request!  I'm
happy to review and merge pull requests.

The standard contribution workflow should look something like this:

- Fork this project on Github.
- Make some changes in the master branch (*this project is simple, so no need to
  complicate things*).
- Send a pull request when ready.

Also, if you're making visual changes, please include a screenshot of the
changes in your pull request text somewhere -- this makes it easier for me to
visually inspect CSS changes / etc.


  [ipify]: http://www.ipify.org/ "ipify - A Simple IP Address API"
  [http://localhost:8000]: http://localhost:8000 "Localhost"
