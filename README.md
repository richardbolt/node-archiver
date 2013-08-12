Node Archiver
=============

Super simple Node utility to create a gzipped tar archive.

Install
-------

	npm install --save node-archiver

Usage
-----

```javascript
  var archiver = require('node-archiver');
  archiver(__dirname, './dist/my-archive.tar.gz');
```

You can pass an optional callback to archiver:
	
```javascript
archiver(__dirname, './dist/my-archive.tar.gz', function(err) {
  if (err) { throw err; }
  // Done!
});
```
