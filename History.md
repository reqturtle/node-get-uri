
0.1.3 / 2014-04-03
==================

  * package: old npm compatible semver

0.1.2 / 2014-04-03
==================

  * package: loosen semver required versions
  * data: just always use the "readable-stream" module

0.1.1 / 2014-02-05
==================

  * http: initial shot at "cached redirects" logic
  * package: pin "ftpd" version to v0.2.4 (for tests)
  * test: refactor tests into their own files
  * file: remove unused `path` require
  * test: fix "file:" URI tests on Windows
  * file: add better Windows support for file:// URIs
  * http: add the Cache-Control and Expires respecting logic
  * http: clean up logic a bit

0.1.0 / 2014-01-12
==================

  * test: add initial "http:" protocol tests
  * package: add "st" as a dev dependency
  * http: don't pass the `res` when there's a response error
  * test: add initial "https:" protocol tests
  * http: initial 304 Not Modified support
  * index: use debug()
  * http: add support for 3xx redirect response codes
  * http, https: initial "http:" and "https:" implementation
  * ftp: fix debug() call
  * package: update "description"
  * test: remove PASV port range from FTP server
  * test: add more "ftp:" protocol tests
  * test: add more "data:" protocol tests
  * test: more "file:" protocol tests
  * test: set `logLevel` to -1 on the FTP server
  * file: close the `fd` upon an error before creating the ReadStream
  * data: use "readable-stream" for node v0.8.x support
  * ftp: add debug() call for the entry logging
  * test: use "ftpd" for the "ftp:" protocol test
  * file: refactor for optimizations and to do proper NotModifiedErrors
  * add .travis.yml file
  * file: decodeURIComponent() on the pathname before normalizing
  * file: beginnings of refactor
  * file: initial async "file:" protocol
  * ftp: tweak comment
  * http, https: prep
  * test: add initial "file:" protocol test
  * data: fix debug() function name
  * notfound: fix jsdoc description
  * data: add NotModifierError() handling logic
  * ftp: handle the "file not found" scenario
  * notfound: add NotFoundError class
  * ftp: better ftp impl, not with NotModified support
  * notmodified: add NotModifiedError() class
  * ftp: fix `onfile()` error handling
  * file: beginnings of "file:" protocol impl
  * test: add initial "ftp" test
  * test: use "stream-to-array" for tests
  * ftp: comment out console.error() call
  * ftp: update to the async interface
  * package: update "data-uri-to-buffer" to v0.0.3
  * test: add initial tests
  * turn into an async interface
  * Add Readme.md
  * initial commit
