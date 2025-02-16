# Ignition Release Features

Here you will find the set of features that are available in each release.

Take a look at the [Roadmap](/docs/roadmap) for information about upcoming
features, some of which may land in released versions of Ignition.

## Acropolis (EOL)

The first major release of Ignition focused on the basics of simulation. The basics primarily encompassed integration of physics, sensors, graphical tools, and programmatic interfaces.

1. Support for [DART](https://dartsim.github.io/) in [Ignition Physics](/libs/physics).
2. Ogre1.9 and Ogre2.1 support in [Ignition Rendering](/libs/rendering)
3. [Entity Component System](https://en.wikipedia.org/wiki/Entity_component_system) based simulation engine in [Ignition Gazebo](/libs/gazebo).
4. A sensor suite that includes contact sensor, logical camera, monocular camera, depth camera, LIDAR, magnetometer, altimeter, and IMU is available through [Ignition Sensors](/libs/sensors) and [Ignition Gazebo](/libs/gazebo).
5. [Launch system](/libs/launch) capable of running and managing a set of plugins and executables.
6. Cloud-hosted simulation assets provided by [app.ignitionrobotics.org](https://app.ignitionrobotics.org).
7. Distributed simulation using lock-stepping.
8. Dynamic loading/unloading of simulation models based on the location of performer, usually a robot.
9. Simulation state logging.
10. Plugin-based GUI system based on [QtQuick](https://en.wikipedia.org/wiki/Qt_Quick) and [Material Design](https://material.io/design/). Available
    plugins include 3D scene viewer, image viewer, topic echo, topic
    publisher, world control, and world statistics.

The Acropolis collection is composed by many different Ignition libraries. The
collection assures that all libraries all compatible and can be used together.

| Library name       | Version       | Changelog     |
| ------------------ |:-------------:|:-------------:|
|   ign-cmake        |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-cmake/blob/ign-cmake2/Changelog.md)     |
|   ign-common       |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-common/blob/ign-common3/Changelog.md)    |
|   ign-fuel-tools   |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-fuel-tools/blob/ign-fuel-tools3/Changelog.md)    |
|   ign-gazebo       |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gazebo/blob/ign-gazebo1/Changelog.md)     |
|   ign-gui          |       1.x     |       None       |
|   ign-launch       |       0.x     |       None       |
|   ign-math         |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-math/blob/ign-math6/Changelog.md)     |
|   ign-msgs         |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-msgs/blob/ign-msgs3/Changelog.md)     |
|   ign-physics      |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-physics/blob/ign-physics1/Changelog.md)      |
|   ign-plugin       |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-plugin/blob/ign-plugin1/Changelog.md)     |
|   ign-rendering    |       1.x     |       None      |
|   ign-sensors      |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-sensors/blob/ign-sensors1/Changelog.md)      |
|   ign-tools        |       0.x     |       [Changelog](https://github.com/ignitionrobotics/ign-tools/blob/ign-tools0/Changelog.md)     |
|   ign-transport    |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-transport/blob/ign-transport6/Changelog.md)      |
|   sdformat         |       8.x     |       [Changelog](https://github.com/osrf/sdformat/blob/sdf8/Changelog.md)        |


## Blueprint (EOL)

1. [Physically based rendering (PBR)](https://en.wikipedia.org/wiki/Physically_based_rendering) materials.
1. Air pressure, RGBD and stereo camera sensors.
1. Global wind model.
1. Joint state publisher.
1. Support for UAVs.
1. Integration of `ign` command line tool into Ignition Gazebo.
1. Logging and playback of simulation state.
1. Command line tools to control log playback.
1. Battery model based on vehicle motion and rechargeable batteries.
1. Integration of [Google benchmark](https://github.com/google/benchmark) for performance metrics and analysis.
1. Tracked vehicle support.
1. Breadcrumbs plugin.
1. Position-based PID controller.
1. Improved resource path handling.
1. Loading custom physics engine plugins.
1. Plugin that publishes a user specified message on an output topic in response to an input message.
1. Noise for RGBD camera.
1. Load worlds from Fuel.
1. [Customizable GUI layout](https://ignitionrobotics.org/api/gazebo/3.3/gui_config.html).
1. [Detachable joints](https://ignitionrobotics.org/api/gazebo/4.0/detachablejoints.html)
1. GUI tools:
    * GUI tools for model placement, and a new Scene Tree widget.
    * Translate and rotate models.
    * Entity tree.
    * Video recorder.
    * Move to models.
    * Follow model.
    * Delete model.
    * Grid.
    * Drag-and-drop models from Fuel to Ignition Gazebo UI.
    * Preset view angles.
    * Hotkeys for transform modes and snapping.
    * Entity selection.
    * [Align models](https://ignitionrobotics.org/docs/dome/manipulating_models#align-tool).
    * Insert simple shapes.
    * Insert models from online sources and local directories.
    * Log playback scrubber.
    * Save worlds.
    * Tape measure.

| Library name       | Version       | Changelog     |
| ------------------ |:-------------:|:-------------:|
|   ign-cmake        |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-cmake/blob/ign-cmake2/Changelog.md)     |
|   ign-common       |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-common/blob/ign-common3/Changelog.md)    |
|   ign-fuel-tools   |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-fuel-tools/blob/ign-fuel-tools3/Changelog.md)    |
|   ign-gazebo       |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gazebo/blob/ign-gazebo2/Changelog.md)     |
|   ign-gui          |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gui/blob/ign-gui2/Changelog.md)       |
|   ign-launch       |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-launch/blob/ign-launch1/Changelog.md)
|   ign-math         |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-math/blob/ign-math6/Changelog.md)
|   ign-msgs         |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-msgs/blob/ign-msgs4/Changelog.md)
|   ign-physics      |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-physics/blob/ign-physics1/Changelog.md)
|   ign-plugin       |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-plugin/blob/ign-plugin1/Changelog.md)     |
|   ign-rendering    |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-rendering/blob/ign-rendering2/Changelog.md)      |
|   ign-sensors      |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-sensors/blob/ign-sensors2/Changelog.md)      |
|   ign-tools        |       0.x     |       [Changelog](https://github.com/ignitionrobotics/ign-tools/blob/ign-tools0/Changelog.md)
|   ign-transport    |       7.x     |       [Changelog](https://github.com/ignitionrobotics/ign-transport/blob/ign-transport7/Changelog.md)
|   sdformat         |       8.x     |       [Changelog](https://github.com/osrf/sdformat/blob/sdf8/Changelog.md)        |


## Citadel (LTS)

1. Visual markers.
1. Animated actors for Ogre 1 and Ogre 2.
1. Thermal camera sensor.
1. Emissive texture maps.
1. SDFormat frame semantics.
1. Upload and delete models to Fuel from command line.
1. Buoyancy model.
1. [Trivial Physics Engine](https://community.gazebosim.org/t/announcing-new-physics-engine-tpe-trivial-physics-engine/629)
1. [Tutorial series](https://community.gazebosim.org/t/gsoc-2020-new-ignition-gazebo-demos/613).
1. [Improved Ignition Physics documentation.](https://community.gazebosim.org/t/gsod-2020-ignition-physics-tutorial-and-api-documentation/746)
1. [Custom rendering engines.](https://ignitionrobotics.org/api/rendering/3.2/renderingplugin.html)
1. [Logical audio sensor and source.](https://ignitionrobotics.org/api/gazebo/3.7/logicalaudiosensor.html)
1. Lockstepped video recording that can optionally use simulation time instead of real time.
1. [Easier migration of SDF files from Gazebo classic.](https://ignitionrobotics.org/api/gazebo/3.7/migrationsdf.html)
1. [Binary Windows install through conda-forge.](https://ignitionrobotics.org/docs/citadel/install_windows)
1. [Restitution coefficient (bouncing).](https://github.com/ignitionrobotics/ign-physics/pull/139)
1. [Custom retroreflection for objects detected by lidar.](https://github.com/ignitionrobotics/ign-gazebo/blob/ign-gazebo3/examples/worlds/gpu_lidar_retro_values_sensor.sdf)
1. [More SDFormat documentation](http://sdformat.org/tutorials).
1. Load PBR materials from OBJ.
1. [Model info CLI.](https://github.com/ignitionrobotics/ign-gazebo/issues/313)
1. [Test fixture to easily run simulation-based automated tests.](https://ignitionrobotics.org/api/gazebo/3.9/test_fixture.html)
1. [Drag and drop meshes into the scene.](https://github.com/ignitionrobotics/ign-gazebo/pull/939)
1. [Tracked vehicles](https://github.com/ignitionrobotics/ign-gazebo/pull/869)
1. [Python interface for Ignition Math.](https://github.com/ignitionrobotics/ign-math/issues/210)
1. [Integration with ros2_control.](https://github.com/ignitionrobotics/ign_ros2_control/)
1. [ign_ros2_control support for various models](https://github.com/ignitionrobotics/docs/issues/222)
1. [Polyline extruded 2D geometries](https://github.com/ignitionrobotics/docs/issues/186)
1. New graphical interfaces:
    * Widget listing all transport topics.
    * Widget that publishes keys pressed on the keyboard.
    * Collision visualization.
    * [Screenshot widget.](https://ignitionrobotics.org/api/gui/3.5/screenshot.html)
    * [Joint position controller.](https://app.ignitionrobotics.org/OpenRobotics/fuel/worlds/NAO%20joint%20control)
    * [2D teleop widget.](https://github.com/ignitionrobotics/ign-gui/issues/186)
    * [3D plot.](https://github.com/ignitionrobotics/ign-gazebo/issues/231)
    * [Notification snackbar](https://github.com/ignitionrobotics/ign-gui/issues/44)
1. APIs that make it easier to migrate from Gazebo classic:
    * [World](https://ignitionrobotics.org/api/gazebo/3.5/migrationworldapi.html)
    * [Model](https://ignitionrobotics.org/api/gazebo/3.5/migrationmodelapi.html)
    * [Link](https://ignitionrobotics.org/api/gazebo/3.5/migrationlinkapi.html)

| Library name       | Version       | Changelog     |
| ------------------ |:-------------:|:-------------:|
|   ign-cmake        |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-cmake/blob/ign-cmake2/Changelog.md)     |
|   ign-common       |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-common/blob/ign-common3/Changelog.md)    |
|   ign-fuel-tools   |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-fuel-tools/blob/ign-fuel-tools4/Changelog.md)    |
|   ign-gazebo       |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gazebo/blob/ign-gazebo3/Changelog.md)     |
|   ign-gui          |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gui/blob/ign-gui3/Changelog.md)       |
|   ign-launch       |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-launch/blob/ign-launch2/Changelog.md)
|   ign-math         |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-math/blob/ign-math6/Changelog.md)
|   ign-msgs         |       5.x     |       [Changelog](https://github.com/ignitionrobotics/ign-msgs/blob/ign-msgs5/Changelog.md)
|   ign-physics      |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-physics/blob/ign-physics2/Changelog.md)
|   ign-plugin       |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-plugin/blob/ign-plugin1/Changelog.md)     |
|   ign-rendering    |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-rendering/blob/ign-rendering3/Changelog.md)      |
|   ign-sensors      |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-sensors/blob/ign-sensors3/Changelog.md)      |
|   ign-tools        |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-tools/blob/ign-tools1/Changelog.md)     |
|   ign-transport    |       8.x     |       [Changelog](https://github.com/ignitionrobotics/ign-transport/blob/ign-transport8/Changelog.md)      |
|   sdformat         |       9.x     |       [Changelog](https://github.com/osrf/sdformat/blob/sdf9/Changelog.md)        |


## Dome (EOL)

1. Particle effects on [Ignition Rendering](https://ignitionrobotics.org/api/rendering/4.1/particles.html) and [Ignition Gazebo](https://github.com/ignitionrobotics/ign-gazebo/blob/ign-gazebo4/examples/worlds/particle_emitter.sdf).
1. Actor plugins.
1. Efficient skeleton animations.
1. [Optical tactile sensor plugin.](https://community.gazebosim.org/t/gsoc-2020-ignition-gazebo-optical-tactile-sensor-plugin/618)
1. [Support entity names with spaces.](https://github.com/ignitionrobotics/ign-gazebo/issues/239)
1. Kinetic energy monitor plugin.
1. [Texture-based thermal signature](https://ignitionrobotics.org/api/sensors/4.1/thermalcameraigngazebo.html) for objects, visible from thermal camera.
1. [Web visualization of running simulations](https://ignitionrobotics.org/docs/dome/web_visualization).
1. [Bullet physics engine.](https://github.com/ignitionrobotics/ign-physics/issues/44)
1. [Parametrized SDF files.](http://sdformat.org/tutorials?tut=param_passing_proposal)
1. [libSDFormat now uses ign-cmake](https://github.com/ignitionrobotics/sdformat/issues/181)
1. GUI tools:
    * [Plotting](https://community.gazebosim.org/t/gsoc-2020-plotting-tool-for-ignition/619)
    * [Lidar visualization](https://community.gazebosim.org/t/gsoc-2020-sensor-data-visualization/638)
    * [Configure physics real time factor and step size.](https://github.com/ignitionrobotics/ign-gazebo/pull/536)
    * [Configure lights from the GUI or transport.](https://github.com/ignitionrobotics/ign-gazebo/issues/122)
    * [Contact visualization.](https://github.com/ignitionrobotics/ign-gazebo/issues/234)

| Library name       | Version       | Changelog     |
| ------------------ |:-------------:|:-------------:|
|   ign-cmake        |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-cmake/blob/ign-cmake2/Changelog.md)     |
|   ign-common       |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-common/blob/ign-common3/Changelog.md)    |
|   ign-fuel-tools   |       5.x     |       [Changelog](https://github.com/ignitionrobotics/ign-fuel-tools/blob/ign-fuel-tools5/Changelog.md)    |
|   ign-gazebo       |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gazebo/blob/ign-gazebo4/Changelog.md)     |
|   ign-gui          |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gui/blob/ign-gui4/Changelog.md)       |
|   ign-launch       |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-launch/blob/ign-launch3/Changelog.md)
|   ign-math         |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-math/blob/ign-math6/Changelog.md)
|   ign-msgs         |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-msgs/blob/ign-msgs6/Changelog.md)
|   ign-physics      |       3.x     |       [Changelog](https://github.com/ignitionrobotics/ign-physics/blob/ign-physics3/Changelog.md)
|   ign-plugin       |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-plugin/blob/ign-plugin1/Changelog.md)     |
|   ign-rendering    |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-rendering/blob/ign-rendering4/Changelog.md)      |
|   ign-sensors      |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-sensors/blob/ign-sensors4/Changelog.md)      |
|   ign-tools        |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-tools/blob/ign-tools1/Changelog.md)     |
|   ign-transport    |       9.x     |       [Changelog](https://github.com/ignitionrobotics/ign-transport/blob/ign-transport9/Changelog.md)      |
|   sdformat         |      10.x     |       [Changelog](https://github.com/osrf/sdformat/blob/sdf10/Changelog.md)        |

## Edifice (EOL)

1. New utility library with minimal dependencies: [Ignition Utils](https://github.com/ignitionrobotics/ign-utils/).
1. [Sky box support.](https://github.com/ignitionrobotics/ign-rendering/issues/98)
1. [Lightmap support.](https://github.com/ignitionrobotics/ign-gazebo/pull/471)
1. [Capsule and ellipsoid geometries.](https://github.com/osrf/sdformat/issues/376)
1. [SDF model composition.](https://github.com/osrf/sdformat/issues/278)
1. [SDFormat interface for non-SDF models.](http://sdformat.org/tutorials?tut=composition_proposal&cat=pose_semantics_docs&#1-5-minimal-libsdformat-interface-types-for-non-sdformat-models)
1. [Choose render order for overlapping polygons.](https://github.com/ignitionrobotics/ign-rendering/pull/188)
1. [Light visualization.](https://github.com/ignitionrobotics/ign-gazebo/issues/193)
1. [Spawn lights from the GUI.](https://github.com/ignitionrobotics/ign-gazebo/issues/119)
1. [Mecanum wheel controller.](https://github.com/ignitionrobotics/ign-gazebo/issues/579)
1. [Hydrodynamics.](https://ignitionrobotics.org/api/gazebo/5.0/classignition_1_1gazebo_1_1systems_1_1Hydrodynamics.html)
1. [Ocean currents.](https://github.com/ignitionrobotics/ign-gazebo/pull/800)
1. [Hook command line tool to binaries instead of libraries.](https://github.com/ignitionrobotics/ign-tools/issues/7)
1. [Heightmap support using Ogre 1 and DART.](https://github.com/ignitionrobotics/ign-gazebo/issues/237)
1. [Turn lights on and off.](https://github.com/ignitionrobotics/ign-gazebo/pull/1343)
1. [Toggle light visualization.](https://github.com/ignitionrobotics/ign-gazebo/issues/638)
1. [Model photoshoot plugin.](https://github.com/ignitionrobotics/ign-gazebo/pull/1331)

| Library name       | Version       | Changelog     |
| ------------------ |:-------------:|:-------------:|
|   ign-cmake        |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-cmake/blob/ign-cmake2/Changelog.md)     |
|   ign-common       |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-common/blob/ign-common4/Changelog.md)    |
|   ign-fuel-tools   |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-fuel-tools/blob/ign-fuel-tools6/Changelog.md)    |
|   ign-gazebo       |       5.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gazebo/blob/ign-gazebo5/Changelog.md)     |
|   ign-gui          |       5.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gui/blob/ign-gui5/Changelog.md)       |
|   ign-launch       |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-launch/blob/ign-launch4/Changelog.md)
|   ign-math         |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-math/blob/ign-math6/Changelog.md)
|   ign-msgs         |       7.x     |       [Changelog](https://github.com/ignitionrobotics/ign-msgs/blob/ign-msgs7/Changelog.md)
|   ign-physics      |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-physics/blob/ign-physics4/Changelog.md)
|   ign-plugin       |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-plugin/blob/ign-plugin1/Changelog.md)     |
|   ign-rendering    |       5.x     |       [Changelog](https://github.com/ignitionrobotics/ign-rendering/blob/ign-rendering5/Changelog.md)      |
|   ign-sensors      |       5.x     |       [Changelog](https://github.com/ignitionrobotics/ign-sensors/blob/ign-sensors5/Changelog.md)      |
|   ign-tools        |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-tools/blob/ign-tools1/Changelog.md)     |
|   ign-transport    |      10.x     |       [Changelog](https://github.com/ignitionrobotics/ign-transport/blob/ign-transport10/Changelog.md)      |
|   ign-utils        |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-utils/blob/ign-utils1/Changelog.md)      |
|   sdformat         |      11.x     |       [Changelog](https://github.com/osrf/sdformat/blob/sdf11/Changelog.md)        |

## Fortress

1. [Headless simulation using EGL.](https://github.com/ignitionrobotics/ign-rendering/issues/223)
1. [Refactor ECM::Each for performance.](https://github.com/ignitionrobotics/ign-gazebo/issues/711)
1. [Upgrade to Ogre 2.2.](https://github.com/ignitionrobotics/ign-rendering/issues/223)
1. [Improve `<pose>` tag on SDFormat.](https://github.com/osrf/sdformat/issues/252)
1. [Heightmaps on Ogre 2](https://github.com/ignitionrobotics/ign-rendering/issues/187)
1. [Spherical coordinates](https://github.com/ignitionrobotics/ign-gazebo/issues/981)
1. [Buoyancy engine](https://github.com/ignitionrobotics/ign-gazebo/blob/ign-gazebo6/examples/worlds/buoyancy_engine.sdf)
1. [Control lights from ROS 2](https://github.com/ignitionrobotics/ros_ign/pull/187)
1. [Python interface to Gazebo.](https://github.com/ignitionrobotics/ign-gazebo/issues/789)
1. [Custom shaders.](https://github.com/ignitionrobotics/ign-gazebo/issues/657)
1. [Visual plugins.](https://github.com/ignitionrobotics/ign-gazebo/issues/265)
1. [Rendering waves.](https://github.com/ignitionrobotics/ign-rendering/pull/541)
1. [Generic comms system.](https://github.com/ignitionrobotics/ign-gazebo/pull/1416)
1. [Wheel slip commands.](https://github.com/ignitionrobotics/ign-gazebo/pull/1241)
1. [USD importer / exporter.](https://github.com/ignitionrobotics/sdformat/tree/sdf12/examples/usdConverter)
1. [Bridge Ignition services to ROS 2 services.](https://github.com/ignitionrobotics/ros_ign/pull/211)
1. [Omniverse application](https://github.com/gazebosim/gz-omni)
1. [Pose and Twist with covariance.](https://github.com/ignitionrobotics/ign-msgs/pull/224)
1. Sensors
  1. [Custom sensors.](https://ignitionrobotics.org/api/sensors/6.0/custom_sensors.html)
  1. [Segmentation camera.](https://ignitionrobotics.org/api/sensors/6.0/segmentationcamera_igngazebo.html)
  1. [Joint force-torque sensor.](https://github.com/ignitionrobotics/ign-sensors/issues/25)
  1. [GPS / NavSat sensor.](https://github.com/ignitionrobotics/ign-sensors/issues/23)
  1. [Triggered cameras.](https://github.com/ignitionrobotics/ign-sensors/issues/185)
1. GUI features
    1. [Consolidate Scene3D with GzScene3D](https://github.com/ignitionrobotics/ign-gui/issues/137)
    1. [Visualize wireframes](https://github.com/ignitionrobotics/ign-gazebo/pull/816)
    1. [Visualize transparent](https://github.com/ignitionrobotics/ign-gazebo/pull/878)
    1. [Visualize inertia](https://github.com/ignitionrobotics/ign-gazebo/issues/111)
    1. [Visualize center of mass](https://github.com/ignitionrobotics/ign-gazebo/issues/110)
    1. [Visualize joints](https://github.com/ignitionrobotics/ign-gazebo/issues/106)
    1. [Orthographic view](https://github.com/ignitionrobotics/ign-gazebo/issues/103)
    1. [System inspector.](https://github.com/ignitionrobotics/ign-gazebo/issues/191)

| Library name       | Version       | Changelog     |
| ------------------ |:-------------:|:-------------:|
|   ign-cmake        |       2.x     |       [Changelog](https://github.com/ignitionrobotics/ign-cmake/blob/ign-cmake2/Changelog.md)     |
|   ign-common       |       4.x     |       [Changelog](https://github.com/ignitionrobotics/ign-common/blob/ign-common4/Changelog.md)    |
|   ign-fuel-tools   |       7.x     |       [Changelog](https://github.com/ignitionrobotics/ign-fuel-tools/blob/ign-fuel-tools7/Changelog.md)    |
|   ign-gazebo       |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gazebo/blob/ign-gazebo6/Changelog.md)     |
|   ign-gui          |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-gui/blob/ign-gui6/Changelog.md)       |
|   ign-launch       |       5.x     |       [Changelog](https://github.com/ignitionrobotics/ign-launch/blob/ign-launch5/Changelog.md)
|   ign-math         |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-math/blob/ign-math6/Changelog.md)
|   ign-msgs         |       8.x     |       [Changelog](https://github.com/ignitionrobotics/ign-msgs/blob/ign-msgs8/Changelog.md)
|   ign-physics      |       5.x     |       [Changelog](https://github.com/ignitionrobotics/ign-physics/blob/ign-physics5/Changelog.md)
|   ign-plugin       |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-plugin/blob/ign-plugin1/Changelog.md)     |
|   ign-rendering    |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-rendering/blob/ign-rendering6/Changelog.md)      |
|   ign-sensors      |       6.x     |       [Changelog](https://github.com/ignitionrobotics/ign-sensors/blob/ign-sensors6/Changelog.md)      |
|   ign-tools        |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-tools/blob/ign-tools1/Changelog.md)     |
|   ign-transport    |      11.x     |       [Changelog](https://github.com/ignitionrobotics/ign-transport/blob/ign-transport11/Changelog.md)      |
|   ign-utils        |       1.x     |       [Changelog](https://github.com/ignitionrobotics/ign-utils/blob/ign-utils1/Changelog.md)      |
|   sdformat         |      12.x     |       [Changelog](https://github.com/osrf/sdformat/blob/sdf12/Changelog.md)        |


