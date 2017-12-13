# tinywebdb
a http-client for tinywebdb api test

example:

StoreaValue

> http-client tinydb.ml 80 POST /api/storeavalue/ “tag=presentationtimer&value=Just a TEST from C”

GetValue

> http-client tinydb.ml 80 GET /api/getvalue/ “tag=presentationtimer”
