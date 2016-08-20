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

```
$ drush5
```
Use for Drupal 6 sites

```
$ drush6
```
Use for stubborn Drupal 7 sites

```
$ drush7
```
Use for well-behaved Drupal 7 sites

```
$ drush8
```
Use for Drupal 8 sites

```
$ drush
```
Latest dev-master version

## Update:

```
$ drush-versions update
```
Update drush to the latest versions
