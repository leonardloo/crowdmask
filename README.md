crowdmask
=========

This is a crowdsourced map of the stocks + prices of N95 masks and air purifiers in Singapore, built in the early days of the haze. We're taking advantage of the good weather now to build this site up, so it'll be ready by the time the haze hits!

[Live site](http://crowdmask.eidus.org) 

### This is a mockup which shows what we intend to build:

![mockup](https://raw.github.com/eidus/crowdhaze/master/n95_finder.png)


### Current architecture

Currently, this does not have a database. Instead, it grabs data from a mirror of the google spreadsheet that has been going around (published as an ATOM feed, consumed as a JSON) and puts it on a map. Not ideal, but allows non-technical users to maintain the database.

### Known bugs/faults

This is a very rough first prototype, so many things can be done!

1. Does not work on mobile (we need help!)
2. We should_have a way to let users indicate that a place has run out of masks
3. We should_have a way to visually show prices of masks on the site

### Hacked together with love:

Ian Wern, Kenneth Tiong, Leonard Loo, [Daniel Ong](http://www.eidus.org)


