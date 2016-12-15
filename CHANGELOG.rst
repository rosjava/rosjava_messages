Changelog
=========

0.3.0 (2016-12-15)
------------------
* updates for Kinetic release.

0.2.2 (2015-04-22)
------------------
* add world_canvas_msgs

0.2.1 (2015-02-25)
------------------
* workaround for move_base_msgs (add roscpp as a msg package).
* dependencies for builds of rosjava/android core and android interactions added.
* restructured as a meta-message artifact generator of core messages only for indigo.
* Contributors: Daniel Stonier, Martin Pecka


0.1.52 (2013-12-26)
-------------------
* message generation and indexing now more intelligent, checks message_generation deps, not xxx_msgs naming.
* scrapes for many more packages (too many to list) with the new indexing

0.1.40 (2013-11-11)
-------------------
* tf2_geometry_msgs -> 0.4.9 

0.1.39 (2013-11-11)
-------------------
* velodyne_msgs -> 1.1.2
* yocs_msgs -> 0.5.2

0.1.38 (2013-11-01)
-------------------
* constrain open ranged dependencies.

0.1.37 (2013-11-01)
-------------------
* concert_msgs -> 0.6.4
* gateway_msgs -> 0.6.4
* rocon_app_manager_msgs -> 0.6.4
* rocon_msgs -> 0.6.4

0.1.36 (2013-10-31)
-------------------
* remove unintended rocon_std_msgs

0.1.35 (2013-10-31)
-------------------
* use ROS_MAVEN_REPOSITORY
* concert_msgs -> 0.6.3
* gateway_msgs -> 0.6.3
* rocon_app_manager_msgs -> 0.6.3
* rocon_msgs -> 0.6.3
* + humanoid_msgs -> 0.2.0
* + humanoid_nav_msgs -> 0.2.0
* + nao_msgs -> 0.2.2

0.1.32 (2013-10-25)
-------------------
* use maven style open range dependencies

0.1.31 (2013-10-09)
-------------------
* rosserial_msgs -> 0.5.4
* + wireless_msgs -> 0.0.1
* multimaster_fkie_msgs -> 0.3.7
* kingfisher_msgs -> 0.0.2
* yocs_msgs -> 0.5.1
* controller_manager_msgs -> 0.5.8
* gazebo_msgs -> 2.3.2
* hector_nav_msgs -> 0.3.1

0.1.22 (2013-10-09)
-------------------
* + yocs_msgs -> 0.4.1
* + sr_ronex_messages -> 0.9.3
* rosgraph_msgs -> 1.9.50
* std_srvs -> 1.9.50
* geographic_msgs -> 0.3.1
* move_base_msgs -> 1.11.4
* moveit_msgs -> 0.5.2

0.1.15 (2013-09-23)
-------------------
* use updated ros gradle plugins with maven-publish for publishing.

0.1.14 (2013-09-22)
-------------------
* rosserial_msgs -> 0.5.3
* rosgraph_msgs -> 1.9.49
* std_srvs -> 1.9.49
* gazebo_msgs -> 2.3.2

0.1.11 (2013-09-18)
-------------------
* run_depends on the build tools only

0.1.9 (2013-09-17)
------------------
* added ugly mixed msg/code map_store dependency for android_apps

0.1.8 (2013-09-17)
------------------
* gradle wrapper -> 1.7
* avoid crashes if the environment isn't exactly correct.

0.1.7 (2013-09-13)
------------------
* first release that has done a full scrape of rosdistro for 'official messages'.
* rosjava's test_ros messages bundled here as a sub-packages (somewhat dirtily).
