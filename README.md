# drush-versions
Bash shell script to set up drush to use multiple versions

## Installation:
```
$ git clone https://github.com/uberhacker/drush-versions.git
$ cd drush-versions
$ chmod +x drush-versions
$ sudo mv drush-versions /usr/local/bin
$ drush-versions
$ source ~/.bashrc
```
*Currently, this script works only in Debian/Ubuntu/RedHat/CentOS and derivative Linux distros.*

## Usage:
```
$ drush-versions [up|update|-d #|--default #]
```

## Examples:

For Drupal 6 sites:
```
$ drush5
```

For stubborn Drupal 7 sites:
```
$ drush6
```

For well-behaved Drupal 7 sites:
```
$ drush7
```

For Drupal 8 sites:
```
$ drush8
```

For bleeding-edge Drupal 8 sites:
```
$ drush9
```

Default version:
```
$ drush
```

## Update:

Update drush to the latest versions:
```
$ drush-versions update
```

## Change:

Change the default to drush version 6:
```
$ drush-versions --default 6
$ source ~/.bashrc
```
