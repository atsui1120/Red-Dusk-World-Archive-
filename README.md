# Red Dusk · World Archive

Public website distribution for the Red Dusk World Archive.

Website: https://atsui1120.github.io/

`site/` contains the reviewed static website. This repository does not contain the development workspace or its Git history.

Publication is manual. A push does not deploy the website. In Actions, run **Publish World Archive** from `main` and explicitly select the publish checkbox after reviewing the new site. The workflow verifies `site.sha256` and deploys only `site/` through GitHub Pages.

For updates, replace `site/` with the freshly built and verified output, regenerate `site.sha256`, review the changes, and commit before manually publishing. Keep GitHub Pages configured to use GitHub Actions.

## Asset rights and non-commercial use

This is an unofficial fan archive for non-commercial reference, discussion, and entertainment. It is independently maintained and is not an official website of, or endorsed by, the Red Dusk development team, Paradox Interactive, or other rights holders.

The mod artwork, portraits, interface assets, game text, and included audio are drawn from [Red Dusk](https://steamcommunity.com/sharedfiles/filedetails/?id=3314680066). Copyright, trademarks, and other rights remain with their respective creators and rights holders. The site maintainer does not claim ownership of these materials. Their inclusion in the mod does not mean that the mod team owns all third-party rights.

The archive's editing and website implementation do not change those rights or grant visitors permission to reuse third-party materials. This notice describes the site's purpose and attribution; it does not itself establish permission to use the materials. Any license separately applied to this site's original code does not cover third-party assets unless explicitly stated by the relevant rights holder.

## Report a rights concern

Anyone can report a possible copyright or attribution issue through [GitHub Issues](https://github.com/atsui1120/atsui1120.github.io/issues). Please identify the relevant page or file and describe the concern. On receiving a report of possible infringement, the maintainer will immediately remove the reported material from the public website and current public distribution while reviewing the concern.
