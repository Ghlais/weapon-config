# SA-MP Weapon Configuration Modifications

## Overview

This repository contains modifications to the weapon configurations for the San Andreas Multiplayer (SA-MP) game server. The adjustments aim to enhance the gameplay experience by making the weapons' behavior more realistic. These changes include modifying damage application, weapon ranges, shooting rates, and damage distribution between health and armour.

## Author

Ghlais Dev

## Modifications

### 1. Weapon Ranges

Updated the range values for all weapons to provide a more realistic representation of their effective ranges in real-life scenarios. The changes reflect the practical use of each weapon, ensuring a more immersive gaming experience.

### 2. Shooting Rates

Modified the fastest possible gap between weapon shots in milliseconds to simulate realistic firing rates for each weapon type. This adjustment balances the gameplay by reflecting the actual capabilities of different weapons.

### 3. Damage Distribution

Configured whether the damage is applied directly to health or distributed between health and armour. Additionally, specified if these rules apply only to the torso. These changes make the combat mechanics more realistic and challenging.

## Detailed Changes

### Weapon Ranges

- **Fist, Brass knuckles, Golf club, Nitestick, Knife, Bat, Shovel, Pool cue, Katana, Chainsaw, Dildo, Vibrator, Flowers, Cane:** Adjusted to reflect realistic melee ranges.
- **Grenade, Teargas, Molotov:** Set ranges for throwable weapons.
- **Vehicle M4, Vehicle minigun:** Custom weapon ranges set to reflect their mounted capabilities.
- **Pistols (Colt 45, Silenced, Deagle), Shotguns (Shotgun, Sawed-off, Spas), SMGs (UZI, MP5, Tec9), Rifles (AK47, M4, Sniper), Heavy Weapons (Rocket launcher, Heatseeker, Flamethrower, Minigun):** Updated to reflect realistic firing ranges.

### Shooting Rates

- **Fist, Brass knuckles, Melee weapons (Golf club, Nitestick, Knife, Bat, Shovel, Pool cue, Katana, Chainsaw, Dildo, Vibrator, Flowers, Cane):** Adjusted to reflect realistic melee attack speeds.
- **Grenade, Teargas, Molotov:** Set firing rates for throwable weapons.
- **Vehicle M4, Vehicle minigun:** Custom firing rates set for mounted weapons.
- **Pistols (Colt 45, Silenced, Deagle), Shotguns (Shotgun, Sawed-off, Spas), SMGs (UZI, MP5, Tec9), Rifles (AK47, M4, Sniper), Heavy Weapons (Rocket launcher, Heatseeker, Flamethrower, Minigun):** Updated to reflect realistic shooting rates.

### Damage Distribution

- **Fist, Brass knuckles, Melee weapons (Golf club, Nitestick, Knife, Bat, Shovel, Pool cue, Katana, Chainsaw, Dildo, Vibrator, Flowers, Cane):** Configured to distribute damage between health and armour.
- **Grenade, Teargas, Molotov, Heavy Weapons (Rocket launcher, Heatseeker, Flamethrower, Minigun):** Set to apply damage directly to health.
- **Vehicle M4, Vehicle minigun, Pistols (Colt 45, Silenced, Deagle), Shotguns (Shotgun, Sawed-off, Spas), SMGs (UZI, MP5, Tec9), Rifles (AK47, M4, Sniper):** Configured to apply damage directly to health, with some applying only to the torso.

## **INSTALLATION**

To apply these modifications to your SA-MP server, follow these steps:

1. **Download the `weapon-config.inc` file.**
2. **Open your server files.**
3. **Navigate to the `pawno` folder.**
4. **Open the `include` folder.**
5. **Paste the `weapon-config.inc` file inside the `include` folder.**
6. **Restart your SA-MP server to apply the changes.**

## Supported Weapons, Vehicles, and Aircraft

### Weapons

- **Melee Weapons:** Fist, Brass knuckles, Golf club, Nitestick, Knife, Bat, Shovel, Pool cue, Katana, Chainsaw, Dildo, Vibrator, Flowers, Cane
- **Throwable Weapons:** Grenade, Teargas, Molotov
- **Pistols:** Colt 45, Silenced, Deagle
- **Shotguns:** Shotgun, Sawed-off, Spas
- **SMGs:** UZI, MP5, Tec9
- **Rifles:** AK47, M4, Sniper
- **Heavy Weapons:** Rocket launcher, Heatseeker, Flamethrower, Minigun

### Vehicles

- **Mounted Weapons:** Vehicle M4 (custom), Vehicle minigun (custom)
- **Armoured Vehicles:** Rhino (Tank), Barracks
- **Cars and Bikes:** All standard in-game vehicles with custom weapon attachments

### Aircraft

- **Planes:** Hydra, Rustler, Hunter (Helicopter), Sea Sparrow
- **Helicopters:** Annihilator, Buzzard, Hunter

## Contributing

If you have suggestions for improvements or additional modifications, feel free to fork this repository and submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Ghlais Dev

Making SA-MP a more realistic and immersive experience, one configuration at a time.

---
