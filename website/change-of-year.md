# On change of year

## Website admin tasks to change the site

In [SPA website](https://github.com/spaconference/spa-website/):
- Change current year in `_config.yml`.
- And in `.travis.yml`
- Remove contents of `\_posts` and hide the `news` page in `_config.yml`.
- Remove all images relating to this year, e.g. keynote speaker's photos
- Add current year to previous conferences page
- Put any dates that we know in and set all others to TBC
- Reset the site navigation menu so relevant ones are shown (at start, probably just location, organisers, previous conferences and code of conduct) and add the pages now not published to the excludes list
- Comment out the book now button
- Reset sponsorship page
- Change year on index page! ("Now in its Nth year...")
- Merge PR and check it all looks OK in situ at the new location

[Example change of year PR](https://github.com/spaconference/spa-website/pull/62) (doesn't include the [Nth year change](https://github.com/spaconference/spa-website/pull/63)).


