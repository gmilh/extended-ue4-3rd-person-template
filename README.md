# extended-ue4-3rd-person-template
An extended third person games template for Unreal Engine 4


I made this template to quickly set up new third person projects in UE4, without having to re-implement certain standard systems on each new project.
- actor components handling hit points, stamina, and similar systems
- integrated solution to handle dynamic camera parameters (e.g.: extending camera FOV when character is in the air, zooming in/out when aiming, etc.)
- a basic modular framework to handle melee weapons and combo attacks

Unlike the default UE4 third person template, this does not include the UE4 Mannequin skeletal mesh and related animation blueprint, as minimise unwanted pre-existing visual assets in a new project.
