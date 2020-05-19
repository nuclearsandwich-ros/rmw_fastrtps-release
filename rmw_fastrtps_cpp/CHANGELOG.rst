^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rmw_fastrtps_cpp
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.0 (2020-05-12)
------------------
* Remove API related to manual by node liveliness.  (`#379 <https://github.com/ros2/rmw_fastrtps/issues/379>`_)
* Update quality declarations on feature testing. (`#380 <https://github.com/ros2/rmw_fastrtps/issues/380>`_)
* Contributors: Ivan Santiago Paunovic, Michel Hidalgo

0.9.1 (2020-05-08)
------------------
* Add package READMEs and QUALITY_DECLARATION files (`#375 <https://github.com/ros2/rmw_fastrtps/issues/375>`_)
* Added doxyfiles (`#372 <https://github.com/ros2/rmw_fastrtps/issues/372>`_)
* Contributors: Alejandro Hernández Cordero, brawner

0.9.0 (2020-04-28)
------------------
* Add missing export of rmw_dds_common. (`#374 <https://github.com/ros2/rmw_fastrtps/issues/374>`_)
* Rename rosidl_message_bounds_t. (`#373 <https://github.com/ros2/rmw_fastrtps/issues/373>`_)
* Feature/services timestamps. (`#369 <https://github.com/ros2/rmw_fastrtps/issues/369>`_)
* Add support for taking a sequence of messages. (`#366 <https://github.com/ros2/rmw_fastrtps/issues/366>`_)
* security-context -> enclave. (`#365 <https://github.com/ros2/rmw_fastrtps/issues/365>`_)
* Rename rosidl_generator_c namespace to rosidl_runtime_c. (`#367 <https://github.com/ros2/rmw_fastrtps/issues/367>`_)
* Remove custom typesupport for rmw_dds_common interfaces. (`#364 <https://github.com/ros2/rmw_fastrtps/issues/364>`_)
* Added rosidl_runtime c and cpp depencencies. (`#351 <https://github.com/ros2/rmw_fastrtps/issues/351>`_)
* Switch to one Participant per Context. (`#312 <https://github.com/ros2/rmw_fastrtps/issues/312>`_)
* Add rmw\_*_event_init() functions. (`#354 <https://github.com/ros2/rmw_fastrtps/issues/354>`_)
* Fixing type support C/CPP mix on rmw_fastrtps_dynamic_cpp. (`#350 <https://github.com/ros2/rmw_fastrtps/issues/350>`_)
* Fix build warning in Ubuntu Focal. (`#346 <https://github.com/ros2/rmw_fastrtps/issues/346>`_)
* Code style only: wrap after open parenthesis if not in one line. (`#347 <https://github.com/ros2/rmw_fastrtps/issues/347>`_)
* Passing down type support information (`#342 <https://github.com/ros2/rmw_fastrtps/issues/342>`_)
* Implement functions to get publisher and subcription informations like QoS policies from topic name. (`#336 <https://github.com/ros2/rmw_fastrtps/issues/336>`_)
* Contributors: Alejandro Hernández Cordero, Dirk Thomas, Ingo Lütkebohle, Ivan Santiago Paunovic, Jaison Titus, Miaofei Mei, Michael Carroll, Miguel Company, Mikael Arguedas

0.8.1 (2019-10-23)
------------------
* use return_loaned_message_from (`#334 <https://github.com/ros2/rmw_fastrtps/issues/334>`_)
* Restrict traffic to localhost only if env var is provided (`#331 <https://github.com/ros2/rmw_fastrtps/issues/331>`_)
* Zero copy api (`#322 <https://github.com/ros2/rmw_fastrtps/issues/322>`_)
* update signature for added pub/sub options (`#329 <https://github.com/ros2/rmw_fastrtps/issues/329>`_)
* Contributors: Brian Marchi, Karsten Knese, William Woodall

0.8.0 (2019-09-25)
------------------
* Add function for getting clients by node (`#293 <https://github.com/ros2/rmw_fastrtps/issues/293>`_)
* Implement get_actual_qos() for subscriptions (`#287 <https://github.com/ros2/rmw_fastrtps/issues/287>`_)
* Fix error message (`#290 <https://github.com/ros2/rmw_fastrtps/issues/290>`_)
* Contributors: Jacob Perron, M. M

0.7.3 (2019-05-29)
------------------

0.7.2 (2019-05-20)
------------------
* Centralize topic name creation logic and update to match FastRTPS 1.8 API (`#272 <https://github.com/ros2/rmw_fastrtps/issues/272>`_)
* Contributors: Nick Burek

0.7.1 (2019-05-08)
------------------
* Support arbitrary message namespaces  (`#266 <https://github.com/ros2/rmw_fastrtps/issues/266>`_)
* Add qos interfaces with no-op (`#271 <https://github.com/ros2/rmw_fastrtps/issues/271>`_)
* Updates for preallocation API. (`#274 <https://github.com/ros2/rmw_fastrtps/issues/274>`_)
* Contributors: Jacob Perron, Michael Carroll, Ross Desmond

0.7.0 (2019-04-13)
------------------
* Add function to get publisher actual qos settings (`#267 <https://github.com/ros2/rmw_fastrtps/issues/267>`_)
* pass context to wait set and fini context (`#252 <https://github.com/ros2/rmw_fastrtps/issues/252>`_)
* Improve service_is_available logic to protect that client is waiting forever (`#238 <https://github.com/ros2/rmw_fastrtps/issues/238>`_)
* Merge pull request `#250 <https://github.com/ros2/rmw_fastrtps/issues/250>`_ from ros2/support_static_lib
* use namespace_prefix from shared package
* Contributors: Dirk Thomas, DongheeYe, William Woodall, ivanpauno

0.6.1 (2018-12-06)
------------------
* Add topic cache object for managing topic relations (`#236 <https://github.com/ros2/rmw_fastrtps/issues/236>`_)
* Fastrtps 1.7.0 (`#233 <https://github.com/ros2/rmw_fastrtps/issues/233>`_)
* RMW_FastRTPS configuration from XML only (`#243 <https://github.com/ros2/rmw_fastrtps/issues/243>`_)
* refactor to support init options and context (`#237 <https://github.com/ros2/rmw_fastrtps/issues/237>`_)
* Methods to retrieve matched counts on pub/sub (`#234 <https://github.com/ros2/rmw_fastrtps/issues/234>`_)
* use uint8_array (`#240 <https://github.com/ros2/rmw_fastrtps/issues/240>`_)
* Contributors: Juan Carlos, Karsten Knese, Michael Carroll, MiguelCompany, Ross Desmond, William Woodall

0.6.0 (2018-11-16)
------------------
* Add semicolons to all RCLCPP and RCUTILS macros. (`#229 <https://github.com/ros2/rmw_fastrtps/issues/229>`_)
* Include node namespaces in get_node_names (`#224 <https://github.com/ros2/rmw_fastrtps/issues/224>`_)
* add rmw_get_serialization_format (`#215 <https://github.com/ros2/rmw_fastrtps/issues/215>`_)
* Merge pull request `#218 <https://github.com/ros2/rmw_fastrtps/issues/218>`_ from ros2/pr203
* Revert "fix template closing indentation (`#214 <https://github.com/ros2/rmw_fastrtps/issues/214>`_)"
* fix template closing indentation (`#214 <https://github.com/ros2/rmw_fastrtps/issues/214>`_)
* Contributors: Chris Lalancette, Dirk Thomas, Karsten Knese, Michael Carroll, Miguel Company, Mikael Arguedas

0.5.1 (2018-06-28)
------------------
* update maintainer
* Contributors: Dirk Thomas

0.5.0 (2018-06-23)
------------------
* Avoid allocations (`#211 <https://github.com/ros2/rmw_fastrtps/issues/211>`_)
* Temporary buffer remove (`#207 <https://github.com/ros2/rmw_fastrtps/issues/207>`_)
* Validate the buffer\_ of CustomServiceRequest object before using it to (`#210 <https://github.com/ros2/rmw_fastrtps/issues/210>`_)
* update usage of rcutils_join_path() (`#208 <https://github.com/ros2/rmw_fastrtps/issues/208>`_)
* Expose raw CDR stream for publish and subscribe (`#186 <https://github.com/ros2/rmw_fastrtps/issues/186>`_)
* Remove topic partitions (`#192 <https://github.com/ros2/rmw_fastrtps/issues/192>`_)
* Fix leak if client reponse is never taken (`#201 <https://github.com/ros2/rmw_fastrtps/issues/201>`_)
* Revert "Export rmw_fastrtps_cpp target" (`#200 <https://github.com/ros2/rmw_fastrtps/issues/200>`_)
* Support access control  (`#197 <https://github.com/ros2/rmw_fastrtps/issues/197>`_)
* Export rmw_fastrtps_cpp target (`#198 <https://github.com/ros2/rmw_fastrtps/issues/198>`_)
* Fix deserialization segfault in bionic. (`#199 <https://github.com/ros2/rmw_fastrtps/issues/199>`_)
* Fix namespaces (`#196 <https://github.com/ros2/rmw_fastrtps/issues/196>`_)
* Merge pull request `#182 <https://github.com/ros2/rmw_fastrtps/issues/182>`_ from ros2/node_name_in_user_data
* add participant listener
* add node name to user data
* change export order for static linking (`#190 <https://github.com/ros2/rmw_fastrtps/issues/190>`_)
* update style (`#189 <https://github.com/ros2/rmw_fastrtps/issues/189>`_)
* optimize timeout judgement according to different condition (`#187 <https://github.com/ros2/rmw_fastrtps/issues/187>`_)
* use existing check_wait_set_for_data to avoid duplicated code (`#185 <https://github.com/ros2/rmw_fastrtps/issues/185>`_)
* Enable logging level manipulation from rmw_fastrtps (`#156 <https://github.com/ros2/rmw_fastrtps/issues/156>`_)
* Small performance improvements (`#183 <https://github.com/ros2/rmw_fastrtps/issues/183>`_)
* Segmentation error to dereference nullptr (`#180 <https://github.com/ros2/rmw_fastrtps/issues/180>`_)
* Contributors: Dirk Thomas, Ethan Gao, Guillaume Autran, Karsten Knese, Michael Carroll, MiguelCompany, Mikael Arguedas, Minggang Wang, Rohit Salem, Shane Loretz, Sriram Raghunathan, William Woodall, jwang11

0.4.0 (2017-12-08)
------------------
* Merge pull request `#178 <https://github.com/ros2/rmw_fastrtps/issues/178>`_ from ros2/fix_wrong_count
* Merge pull request `#177 <https://github.com/ros2/rmw_fastrtps/issues/177>`_ from ros2/rename_group
* Wait set two words (`#175 <https://github.com/ros2/rmw_fastrtps/issues/175>`_)
* not exporting pthread manually (`#174 <https://github.com/ros2/rmw_fastrtps/issues/174>`_)
* Merge pull request `#169 <https://github.com/ros2/rmw_fastrtps/issues/169>`_ from ros2/rep149
* Merge pull request `#171 <https://github.com/ros2/rmw_fastrtps/issues/171>`_ from jwang11/master
* rcutils_join_path returns a char * now. (`#173 <https://github.com/ros2/rmw_fastrtps/issues/173>`_)
* memory leak issue (`#172 <https://github.com/ros2/rmw_fastrtps/issues/172>`_)
* Unify and simplify de/serializeROSmessage processing
* Avoid duplicated code in calculateMaxSerializedSize for array and normal member (`#168 <https://github.com/ros2/rmw_fastrtps/issues/168>`_)
* Fix the issues to dereference to nullptr (`#165 <https://github.com/ros2/rmw_fastrtps/issues/165>`_)
* Fix rmw_fastrtps dead code (`#163 <https://github.com/ros2/rmw_fastrtps/issues/163>`_)
* Merge pull request `#167 <https://github.com/ros2/rmw_fastrtps/issues/167>`_ from deng02/tune-count-pub-sub
* Remove string allocation in the count of subscribers and publishers
* use auto deduction and nullptr to keep coding style consistent (`#162 <https://github.com/ros2/rmw_fastrtps/issues/162>`_)
* Merge pull request `#164 <https://github.com/ros2/rmw_fastrtps/issues/164>`_ from dejanpan/master
* Fix several parameter check issues in rmw_fastrtps_cpp apis
* Remove unnecessary dependency on rosidl_generator_cpp (`#161 <https://github.com/ros2/rmw_fastrtps/issues/161>`_)
* Move the hasData checks for non-blocking wait 'timeout' higher (`#158 <https://github.com/ros2/rmw_fastrtps/issues/158>`_)
* Support loading default XML profile file (`#153 <https://github.com/ros2/rmw_fastrtps/issues/153>`_)
* Drop duplicated rmw_init.cpp in rmw_fastrtps_cpp/CMakeLists.txt (`#155 <https://github.com/ros2/rmw_fastrtps/issues/155>`_)
* Merge pull request `#154 <https://github.com/ros2/rmw_fastrtps/issues/154>`_ from ros2/uncrustify_master
* Removing magic numbers: old maximun lengths (`#152 <https://github.com/ros2/rmw_fastrtps/issues/152>`_)
