# Juno Homebrew Tap

This repo contains a [Homebrew tap](https://docs.brew.sh/Taps) with the following forumlae:

* `curl-opensslonly` - A fork of the curl formula without secure-transport to
  allow pycurl versions prior to 7.43.0.6 to work (celery[sqs] requires
  7.43.0.5)

## How do I install these formulae?
`brew install junohq/tap/<formula>`

Or `brew tap junohq/tap` and then `brew install <formula>`.

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
