# Center Section

The center area of the right console contains IFF and lighting controls.

## IFF Control Panel

![IFF](../../../img/IFF.jpg)

As opposed to the Interrogator panel in the WSO cockpit, this panel provides
the pilot with the ability to adjust the IFF sender of the own aircraft.
Which would then be picked up by interrogators in other aircraft.

>💡 Due to DCS limitations, this is not simulated in-game.

For further explanation see
the [IFF System controls chapter](../../../systems/identification_systems.md#iff-controls-and-indicators).

## DCU-94A Stores Control-Monitor Panel

![DCU94](../../../img/DCU94.jpg)

This panel is used to control and test the separate release circuit system for
nuclear stores.

Nuclear stores are separated from the regular release system to prevent
accidental release. This is not simulated in-game.

## Temperature Control

![PilTemp](../../../img/PilTemp.jpg)

The knob can be used with the switch in the AUTO position and
allows the pilot to set the temperature inside both cockpits
from COLD to HOT for crew comfort.

Should the AUTO system fail, the switch can be placed in either
a manual mode.

The center position of the switch turns the system off.

## Cockpit Lighting Control Panel

![PilCockLights](../../../img/PilCockLights.jpg)

The Cockpit Lighting Control Panel provides control of all panel edge lighting,
flight instrument panel lighting, the console floodlights, the white floodlights
found under the canopy sill over each console, and also includes the Warning
Light Test/Standby Compass Light switch.

For further information about lighting see
the [lighting chapter.](../../../systems/lighting.md#interior-lighting)

### White Floodlight

The White Floodlight switch acts independent of all other controls on the panel,
and is either ON or OFF. It activates a separate emergency floodlight (also
called Thunderstorm Light) that illuminates the cockpit in white. The lamp is
energized through the Battery Bus to ensure it is always operational, even in
case of total power loss. Do not forget to turn off the light before parking the
aircraft for a longer time, as it will otherwise drain the battery.

### Instrument Panel Knob

The Flight Instrument Light Knob (marked INSTR PANEL), when moved to the right
of the OFF detent, controls illumination of the following six instrument lights
in unison:

- [Airspeed/Mach Indicator](../../pilot/flight_director_group.md#airspeed-and-mach-indicator)
- [Attitude Director Indicator](../../pilot/flight_director_group.md#attitude-director-indicator)
- [Angle of Attack Indicator](../../pilot/flight_director_group.md#angle-of-attack-indicator)
- [Vertical Velocity Indicator](../../pilot/flight_director_group.md#vertical-velocity-indicator)
- [Altimeter](../../pilot/flight_director_group.md#altimeter)
- [Horizontal Situation Indicator](../../pilot/flight_director_group.md#horizontal-situation-indicator)

When in the OFF position, these indicators are independently controlled for
illumination by the knobs on the Flight Instrument Lights Intensity Panel.

### Console Knob

The Console Light Control Knob, with range from OFF to BRT, controls
illumination level for all panel edge lighting and the console floodlights.

### Console Floodlight

The red console floodlights (CONSOLE FLOOD) are triggered independently of the knob
when it is placed to the right of the OFF detent position, and offer three
settings - DIM, MED, or BRT. The floodlights will remain on until the Console
Light Control knob is returned to the OFF position, and the floodlight switch is
placed in DIM. All three positions are powered by different buses to ensure
maximal availability:

| Lamp   | Bus                   |
|--------|-----------------------|
| Bright | Essential 28V DC Bus  |
| Medium | Left Main 14V AC Bus  |
| Dim    | Left Main 115V AC Bus |

### Warning Light Test Switch

The Warning Light Test Switch (Marked WARN LT TEST) is a three-position switch;
in the WARN LT TEST position, confirms function of the various emergency
indicators in the cockpit. In the STBY COMP position, it illuminates the light
for the [Standby Compass.](../../pilot/overhead_indicators.md#standby-magnetic-compass) Both
functions are deactivated when the switch is placed in the OFF position.