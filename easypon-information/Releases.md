# Changelog

## v2.3.20 - 2024-03-13

---
## v2.3.19 - 2024-02-16

---
## v2.3.18 - 2024-02-01

---
## v2.3.17 - 2024-01-16

---
## v2.3.16 - 2023-12-12
#### Changes:
* Fixed error during switch initialisation
* Allowed changing username and email from the user profile page
* Added users avatars in general list of users and to the profile
* Added support for the OLTs: BDCOM P3600-16E, BDCOM GP3600-16B, GP3608B
* Added support for the new OLT: BDCOM GP3600-08B. (fbb0933b)
* Optimized time for display of detailed info about OLT on the OLT page
* Cleared ONU ethernet ports and client macs when ONU was deleted.
* Added user avatars to event log detailed page
* Added the new 404 page look
* Created redirection from detailed OLT page to periodic tasks table for this OLT
* Blog to the Website! We started our blog and very exited about it!
---
## v2.3.15 - 2023-11-13
#### Changes:
* Increased productivity of ONU registration on  OLT ZTE C220
* Added the error messages on impossible license syncronization with the EasyPON server
* Fixed ONU deletion on the BDCOM 3310 OLTs
* Log entry improvements.
* Improved establishing SSH connection with OLT
* Added button to syncronize license status with the server
* Added feature of search ONU by its location.
* Handle error from invalid response during updating OLTs tx value. (36bb7ddb)
* Implemented a new method for the ONU deletion on Huawei OLTs. Reduced total process execution time by a factor of 10.
* Increased speed of get ONU on the specified card or port for the Huawei OLTs.
* Fixed displaying new installed version after upgrading EasyPON.
* Fixed port oper and admin status for BDCOM OLTs. Added Loss and PowerOFF statuses for ONU on this vendor.
* Changed services in the Debian installation to make it run better.
* Added functional of enable/disable public API
* Added filters for the ONU firmware variety table
* Redesigned OLT reply in the log, formatted as the terminal output. (2bec47c4)
* Added switch info for public API
* Updated public API: added config type to the ONU detail response and created new endpoint for detail config type response in the directory.
---
## v2.3.14 - 2023-09-22
#### Changes:
* Fixed installation
---
## v2.3.13 - 2023-09-22
#### Changes:
* Added some endpoints for the public API: onu types, olt types, custom action
* Removed external modules from the requirements (998e6ba2)
---
## v2.3.12 - 2023-09-20
#### Changes:
* Implemented secure auth module for the user profiles
* Fixed ONU filtering by mac and ordering by another field at the same time. (f3daeaa7)
* Fixes for system stability response
---
## v2.3.11 - 2023-08-31
#### Changes:
* Reduce task chunk amount for OLT ZTE c220
* Added detailed endpoint for report files
* Building map and table filters have been changed on to work with statuses and filters by OLT
* New methods to get ONU MAC-addresses from Userside by integration
* The comment section for ONU was added for use on each page of ONU detailed information
* Added block for application configuration to a non-existing ONU
* Fixed the missing ONU amount in generated reports on the All OLT page
* Added variety of statuses that are given by OLT BDCOM P3600-08E to see in the EasyPON
* The building types on the map and in general table now can be filtered and be seen differently by the icon as apartment buildings and private houses
---
## v2.3.10 - 2023-08-07

---
## v2.3.9 - 2023-07-24
#### Changes:
* The ONU autoregistration on 220 ZTE OLTs for additional clients were fixed (c18a636)
* Added the retry attempts to send command for the ONU registration
* Changed balance information in license by adding user address
* Added not showing the deleted ONUs on a building map (4c73cfd)
* Added new endpoint for external API (42f26ec)
* Set timeouts for cache keys (2f8247e)
* Move this documentation files to the correct folder for a right ordering (05fd9d0)
* Fixed proccess of getting ONU configs on BDCOM OLTs (467deea)
---
## v2.3.8 - 2023-07-13
#### Changes:
* Minor fixes of frontend layout (cff5d0f)
---
## v2.3.7 - 2023-07-12
#### Changes:
* Code refactoring (d3c300e)
* Added new statuses for building and to the filter (6c33c8f)
* Added filters by slots and ports to the building map (45993cf)
* Reduced DB queries (2aa3264)
* Added more info about author to the Event log section (c62a7d5)
* Forbid celery remote control (af06d42)
* Added usage of update methods to change port's admin status (33c9bd4)
---
## v2.3.6 - 2023-07-04
#### Changes:
* method for send and receive commands with retry (d0dd251)
* Merge branch 'EP-000/fix_bdcom_olt_creating' into 'stg' (8c448f3)
* fix BDCOM olt snmp protocol connection check and adding new one (4e9b45b)
* Added Userside check connection with data from user or from the settings (fe6a3a3)
* Opportunity to enable Userside sync and Google auth flag in the settings(d0b2269)
* Limited max retries and added timeout for OLT ZTE c220 ONU configuration(3747b37)
* Assigned new default permissions to the admin group (516a7c5)
* Fixed OLT SNMP protocol connection checking and adding new one for BDCOM vendors (78ac96a)
* Added external API schema (559a073)
* Awaken an error when the port operational status is unknown (5c7d9fd)
* Set port status as unknown when OLT does not response with the information about it (0be0975)
---
## v2.3.5 - 2023-06-21
#### Changes:
* Generated titles for log entry (f00af8e)
* Fixed registering ONU when number on port is unavailable (4a4c2de)
* Minor fixes for enhancing user experience satisfaction
---
## v2.3.4 - 2023-06-20

---
## v2.3.3 - 2023-06-20

---
## v2.3.2 - 2023-06-16
#### Changes:
* Fixes on the functional of ONU port migration (150f665)
* Changed default interval for periodic tasks (6e48c59)
* Fixes on ONU task status receiving (5687238)
* Added collecting of requested IP address(d8450d5)
* Started to update main ONU info on sync and refresh buttons from DB (55888cb)
* Separation of the templates and custom actions in a list through the system (a4c7241)
---
## v2.3.1 - 2023-06-13
#### Changes:
* fix mac assigment in userside integration (537c7be)
* Merge branch 'EP-000/more_descriptive_title_for_patch_log_entry' into 'stg' (0989103)
* added changed data to the title of log entry (3294376)
* Merge branch 'EP-000/fix_get_onu_mac_from_user_info' into 'stg' (fd5c754)
* use suppress context manager (dca7401)
* fix get onu mac or serial from userside user info (3d28ec1)
* Merge branch 'EP-000/add_ordering_by_title_to_account_logs' into 'stg' (fe215d4)
* added ordering by title (6e7175e)
* Merge branch 'EP-000/add_page_size_to_map_building' into 'stg' (a99ee45)
* replaced paginator with increased page size (48547d8)
* Merge branch 'EP-1025/validate_onu_instances_with_serializer' into 'stg' (fca4f54)
* Merge branch 'EP-000/fix_setting_userside_fields' into 'stg' (badf76d)
* Merge branch 'EP-000/fix_kwargs_assigment_in_api_logging' into 'stg' (37f1f5a)
* validate onu instances with serializer (b66d621)
* fix settings for userside integration (3933b50)
* create signal kwargs on class initialization (a524912)
* Merge branch 'EP-000/fix_client_group_assigment' into 'stg' (cf4aa13)
* fix retrieving crontab for tasks (aa4d4ea)
* fix retrieving crontab for tasks (b1da729)
* add client to admin site (5dd062b)
* fix group creation when not exists (a221259)
* Merge branch 'EP-000/remove_not_exists_task' into 'stg' (eeded54)
* Merge branch 'EP-000/fix_loging_failed_requests' into 'stg' (ab704e8)
* Merge branch 'EP-000/fix_userside_request_serivce' into 'stg' (1e7c96b)
* remove not exists task (cf7c15e)
* fix log error on failed request (c9be74e)
* fix request args (ad5d1f2)
* Merge branch 'EP-1076/filtering_and_ordering_building_list' into 'stg' (09d27de)
* remove redundant serializer (c16c12b)
* created filters and split serializers (69f0331)
* Merge branch 'EP-000/add_pagination_to_building_map' into 'stg' (7a8edf0)
* add pagination to building map (214444a)
* Merge branch 'EP-000/return_all_buildings_on_map' into 'stg' (262ae72)
* Resolve EP-000 "/return all buildings on map" (70909ef)
* Merge branch 'EP-000/include_onu_magic_and_olt_type_in_onu_response' into 'stg' (ddb617d)
* add onu magic and olt type in external onu response (eda168d)
* Merge branch 'EP-000/send_domain_name_on_sync_license_request' into 'stg' (6d0dd0c)
* send domain name in header on check license requests (d67d098)
* Merge branch 'EP-000/add_onu_list_to_building' into 'stg' (3755d5d)
* Resolve EP-000 "/add onu list to building" (90f63d2)
* Merge branch 'EP-1057/userside_integration_settings' into 'stg' (559cb1b)
* Resolve EP-1057 "/userside integration settings" (a8250c8)
* Merge branch 'stg' into 'master' (34f12f7)
* Fix filtering in map building (7751d9e)
* Merge branch 'stg' into 'master' (2865952)
* Exclude from map building empty buildings (9ca4343)
* Merge branch 'stg' into 'master' (d5fa64d)
* Add celery integration to sentry sdk (a9cf1e3)
* Change crontab of userside sync (507c2a2)
* Merge branch 'stg' into 'master' (b39dbdd)
* Merge branch 'EP-1059/add_permission_to_config_endpoint' into 'stg' (61c7c12)
* Resolve EP-1059 "/add permission to config endpoint" (03db858)
* Merge branch 'EP-000/fix_get_qinq_ports' into 'stg' (b79c9c0)
* fix retrieving qinq port (97ac61d)
* Merge branch 'EP-1048/save_search_filters' into 'stg' (d21f575)
* Save and manage filters the user uses to filter some data in different modules. (47a6c5d)
* Change format of geopoint in map_building (2077d63)
* Merge branch 'EP-1025/transfer_onu_location_and_notice_after_dublicate_deletion' into 'stg' (ba793ce)
* Resolve EP-1025 "/transfer onu location and notice after dublicate deletion" (6df012e)
* Fix switch urls (46d71ca)
* Merge branch 'EP-759/switch_topology' into 'stg' (9e83aa4)
* Add switch topology graph (9d9fc15)
* Merge branch 'EP-000/cherry_pick_card_type_to_external_onu_api' into 'master' (726de9d)
* added connection type to external onu api response (c108634)
* Merge branch 'EP-000/add_card_type_to_external_onu_api' into 'stg' (ea94f0d)
* added connection type to external onu api response (73c1a6a)
* Add type of userside synchronization (a642b6d)
* Merge branch 'EP-1015/change_invalid_login_description_message' into 'stg' (ba5ce34)
* Merge branch 'EP-1014/logout_user_after_deactivating' into 'stg' (8247c19)
* change invalid login description message (3747b18)
* logout user after deactivating (4eca60d)
---
## v2.3.0 - 2023-05-18
#### Changes:
* Merge branch 'stg' into 'master' (e11a482)
* Rename some settings (68bbc2e)
* Merge branch 'master' into stg (dd0d43a)
* Fix configuration with live settings (07475ea)
* Done with config in web (f9c95fc)
* Done with adding building to onu (37b964a)
* Add views/serializers for buildings and clients (af2391f)
* Done with buildings and clients (b768c8e)
* Add migration (4a1dede)
* Add integration for userside, now you can import geolocation onu (a4e6f7e)
* Update disprofile module (b882b4b)
* Add near onu geolocation (920ac3c)
* Merge branch 'EP-000/fix_searching_soft_deleted_onus' into 'stg' (f2cfbd4)
* Fix registering onu on deleted onu. (d0642c3)
* Merge branch 'EP-000/init_olt_cache_task' into 'stg' (f30824c)
* Add detail task information about initialise OLT. (34f1690)
* Merge branch 'EP-000/fix_creating_onu_config_type_on_huawei_ilt' into 'stg' (8b1427f)
* Fix onu config type creating on Huawei olt. (607e04d)
* Merge branch 'EP-000/fix_clear_deleting_old_report_files' into 'stg' (44bd020)
* Remove damaged reports after unsuccessful file downloading. (085058a)
* Merge branch 'EP-000/fix_updating_task_status_on_long_tasks' into 'stg' (64d58ab)
* Fix onu task status changes. (b5c685d)
* Merge branch 'EP-000/handle_snmp_error_on_onu_reboot' into 'stg' (3fe5f32)
* Return descriptive message when try to reboot onu and get the connection error. (78c153b)
* Add release to sentry tracking (250da80)
* Fix clients mac on huawei (9c851d5)
* Add find by hexed serial number onu (25aa30b)
* Merge branch 'EP-000/cherry_pick_fix_onu_tasks' into 'master' (505e319)
* Fix onu update tasks (e6f7c46)
* Skipped slots without qinq (bb6b87d)
* Merge branch 'EP-000/connect_status_information_with_update_onu_tasks' into 'stg' (d29df40)
* Fix onu update tasks (d787667)
* Merge branch 'EP-000/fix_update_vlans_task' into 'stg' (5b5a49f)
* Fix update onu ethernet vlans tasks. (c85d573)
* Merge branch 'EP-954/format_response_from_custom_actions' into 'stg' (c2d74ae)
* Formatted custom action result response. (11990b6)
* Merge branch 'EP-822/additional_ordering_for_some_tables' into 'stg' (8c7316c)
* Added ordering to for onu port migration and file report tables. (2a19963)
* Merge branch 'EP-948/remove_reports_with_non_exisiting_files' into 'stg' (299142e)
* Clear not existing files and delete them from the filesystem. (f7f0e37)
* Merge branch 'EP-000/show_onu_as_base_object_in_applied_presets' into 'stg' (763515d)
* Improved onu filtering in logs. (2420155)
* Merge branch 'EP-988/onu_soft_deletion' into 'stg' (f5afd7e)
* Log can handle the entire onu history. After onu deletion, it does not remove from db. (85dcc5a)
* Add version checker for huawei (56a90d0)
* Change commands for show config in huawei (a3d353a)
* Fix reboot on huawei (4a368e4)
* Fix full update onu on huawei (cab7422)
* Merge branch 'EP-980/add_huawei_support' into 'stg' (942ab9a)
* Add support of Huawei MA5608T. (9540005)
* Merge branch 'EP-964/client_can_set_google_keys_for_oauth2' into 'stg' (64a0208)
* make google keys not required (022017f)
* Merge branch 'EP-000/change_endpoint_for_release_check' into 'stg' (f7e0b51)
* It was improved receiving latest release information. Now get the version that matches client requirements. (267121d)
* Merge branch 'EP-959/show_is_user_member_of_admin_group' into 'stg' (34c008e)
* Show notification for admin users if a new version of EeasyPON was released. (a1e4374)
---
## v2.2.2 - 2023-05-01
#### Changes:
* Merge branch 'stg' into 'master' (c869301)
* Stg (5070bd3)
* Merge branch 'EP-000/add_action_permissions' into 'master' (acdb91f)
* Created permission for custom onu action. (4a8fded)
---
## v2.2.1 - 2023-04-27
#### Changes:
* Merge branch 'stg' into 'master' (ed310bd)
* Fix update onu on ZTE GPON (0b33d05)
---
## v2.2.0 - 2023-04-27
#### Changes:
* Release v2.1.1 (982ac49)
* Update .gitlab-ci.yml file (a2e4a18)
* Merge branch 'stg' into 'master' (c32a656)
* Fix problem with compiled version (cb893d1)
---
## v2.1.1 - 2023-04-27
#### Changes:
* Update .gitlab-ci.yml file (a2e4a18)
* Merge branch 'stg' into 'master' (c32a656)
* Fix problem with compiled version (cb893d1)
---
## v2.1.0 - 2023-04-27
#### Changes:
* Merge branch 'stg' into 'master' (07e33df)
* Merge branch 'EP-000/fix_template_variable_migration' into 'stg' (99f52d2)
* Fix install issue with DB migration. (03db83c)
* Fix problem with infinity get all onu on some ZTE (6c6e247)
* Fix problem on c320 with "No such instance" on get onu status (60459eb)
* Merge branch 'EP-000/find_olt_timezone_based_on_retrieved_time' into 'stg' (58752c1)
* Changed method for retrieving olt timezone to improve time calculation. (576fef3)
* Merge branch 'EP-946/fix_editing_periodic_tasks' into 'stg' (7989163)
* Fixed error when trying to update periodic tasks. (5b5866e)
* Merge branch 'EP-000/fix_shelf_retrieving_on_c220_olts' into 'stg' (4b2b435)
* Fixed error on retrieving shel information on ZTE C220 olts. (fc40d8a)
* Merge branch 'EP-000/set_name_for_deleted_onu_on_onu_configruation_log_entry' into 'stg' (64b7037)
* Increased description information about config onu log entry. (62134b9)
* Fix migrate onu on another port (19bbfe2)
* Disable prefetch related in olt viewset (b243cad)
* Merge branch 'EP-000/additional_fields_to_log_list' into 'stg' (4a178ee)
* Show additional info about the object in the main user log table. (9091164)
* Merge branch 'EP-000/remove_view_switch_logentry' into 'stg' (eb78d4d)
* Remove logging every view action on the switch and switch port. (7bb4929)
* Merge branch 'EP-000/onu_port_number_macros' into 'stg' (c987b52)
* New macros for retrieving onu port number (8bad61b)
* Merge branch 'EP-926/change_description_for_xlsx_export_when_filters_are_not_set' into 'stg' (61e098a)
* A more informative description of the Excel exported file. (f348f53)
* Merge branch 'EP-922/total_onus_counter' into 'stg' (83cb743)
* Added to background task that scans all "onus" on the olt more detailed information about each record.<br> Implemented a counter to keep track of the total number of ONUs found when scanning them on OLT. (3792717)
* Merge branch 'EP-000/update_install_instruction' into 'stg' (ba99a28)
* Updated install instructions (25e7fda)
* Merge branch 'EP-000/get_google_client_id_endpoint' into 'stg' (497691b)
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
* Merge branch 'EP-000/change_location_map_route' into 'stg' (d8f6790)
* Changed location map route. (e8e78cb)
* Merge branch 'EP-000/fix_onu_location_retrieving' into 'stg' (26b2b41)
* Fixed onu location retrieving (63cef46)
* Add cache-control to allow headers (db2c1ed)
* Test clear cache endpoint (1dfa70d)
* Merge branch 'EP-000/hide_internal_periodic_tasks' into 'stg' (89551c0)
* Removed the internal periodic tasks from the request result, so now users will only see the main tasks associated with them. (8dedbd9)
* Merge branch 'EP-819/save_front_filters' into 'stg' (46a718b)
* Added ability for users to save and retrieve filter parameters. (be73aef)
* Merge branch 'EP-820/create_install_md_file' into 'stg' (4149dbc)
* Added installation instructions for EasyPON. (496bf5e)
* Merge branch 'EP-888/add_new_fields_to_onu_logs' into 'stg' (d026ff1)
* Improve ONU logging to include information on retrieval and applying configuration results: success and failure. (bcefcc4)
* Merge branch 'EP-899/merge_migrations' into 'stg' (da92e29)
* Resolve EP-899 "/merge migrations" (7142e3b)
* Merge branch 'EP-899/add_permission_for_onu_duplicates' into 'stg' (c791550)
* Implement access control for dedicated source with new 'Can view onu duplicates' permission (f5ae1d0)
* add celery-expoter binary adn systemd service (49e2c1a)
* Merge branch 'EP-895/get_olt_name_on_the_olt_creation' into 'stg' (decdba2)
* Simplify the OLT registration process with the minimal required info: IP, login, pass, and olt type (30c8973)
* Merge branch 'EP-907/add_offline_time_to_duplicates_onus_on_detail_onu_edpoint' into 'stg' (691dbbd)
* Resolve EP-907 "/add offline time to duplicates onus on detail onu edpoint" (eb4648b)
* Merge branch 'EP-907/add_field_with_onu_duplicates_to_detail_onu' into 'stg' (04d8758)
* Implemented new feature for detail page that allows users to view a list of duplicated ONUs, if they exist. (6f27c17)
* Merge branch 'EP-903/remove_ru_description' into 'stg' (9df91a6)
* Streamlined project language support by keeping only English descriptions. (e81eaa2)
* Merge branch 'EP-822/add_ordering_for_all_tables' into 'stg' (8da11e8)
* Implemented new feature: Ordering filter now available for all tables. (e665ddd)
* Merge branch 'EP-884/remove_olt_name_from_onu_firmware_variety_list' into 'stg' (59771d2)
* In the onu firmware variety list, all rows are not grouped by olt. (6319bbb)
* Merge branch 'EP-847/change_start_time_for_tasks' into 'stg' (a6b4e2d)
* Resolve EP-847 "/change start time for tasks" (4ca46db)
* Merge branch 'EP-872/translate_permissions' into 'stg' (410955c)
* edit all permissions name (250d4db)
* Merge branch 'EP-847/rework_olt_periodic_tasks' into 'stg' (cf8e0f3)
---
## v2.0.3 - 2023-04-03

---
## v2.0.2 - 2023-03-29
#### Changes:
* Merge branch 'stg' (cc9940f)
* Update release-it package (da53d73)
* Merge remote-tracking branch 'origin/master' (af56bc3)
* Add artifacts (7b8e461)
---
## v2.0.1 - 2023-03-29
#### Changes:
* Merge branch 'stg' (8466619)
* Done with cicd (e6735b6)
* Merge branch 'stg' into 'master' (7bcda83)
* Merge remote-tracking branch 'origin/stg' into stg (0a9a612)
* Fix module (764a6ea)
* Merge branch 'EP-000/release_changelog_and_decompess_response_data' into 'stg' (ea4a79d)
* remove compressed data (f41cb55)
* fix outdated checking (750abc7)
* add latest ep release endpoint (f3eab1f)
* decompress data in license check request (5af9d9b)
---
## v2.0.0 - 2023-03-29

---
## v1.0.0 - 2023-03-28
