# Import report: Katie Teague

Imported from https://www.katieteague.com (Squarespace 7.1) on 2026-10-31 with `openspace import squarespace`.
Sources: page HTML and the sitemap, Squarespace's `?format=json` data (owner mode). 108 requests.

## Summary

- **26** pages, **4** collection items in 1 collection(s)
- **41** media files (6.5 MB) downloaded into `media/`
- **1** redirects so old addresses keep working
- **25** item(s) need your attention (below)

## Pages

| Squarespace | OpenSpace | Title | Sections | Blocks |
| --- | --- | --- | ---: | ---: |
| `/` | `/` | Home | 3 | 22 |
| `/in-the-making-films` | `/in-the-making-films` | In the Making Films | 6 | 26 |
| `/about` | `/about` | About | 4 | 7 |
| `/services` | `/services` | Services | 3 | 6 |
| `/home-copy` | `/home-copy` | Home | 4 | 12 |
| `/our-team` | `/our-team` | Our Team | 1 | 1 |
| `/resources` | `/resources` | Resources | 2 | 1 |
| `/wilderness-programs` | `/wilderness-programs` | Wilderness Programs | 2 | 2 |
| `/conflict-as-threshold` | `/conflict-as-threshold` | Conflict as Threshold | 2 | 5 |
| `/individual-thresholding` | `/individual-thresholding` | Individual Thresholding | 3 | 5 |
| `/wilderness-rites-of-passage` | `/wilderness-rites-of-passage` | Wilderness Rites of Passage | 2 | 2 |
| `/films` | `/films` | Films | 1 | 1 |
| `/read-more` | `/read-more` | Read More | 2 | 7 |
| `/wilderness-rites-of-passage-1` | `/wilderness-rites-of-passage-1` | Wilderness Rites of Passage (Copy) | 2 | 2 |
| `/home-1` | `/home-1` | Home (Copy) | 3 | 5 |
| `/individual-thresholding-1` | `/individual-thresholding-1` | Individual Thresholding (Copy) | 3 | 5 |
| `/wilderness-rites-of-passage-2` | `/wilderness-rites-of-passage-2` | Wilderness Rites of Passage (Copy) | 2 | 2 |
| `/wilderness-programs-1` | `/wilderness-programs-1` | Wilderness Programs (Copy) | 2 | 2 |
| `/giving-page-1-1` | `/giving-page-1-1` | Giving Page 1 | 7 | 14 |
| `/donate` | `/donate` | Donate | 1 | 3 |
| `/materials-for-learning` | `/materials-for-learning` | Materials for Learning | 2 | 1 |
| `/our-vision` | `/our-vision` | Our Vision | 1 | 2 |
| `/education-for-teachers` | `/education-for-teachers` | Education for Teachers | 2 | 1 |
| `/support-for-communities` | `/support-for-communities` | Support for Communities | 2 | 1 |
| `/in-the-making` | `/in-the-making` | In the Making Documentary | 2 | 10 |
| `/in-the-making-1` | `/in-the-making-1` | In the Making  (Copy) | 2 | 3 |

## Collections

| Squarespace | OpenSpace | Kind | Items | Drafts |
| --- | --- | --- | ---: | ---: |
| `/blog` | `/blog/` | blog | 4 | 0 |

## Design

The look was recreated with OpenSpace's own design system (Site Styles tokens, section color themes, layouts and section presets), not by copying Squarespace's template CSS or code.

- Brand color #253551 (Squarespace "accent" color).
- Fonts on Squarespace: freight-sans-pro / Open Sans → pairing "Merriweather & Open Sans" (Merriweather / Open Sans), same family for Open Sans. Licensed fonts can be uploaded in Site Styles → Fonts.
- Type scale on Squarespace: Heading 1 is 3.3× body text. Density "comfortable" from the section heights.
- Fonts on Squarespace kept as they are (Open Sans): free on Google Fonts, self-hosted with the site.
- freight-sans-pro (licensed from Adobe Fonts) can't be copied, so Mukta — the closest measured shape (x-height, width) among free fonts — stands in. With a web licence, upload the real font in Site Styles → Your fonts.
- Type scale on Squarespace (the live site, measured in a browser) kept: heading 2 45.4px/34.4px, body 17.7px/17.1px.
- Page background #ffffff on Squarespace → #fafafa (text contrast 15.6:1).

Design check: 8 error(s), 55 warning(s).

- **error** (/in-the-making-films): Two text blocks (button and button) overlap on desktop, so neither can be read properly.
- **error** (/in-the-making-films): Two text blocks (button and button) overlap on desktop, so neither can be read properly.
- **error** (/about): Two text blocks (text and text) overlap on desktop, so neither can be read properly.
- **error** (/services): Two text blocks (text and text) overlap on desktop, so neither can be read properly.
- **error** (/services): Two text blocks (text and text) overlap on desktop, so neither can be read properly.
- **error** (/services): Two text blocks (text and text) overlap on desktop, so neither can be read properly.
- **error** (/in-the-making): Two text blocks (text and text) overlap on desktop, so neither can be read properly.
- **error** (/in-the-making): Two text blocks (text and text) overlap on desktop, so neither can be read properly.
- warning (/in-the-making-films): This section is empty.
- warning (/in-the-making-films): This section has 3 primary buttons. One main action per screenful is clearer.
- warning (/in-the-making-films): This section has 3 primary buttons. One main action per screenful is clearer.
- warning (/about): This section is empty.
- … and 51 more: run Design check in Studio or `design_check` with Claude.

## Needs attention

### Custom code and embeds

- Code block moved into a sandboxed Embed block (scripts run isolated from the page). Check it still works; site-wide scripts belong in Settings → Advanced. _(/in-the-making, /in-the-making-1)_

### Forms and newsletter

- Newsletter signup recreated. Squarespace Email Campaigns / Mailchimp subscribers are not moved: export your list from Squarespace and import it in the Hub. _(/, /in-the-making-films)_

### Blocks that need a look

- Squarespace "donation" block has no direct OpenSpace equivalent; its text was kept as a text block. _(/giving-page-1-1, /donate)_

### Links

- Link to /events led to a page that wasn't imported; it now points at the home page. Point it at the right page. _(/home-copy)_

### Design

- A photo section's overlay was darkened from 40% to 80% so its text stays readable. _(/, /in-the-making-films)_
- A photo section's overlay was darkened from 15% to 80% so its text stays readable. _(/about, /individual-thresholding, /individual-thresholding-1)_
- A photo section's overlay was darkened from 15% to 65% so its text stays readable. _(/services)_
- A photo section's overlay was darkened from 17% to 45% so its text stays readable. _(/home-copy, /read-more, /home-1)_
- A photo section's overlay was darkened from 16% to 80% so its text stays readable. _(/home-copy, /individual-thresholding, /individual-thresholding-1)_
- A photo section's overlay was darkened from 29% to 60% so its text stays readable. _(/home-copy)_
- A photo section's overlay was darkened from 15% to 45% so its text stays readable. _(/conflict-as-threshold)_
- A photo section's overlay was darkened from 30% to 60% so its text stays readable. _(/wilderness-rites-of-passage, /wilderness-rites-of-passage-1, /wilderness-rites-of-passage-2)_
- A photo section's overlay was darkened from 15% to 60% so its text stays readable. _(/giving-page-1-1)_

### Other

- The page had no Heading 1; its first heading was made the Heading 1 (search engines and screen readers use it). _(/, /in-the-making-films, /about, /services, +12 more)_

## Redirects

Saved in `content/site.json` (`redirects`), published with the site:

| From | To |
| --- | --- |
| `/home` | `/` |

## Not moved by the importer

- Orders, customers, inventory, discounts, gift cards, shipping and tax settings (commerce stays in Squarespace until you switch).
- Newsletter subscribers, form submissions, member accounts and blog comments.
- Scheduling (Acuity), donations, digital-download files and anything behind a login.
- Squarespace analytics and SEO history (search engines follow the redirects).

## Next steps

1. `npm install`, then `npx openspace check` (it should report no errors) and `npx openspace dev` to look around.
2. Bring it to visual parity with Claude: in this folder run `claude`, then `/openspace:import-squarespace` (or ask Claude to compare each page with the original). It screenshots both sites at desktop and mobile and adjusts presets, Site Styles and sections — never raw HTML.
3. Fix the items under **Needs attention**, then publish (push to GitHub, or `publish` with Claude).
4. Move the domain only after the new site is live and checked:
   - add the custom domain in OpenSpace (`deploy.customDomain` in `openspace.json`, or the Hub);
   - at your DNS provider (Squarespace Domains or elsewhere), point the records at the new host as the domain guide says (GitHub Pages: `A`/`CNAME` records; Cloudflare: the Pages project's records);
   - keep the Squarespace subscription until the new site serves your domain over HTTPS and the redirects work; then cancel it (and transfer the domain away from Squarespace if you like).

## Phones

Made 13 phone-only adjustments so the site reads well on phones (shorten it on phones). The desktop design is unchanged.
