# Design Notes

## Page Order

There is currently no way to order pages. They'll be sorted according to whatever the filesystem decides. 
So, it may behoove us to include some configuration of page order. Perhaps a simple json file that is essentially a manifest.
It describes the pages and organization of the book. And we can read our nav from that.

### What if it's out of sync?

the proverbial question. What if it is? we can show blank pages if there's no content yet.
If something is on the file system, but doesn't appear in the json, we can ignore it. 

### Things to work on

[] define a font face for ibm plex. it doesn't seem to work on mobile. 
[] 