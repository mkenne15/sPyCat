# sPyCat
This repo contains the json files, light curves, and finders for the pulsars in sPyCat.

Each spider has a JSON file within the JSON folder, and a corresponding folder within the spiders directory.

## Editing known spiders
If you wish to propose any changes to the JSON files, or want to update finders/light curves for any spider, please create a new branch,
edit the corresponding information, and then submit a pull request with the updated information. This will then be reviewed
by our team to ensure the format of the updates is correct, and to ensure references for any targets are correct.

## Adding a new spiders
If you wish to add a new spider to sPyCat, please create a new branch, create a JSON file which follows the format for other spiders, create a new folder
within spiders with the new objects name, and add any light curves to it. Finders are also welcome, but not required as these can be
created on the fly when recompiling the website.
