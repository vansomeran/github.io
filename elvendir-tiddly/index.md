#!/bin/sh

# build a single File TW in elvendir-tiddly/output/index.html

tiddlywiki.js elvendir-tiddly --build index
mv elvendir-tiddly/output/index.html ..
