# drush-versions
Bash shell script to set up drush to use multiple versions

## Installation:
```
$ git clone https://github.com/uberhacker/drush-versions.git
$ cd drush-versions
$ chmod +x drush-versions
$ sudo mv drush-versions /usr/local/bin
$ drush-versions
```
*Currently, this script works only in Debian/Ubuntu/RedHat/CentOS and derivative Linux distros.*

## Usage:

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

Latest dev-master version:
```
$ drush
```

## Update:

Update drush to the latest versions:
```
$ drush-versions update
```
