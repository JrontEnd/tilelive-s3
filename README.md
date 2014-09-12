tilelive-s3
-----------
Extends `node-tilejson` for using S3 as a tilejson backend.

[![Build Status](https://secure.travis-ci.org/mapbox/tilelive-s3.png)](http://travis-ci.org/mapbox/tilelive-s3)

 - pkg-config
 - libpng
 - node >= 0.6.13 && < 0.11.0

Tests
=====

Configure by setting the following environment variables.

```
AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_SESSION_TOKEN (optional)
```

Run `npm test`.
