# govcms_modules

drush vset update_check_disabled 1 -y

drush cache-clear drush

drush pm-refresh --check-disabled

drush pm-info --format=json > "C:\Users\tobyb\Documents\GitHub\govcms_modules\modules_info.json"

drush pm-updatestatus --check-disabled --format=json > "C:\Users\tobyb\Documents\GitHub\govcms_modules\modules_upgrade.json"

http://www.jsoneditoronline.org/?url=https%3A%2F%2Fgithub.com%2Ftobybellwood%2Fgovcms_modules%2Fblob%2Fmaster%2Fmodules_upgrade.json%3Fraw%3Dtrue


drush pm-updatestatus --check-disabled --format=csv > "C:\Users\tobyb\Documents\GitHub\govcms_modules\modules_upgrade.csv"


`="- [ ] Update ["&A1&"](https://www.drupal.org/project/"&A1&") to "&C1&" (from "&B1&")"`
