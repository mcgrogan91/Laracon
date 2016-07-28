# Ben Ramsey - Long Live HTTP/2

https://benramsey.com/talks/2016/07/laracon-http2/

HTTPbis - tasked with revising how HTTP had been used

### Reasons to remove

Lots of ambiguity in RFC 2616 HTTP/1.1
Web got bigger. APIs, etc

### HTTP/2

Better at gathering assets.  Connection limits aren't necessary anymore.
Single connection, interleaved packets
Google, Facebook, Twitter, etc are using it

#### Lack of connection limits

No need for image sprites
CSS/JS can be in multiple files

### Server push

Pushes data on initial request for commonly combined assets
PHP can invoke server push
Add 'Link' headers for assets if it's a HTTP request.
