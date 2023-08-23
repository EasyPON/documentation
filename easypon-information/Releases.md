# Changelog

## v2.3.10 - 2023-08-07

---
## v2.3.9 - 2023-07-24

---
## v2.3.8 - 2023-07-13

---
## v2.3.7 - 2023-07-12

---
## v2.3.6 - 2023-07-04

---
## v2.3.5 - 2023-06-21

---
## v2.3.4 - 2023-06-20

---
## v2.3.3 - 2023-06-20

---
## v2.3.2 - 2023-06-16

---
## v2.3.1 - 2023-06-13
#### Changes:
* fix group creation when not exists (a221259)
* remove not exists task (cf7c15e)
* fix log error on failed request (c9be74e)
* fix request args (ad5d1f2)
* remove redundant serializer (c16c12b)
* created filters and split serializers (69f0331)
* add pagination to building map (214444a)
* Resolve EP-000 "/return all buildings on map" (70909ef)
* add onu magic and olt type in external onu response (eda168d)
* send domain name in header on check license requests (d67d098)
* Resolve EP-000 "/add onu list to building" (90f63d2)
* Resolve EP-1057 "/userside integration settings" (a8250c8)
* Fix filtering in map building (7751d9e)
* Exclude from map building empty buildings (9ca4343)
* Add celery integration to sentry sdk (a9cf1e3)
* Change crontab of userside sync (507c2a2)
* Resolve EP-1059 "/add permission to config endpoint" (03db858)
* fix retrieving qinq port (97ac61d)
* Save and manage filters the user uses to filter some data in different modules. (47a6c5d)
* Change format of geopoint in map_building (2077d63)
* Resolve EP-1025 "/transfer onu location and notice after dublicate deletion" (6df012e)
* Fix switch urls (46d71ca)
* Add switch topology graph (9d9fc15)
* added connection type to external onu api response (c108634)
* added connection type to external onu api response (73c1a6a)
* Add type of userside synchronization (a642b6d)
* change invalid login description message (3747b18)
* logout user after deactivating (4eca60d)
---
## v2.3.0 - 2023-05-18
#### Changes:
* Rename some settings (68bbc2e)
* Fix configuration with live settings (07475ea)
* Done with config in web (f9c95fc)
* Done with adding building to onu (37b964a)
* Add views/serializers for buildings and clients (af2391f)
* Done with buildings and clients (b768c8e)
* Add migration (4a1dede)
* Add integration for userside, now you can import geolocation onu (a4e6f7e)
* Update disprofile module (b882b4b)
* Add near onu geolocation (920ac3c)
* Fix registering onu on deleted onu. (d0642c3)
* Add detail task information about initialise OLT. (34f1690)
* Fix onu config type creating on Huawei olt. (607e04d)
* Remove damaged reports after unsuccessful file downloading. (085058a)
* Fix onu task status changes. (b5c685d)
* Return descriptive message when try to reboot onu and get the connection error. (78c153b)
* Add release to sentry tracking (250da80)
* Fix clients mac on huawei (9c851d5)
* Add find by hexed serial number onu (25aa30b)
* Fix onu update tasks (e6f7c46)
* Skipped slots without qinq (bb6b87d)
* Fix onu update tasks (d787667)
* Fix update onu ethernet vlans tasks. (c85d573)
* Formatted custom action result response. (11990b6)
* Added ordering to for onu port migration and file report tables. (2a19963)
* Clear not existing files and delete them from the filesystem. (f7f0e37)
* Improved onu filtering in logs. (2420155)
* Log can handle the entire onu history. After onu deletion, it does not remove from db. (85dcc5a)
* Add version checker for huawei (56a90d0)
* Change commands for show config in huawei (a3d353a)
* Fix reboot on huawei (4a368e4)
* Fix full update onu on huawei (cab7422)
* Add support of Huawei MA5608T. (9540005)
* make google keys not required (022017f)
* It was improved receiving latest release information. Now get the version that matches client requirements. (267121d)
* Show notification for admin users if a new version of EeasyPON was released. (a1e4374)
---
## v2.2.2 - 2023-05-01
#### Changes:
* Created permission for custom onu action. (4a8fded)
---
## v2.2.1 - 2023-04-27
#### Changes:
* Fix update onu on ZTE GPON (0b33d05)
---
## v2.2.0 - 2023-04-27
#### Changes:
* Release v2.1.1 (982ac49)
* Update .gitlab-ci.yml file (a2e4a18)
* Fix problem with compiled version (cb893d1)
---
## v2.1.1 - 2023-04-27
#### Changes:
* Update .gitlab-ci.yml file (a2e4a18)
* Fix problem with compiled version (cb893d1)
---
## v2.1.0 - 2023-04-27
#### Changes:
* Fix install issue with DB migration. (03db83c)
* Fix problem with infinity get all onu on some ZTE (6c6e247)
* Fix problem on c320 with "No such instance" on get onu status (60459eb)
* Changed method for retrieving olt timezone to improve time calculation. (576fef3)
* Fixed error when trying to update periodic tasks. (5b5866e)
* Fixed error on retrieving shel information on ZTE C220 olts. (fc40d8a)
* Increased description information about config onu log entry. (62134b9)
* Fix migrate onu on another port (19bbfe2)
* Disable prefetch related in olt viewset (b243cad)
* Show additional info about the object in the main user log table. (9091164)
* Remove logging every view action on the switch and switch port. (7bb4929)
* New macros for retrieving onu port number (8bad61b)
* A more informative description of the Excel exported file. (f348f53)
* Added to background task that scans all "onus" on the olt more detailed information about each record.<br> Implemented a counter to keep track of the total number of ONUs found when scanning them on OLT. (3792717)
* Updated install instructions (25e7fda)
* Retrieve Google client id for oauth2 authentication. (79ebeb7)
* Add redis to ci/cd (dffe609)
* Add redis to ci/cd (103f6e5)
* Add redis to ci/cd (1b444e8)
* Add redis to ci/cd (f744867)
* Done with export documentation to gitbook (d9107f0)
* Done with export documentation to gitbook (6800d06)
* Done with export documentation to gitbook (e1af4cc)
* Done with export documentation to gitbook (d5d41ef)
* Done with export documentation to gitbook (e50a8e1)
* Done with export documentation to gitbook (ff09f6d)
* Done with export documentation to gitbook (a31d634)
* Done with export documentation to gitbook (9ba1d43)
* Done with export documentation to gitbook (830ffcd)
* Add override xclsx name for olt classes (3317a2c)
* Changed location map route. (e8e78cb)
* Fixed onu location retrieving (63cef46)
* Add cache-control to allow headers (db2c1ed)
* Test clear cache endpoint (1dfa70d)
* Removed the internal periodic tasks from the request result, so now users will only see the main tasks associated with them. (8dedbd9)
* Added ability for users to save and retrieve filter parameters. (be73aef)
* Added installation instructions for EasyPON. (496bf5e)
* Improve ONU logging to include information on retrieval and applying configuration results: success and failure. (bcefcc4)
* Resolve EP-899 "/merge migrations" (7142e3b)
* Implement access control for dedicated source with new 'Can view onu duplicates' permission (f5ae1d0)
* add celery-expoter binary adn systemd service (49e2c1a)
* Simplify the OLT registration process with the minimal required info: IP, login, pass, and olt type (30c8973)
* Resolve EP-907 "/add offline time to duplicates onus on detail onu edpoint" (eb4648b)
* Implemented new feature for detail page that allows users to view a list of duplicated ONUs, if they exist. (6f27c17)
* Streamlined project language support by keeping only English descriptions. (e81eaa2)
* Implemented new feature: Ordering filter now available for all tables. (e665ddd)
* In the onu firmware variety list, all rows are not grouped by olt. (6319bbb)
* Resolve EP-847 "/change start time for tasks" (4ca46db)
* edit all permissions name (250d4db)
---
## v2.0.3 - 2023-04-03

---
## v2.0.2 - 2023-03-29
#### Changes:
* Update release-it package (da53d73)
* Add artifacts (7b8e461)
---
## v2.0.1 - 2023-03-29
#### Changes:
* Done with cicd (e6735b6)
* Fix module (764a6ea)
* remove compressed data (f41cb55)
* fix outdated checking (750abc7)
* add latest ep release endpoint (f3eab1f)
* decompress data in license check request (5af9d9b)
* test
---
## v2.0.0 - 2023-03-29

---
## v1.0.0 - 2023-03-28
