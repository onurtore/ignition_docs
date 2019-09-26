# Gazebo Classic to Ignition migration guide

This guide is designed to help you move your models, worlds, and plugins
from Gazebo Classic to Ignition. We will use the term Gazebo Classic to
refer to any version of Gazebo that derives from the `osrf/gazebo` code
repository. Ignition refers to code that derives from the [Ignition Robotics
libraries](https://ignitionrobotics/libs).

Gazebo Classic is transitioning to maintenance only, and all new simulation development will take place in Ignition. The latest release of Gazebo, version 11 planned for Jan 2020, will have an EOL date in 2025. This five-year window should allow ample time to migrate from Gazebo Classic to Ignition.

## Migrating an SDF model

This section deals with migrating simulation models defined using SDF. Not
covered are SDF parameters for worlds, nor plugins associated with a model.

Ignition utilizes the same [SDF](https://sdformat.org) file
format as Gazebo Classic. A model that loads in Gazebo Classic will also
load in Ignition. The exception to this rule is any feature implemented in
Gazebo Classic that has not, yet, been implemented in Ignition. Any SDF
feature not implemented in Ignition should fail gracefully, but may result
in unexpected or incorrect simulation behavior.  Use the following SDF compatibility table to track which features are implemented in Ignition.

TODO(Addisu - drop in notes here).

## Migrating an SDF world

Todo

## Migrating a Plugin

Todo
