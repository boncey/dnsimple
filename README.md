dnsimple
========

Random tools for messing around with DNSimple.

## Getting started

### Authentication

Put your credentials in `~/.dnsimple

    username: your_username
    api_token: your_api_token

### Gems

    gem install dnsimple-ruby

## dns-cat

    ./dns-cat

Outputs all your DNSimple domain records to stdout.

## dns-clear

    ./dns-clear <domain>

Outputs that domain's DNSimple domain records to stdout then prompts asking if you wish to clear that info.
If you reply 'Y' then it will clear the `A`, `CNAME` and `MX` records.
