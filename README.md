# fehbuilder_kokr
Fan-based Korean Localization data for Fire Emblem Hereos and [Eskuero/fehbuilder](https://github.com/Eskuero/fehbuilder)

## About
- Use Github Action to get Localization data from [FEH WIKI](https://feh.wiki), and commit update data.
  - Using REST API https://feh.wiki/api/get_kor_locale_list.php
  - Requires Secret Key and File Type (Optional)

- Use Github Action Workflow Dispatch to trigger Action.
  - When the main branch of the private FEH raw data repository is committed, its GitHub Action sends a request to the Dispatch API.

## ETC..
- This translation follows the data used on [FEH WIKI](https://feh.wiki). Some proper nouns may differ from Nintendo’s official localization, which is intentional.
