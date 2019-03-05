# Feature comparison

A list of features present in [Gazebo-classic](https://bitbucket.org/osrf/gazebo/) and
the status of their migration to [Ignition](https://ignitionrobotics.org/).

## Sensors

Sensor | Gazebo-classic | Ignition Gazebo
-- | -- | --
Altimeter | :heavy_check_mark: | :heavy_check_mark:
Camera | :heavy_check_mark: | :heavy_check_mark:
Contact sensor | :heavy_check_mark: | :heavy_check_mark:
Depth camera | :heavy_check_mark: | :heavy_check_mark:
Force-torque | :heavy_check_mark: |
GPS | :heavy_check_mark: |
GPU Ray | :heavy_check_mark: | :heavy_check_mark: Renamed to GPU Lidar
IMU | :heavy_check_mark: | :heavy_check_mark:
Logical camera | :heavy_check_mark: | :heavy_check_mark:
Magnetometer | :heavy_check_mark: | :heavy_check_mark:
Multi-camera | :heavy_check_mark: |
Ray | :heavy_check_mark: |
RFID | :heavy_check_mark: |
RFIDTag | :heavy_check_mark: |
Sonar | :heavy_check_mark: |
Wide-angle camera | :heavy_check_mark: |
Wireless receiver | :heavy_check_mark: |
Wireless transceiver | :heavy_check_mark: |
Wireless transmitter | :heavy_check_mark: |

## Plugins

Plugin | Gazebo-classic | Ignition Gazebo
-- | -- | --
ActorPlugin | :heavy_check_mark: |
ActuatorPlugin | :heavy_check_mark: |
AmbientOcclusionVisualPlugin | :heavy_check_mark: |
ArduCopterPlugin | :heavy_check_mark: |
ArrangePlugin | :heavy_check_mark: |
AttachLightPlugin | :heavy_check_mark: | :heavy_multiplication_x: Does not apply, use SDF
BlinkVisualPlugin | :heavy_check_mark: |
BreakableJointPlugin | :heavy_check_mark: |
BuoyancyPlugin | :heavy_check_mark: |
CameraPlugin | :heavy_check_mark: |
CartDemoPlugin | :heavy_check_mark: |
CessnaPlugin | :heavy_check_mark: |
ContactPlugin | :heavy_check_mark: |
ContainPlugin | :heavy_check_mark: |
DepthCameraPlugin | :heavy_check_mark: |
DiffDrivePlugin | :heavy_check_mark: | :heavy_check_mark:
FiducialCameraPlugin | :heavy_check_mark: |
FlashLightPlugin | :heavy_check_mark: |
FollowerPlugin | :heavy_check_mark: |
ForceTorquePlugin | :heavy_check_mark: |
GimbalSmall2dPlugin | :heavy_check_mark: |
GpuRayPlugin | :heavy_check_mark: |
HarnessPlugin | :heavy_check_mark: |
HeightmapLODPlugin | :heavy_check_mark: |
ImuSensorPlugin | :heavy_check_mark: |
InitialVelocityPlugin | :heavy_check_mark: |
JointControlPlugin | :heavy_check_mark: |
JointTrajectoryPlugin | :heavy_check_mark: |
KeysToJointsPlugin | :heavy_check_mark: |
LedPlugin | :heavy_check_mark: |
LensFlareSensorPlugin | :heavy_check_mark: |
LiftDragPlugin | :heavy_check_mark: |
LinearBatteryConsumerPlugin | :heavy_check_mark: |
LinearBatteryPlugin | :heavy_check_mark: |
LinkPlot3DPlugin | :heavy_check_mark: |
ModelPropShop | :heavy_check_mark: |
MudPlugin | :heavy_check_mark: |
PlaneDemoPlugin | :heavy_check_mark: |
PressurePlugin | :heavy_check_mark: |
RayPlugin | :heavy_check_mark: |
RaySensorNoisePlugin | :heavy_check_mark: |
RubblePlugin | :heavy_check_mark: |
ShaderParamVisualPlugin | :heavy_check_mark: |
SkidSteerDrivePlugin | :heavy_check_mark: |
SonarPlugin | :heavy_check_mark: |
SphereAtlasDemoPlugin | :heavy_check_mark: |
StaticMapPlugin | :heavy_check_mark: |
StopWorldPlugin | :heavy_check_mark: |
TouchPlugin | :heavy_check_mark: | :heavy_check_mark:
VehiclePlugin | :heavy_check_mark: |
WheelSlipPlugin | :heavy_check_mark: |
WindPlugin | :heavy_check_mark: |
ElevatorPlugin | :heavy_check_mark: |
RandomVelocityPlugin | :heavy_check_mark: |
TransporterPlugin | :heavy_check_mark: |
HydraPlugin | :heavy_check_mark: |
HydraDemoPlugin | :heavy_check_mark: |
JoyPlugin | :heavy_check_mark: | :heavy_check_mark: Migrated as standalone program
CessnaGUIPlugin | :heavy_check_mark: |
KeyboardGUIPlugin | :heavy_check_mark: |
LookAtDemoPlugin | :heavy_check_mark: |
TimerGUIPlugin | :heavy_check_mark: |
GravityCompensationPlugin | :heavy_check_mark: |




