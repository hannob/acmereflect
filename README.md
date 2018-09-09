# acmereflect
quick and dirty check for ACME API endpoints that reflect content

ACME endpoints that reflect the filename can lead to XSS, see
[this blog post by Detectify](https://labs.detectify.com/2018/09/04/xss-using-quirky-implementations-of-acme-http-01/).

This is just a quick and dirty bash/curl based check. I also added a check for this
issue to my tool [snallygaster](https://github.com/hannob/snallygaster).

Written by [Hanno Böck](https://hboeck.de).
