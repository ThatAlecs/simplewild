**Overview**

SimpleWild adds a /wild command to Uberbukkit/Craftbukkit 1060 for versions prior to Minecraft beta 1.7.3

**Features:**

**Random Teleportation:** Players can use the /wild command to teleport to a random location within the defined coordinate ranges.

**Safety Precautions:** The plugin ensures safe teleportation by evaluating the Y level and avoiding hazardous spawn locations.

**Cooldown System:** To prevent abuse, a cooldown system is implemented to limit the frequency of teleportation.

**Configuration:** The plugin offers a configuration file (config.properties) that allows server administrators to customize various aspects:

**coordinateXRange:** Specifies the range of X coordinates for random teleportation.

**coordinateZRange:** Specifies the range of Z coordinates for random teleportation.

**minimumYLevel:** Sets the minimum Y level required for a safe teleportation spot.

**cooldownDuration:** Defines the duration of the cooldown period in seconds between teleportations.

PERMISSION NODE: simplewild.wild (should be enabled by default)


TLDR: it's a simple /wild command with a config file
