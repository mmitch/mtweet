# THIS PROJECT HAS BEEN ARCHIVED because of the incompatible Twitter API v2 changes in 2023

## mtweet - Mitch's commandline tweeter with OAuth support

http://github.com/mmitch/mtweet
licensed under GNU GPL

Twitter switched off the old direct API and OAuth is needed now.  I have not
yet found a simple client with OAuth support, so I'm rolling my own...

Requirements:
  Crypt::SSLeay
  HTTP::Request::Common
  LWP::UserAgent
  Net::OAuth (at least 0.16)
(and Data::Dumper for debugging purposes, feel free to comment out)
