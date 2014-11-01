#infos

auth-name       : substack
tag             : browser, crypto, web

advance costs   : N
need room       : Y
Location        : Oakland (but I will be in Paris)
Can host ppl    : N


# REBOOT THE WEB

Browsers have been quietly and methodically adding native crypto primitives,
but one gaping attack vector remains: every time you load a page, you load code
directly from the server.

The person running that server can be coerced, hacked, or forced by sealed court
order to change that javascript payload at any time. What we need to make web
crypto viable is a bootloader for the web. Luckily, this is now possible by
abusing the new application cache API to brick a website except for a
whitelisted update feed. Now the user can finally be in control of which updates
they get from web pages, making browser crypto much more secure while preserving
all the usability benefits of the web.
