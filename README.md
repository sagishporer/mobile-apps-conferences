Conferences
===========

A community-curated list of conferences around the world for Android developers.


Adding a conference
-------------------

Send a pull-request which adds a file to the `_conferences/` directory
with a new file representing the conference. The file should be named
with the conference name, the year, and with an `.md` extension (for
example, `my-cool-conference-2016.md`).

The contents of the file should use the following template:
```
---
name: "Droidcon"
website: http://uk.droidcon.com/2015/
location: London, UK
status: Canceled/Postponed  # Optional, will show up in red if provided
online: true                # Optional, for online events.
live: true                  # Optional, for live event

date_start: 2015-10-29
date_end:   2015-10-30

cfp:  # Optional
  start: 2015-06-16
  end:   2015-07-21
  site: http://uk.droidcon.com/2015/lineup-2015/ # Optional, will default to website
---
```

*Note: Do not include the location of the conference in the name. The above conference is often referred to as "Droidcon London", but we will always render the location with the name so it is redundant.*

Running locally
---------------
![Build Jekyll Pages](https://github.com/sagishporer/mobile-apps-conferences/workflows/Build%20Jekyll%20Pages/badge.svg)

```
bundle install --path vendor/bundle
bundle exec jekyll serve
```

Once running the site can be opened at http://localhost:4000.


License
-------

All content is [CC0][1].


 [1]: https://creativecommons.org/publicdomain/zero/1.0/
