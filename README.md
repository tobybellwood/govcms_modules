# govcms_modules

drush vset update_check_disabled 1 -y

drush cache-clear drush
drush pm-refresh --check-disabled

drush pm-info --format=json > modules_info.json


drush pm-updatestatus --check-disabled --format=json > modules_up_20170530.json
