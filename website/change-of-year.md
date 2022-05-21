# On change of year

_Note: these instructions apply for years up to and including 2020.  In 2021, for various reasons, a Wix site was used instead.  The HTML from the Wix site was exported and saved to the "2021" directory in the [previous-spa-sites](https://github.com/spaconference/previous-spa-sites) repo.  For 2022, as the conference was simplified to a one day "MiniSPA" event, a simple hand-coded HTML site was used, which is in the "2022" directory in the same repo.  For 2023, a decision will need to be made whether to go back to using this full PHP based site with the build pipeline or not._

## Website admin tasks

In [SPA website](https://github.com/spaconference/spa-website/):
- Change current year in `_config.yml`.
- And in `.travis.yml`
- Remove contents of `\_posts` and hide the `news` page in `_config.yml`.
- Remove all images relating to this year, e.g. keynote speaker's photos
- Add current year to previous conferences page
- Put any dates that we know in and set all others to TBC
- Reset the site navigation menu so relevant ones are shown (at start, probably just location, organisers, previous conferences and code of conduct) and add the pages now not published to the excludes list
- Comment out the book now button (in [the header](/_includes/header.html)).
- Make changes to index page (e.g. change year) and other changes to content (e.g. if sponsorship package has been agreed).
- Merge PR and check it all looks OK in situ at the new location

[Example change of year PR](https://github.com/spaconference/spa-website/pull/62) (doesn't include the [Nth year change](https://github.com/spaconference/spa-website/pull/63)).


## Conference organisers tasks

Before the website admin can redirect https://spaconference.org to this year's site, the conference organisers need to have updated at least:

- sponsorship page
- conference dates
- organisers page

and ideally the lead a session page and dates.

The website itself is [here](https://github.com/spaconference/spa-website).

### Update Twitter and LinkedIn

The Twitter and LinkedIn accounts are run by the conference chairs.

When the site is live update the [@spaconference](https://twitter.com/spaconference) Twitter profile. Update the profile image to reflect the current year, and the header image to reflect the conference dates.  Then update the [LinkedIn organisation](https://www.linkedin.com/company/19143029/admin/) with the same image.

The Photoshop PSD files for the images are in [assets/twitter](assets/twitter). Export the images as PNGs. Please ask the organisers for the twitter account password.

See [month-by-month](/month-by-month.md) for more detail of what needs to be done at each stage.
