^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package panther_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.0.1 (2024-05-01)
------------------
* Prevent unwanted PR (`#35 <https://github.com/husarion/panther_msgs/issues/35>`_)
* Add PR body (`#33 <https://github.com/husarion/panther_msgs/issues/33>`_)
* Update workflow (`#30 <https://github.com/husarion/panther_msgs/issues/30>`_)
* Revert version in package.xml (`#29 <https://github.com/husarion/panther_msgs/issues/29>`_)
* Ros2 automatize release process (`#25 <https://github.com/husarion/panther_msgs/issues/25>`_)
* Merge pull request `#22 <https://github.com/husarion/panther_msgs/issues/22>`_ from husarion/ros2-update-workflow
* Update setup-ros
* Merge pull request `#21 <https://github.com/husarion/panther_msgs/issues/21>`_ from husarion/release-2.0.0-alpha
* Contributors: Jakub Delicat, Paweł Irzyk, Paweł Kowalski, rafal-gorecki

2.0.0 (2024-03-29)
------------------
* Merge pull request `#19 <https://github.com/husarion/panther_msgs/issues/19>`_ from husarion/ros2-fix-typo
  fix typo
* fix typo
* Merge pull request `#17 <https://github.com/husarion/panther_msgs/issues/17>`_ from husarion/ros2-control
  Ros2 control changes
* ros2_control PDO commands (`#18 <https://github.com/husarion/panther_msgs/issues/18>`_)
  * Add heatsink temperature
  * Update error names
  * Update timed out errors
* Merge branch 'ros2' into ros2-control
  Conflicts:
  msg/DriverState.msg
  msg/MotorControllerState.msg
  msg/MotorState.msg
* Refactor motor controller state msg - remove joint name and move runtime error
* Move can error to motorcontrollerstate
* Rename fields
* Add more information to driver state msg
* Merge pull request `#16 <https://github.com/husarion/panther_msgs/issues/16>`_ from husarion/ros2-update-panther-msgs
  ROS 2 update panther msgs
* Update services
* Update messages
* update package.xml
* add DriverState msg
* ROS2 devel (`#2 <https://github.com/husarion/panther_msgs/issues/2>`_)
  * Initial commit
  * Initial commit
  * Fix issue with no panther_msgs listing
  * Change workflow name
  * Change workflow file name
  * Fix workflows folder name typo
  * Change workflow name
  * Reatach ROS2 workflow to ros2 branch
  * Update package.xml
  * Unwrap package folder
  * Fixed email by adding .com in package.xml
  Co-authored-by: Nicolas Duc <49471089+TopRamen1@users.noreply.github.com>
* Initial commit
* Contributors: Dawid, Dominik Nowak, Krzysztof Wojciechowski, Maciej Stępień, Paweł Kowalski
