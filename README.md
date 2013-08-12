Node Archiver
=============

Super simple Node utility to create a gzipped tar archive.

Install
-------

	npm install --save node-archiver

Usage
-----

	var archiver = require('node-archiver');
	archiver(__dirname, './dist/my-archive.tar.gz');