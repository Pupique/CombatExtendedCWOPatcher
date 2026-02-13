# CombatExtended - Core Weapons Only Patcher
Patcher for CE, CE Armory and CE Guns

## Purpose

Whilst playing Rimworld with only Combat Extended, it's noticeable that many calibers from multiple technology levels are left out without their respective weapons, sometimes leaving out entirely hollow technologies such as Gunpowder without any weapons and a lackluster Spacer charged weapon technology with no variety.

To rectify that and use up most of the available calibers, CE Armory and CE Guns become necessary mods. However, I personally have two reasons why I wouldn't like to use these two mods to their fullest extent:

1) Nomenclature
Even though I appreciate the intent to make real-life equivalents in Rimworld, I prefer the Vanilla nomenclature since, to me, it's more reasonable to see "Assault Rifle" over "M16A4" as what the weapon does is more important than its particular model.

Additionally, I enjoy Rimworld's Vanilla generic naming system so I made this patcher to maintain such conformity.

2) Redundant Industrial-level Weapons and Calibers
This was the biggest reason for my reluctance to use CE Armory and CE Guns. The Industrial tech level already has the largest variety of weapons in the Vanilla experience and the two mods expand it even further, therefore becoming redundant in my opinion. This patcher excludes most of these cases in an attempt to flatten the Industrial weapon and caliber variety when compared to its Spacer counterparts.

### Disclaimer

Originally, my intention was to rip the missing weapons (as per explained in section 1) in a separate, independent fork. The issue is that whatever tweaks done by the CE team naturally wouldn't transmit to the intended mod, forcing me to tweak them the same. Therefore, I had the idea to make this patcher, keeping up-to-date with whatever the CE team does while attaining this mod's two main purposes.

> [!NOTE]
> Despite not having any CE mod as a dependency, this patcher requires any combination of them to take effect as it does nothing by itself.

## Applied Patches

Below is the list of patches that were applied:

### Renamed Weapons

| ID | Source | Name | Renamed To |
| --- | --- | --- | --- |
| Turret_KPV | CE | KPV | HMG Emplacement |
| Turret_M240B | CE | M240B | MMG Emplacement |
| Turret_AGSThirty | CE | AGS-30 | LGL Emplacement |
| CE_Gun_RPGSeven | CE Guns | RPG-7 | Rocket Launcher |
| CE_Gun_MilkorMGL | CE Guns | Milkor MGL | Multiple Grenade Launcher |
| CE_Gun_ChargePistol | CE Guns | P-6 | Charge Pistol |
| CE_Gun_ChargeShotgun | CE Guns | S-12 | Charge Shotgun |
| CE_Gun_ChargeSMG | CE Guns | S-6 | Charge SMG |
| CE_Gun_ChargeSniperRifle | CE Guns | R-8 | Charge Sniper Rifle |
| CE_Gun_ChargeLMG | CE Guns | L-8 | Charge LMG |
| CE_Gun_ChargeAMR | CE Guns | A-12 | Charge AMR |
| CE_Gun_Flamethrower | CE Guns | RM2 | Flamethrower |
| CE_Turret_MkNineteenGL | CE Armory | Mk 19 Grenade Launcher | HGL Emplacement |
| CE_Turret_SPGNine | CE Armory | SPG-9 Recoilless Gun | Rocket Launcher Emplacement |
| CE_Turret_Vickers | CE Armory | Vickers Machine Gun | LMG Emplacement |
| CE_Gun_CarlGustaf | CE Armory | Carl Gustaf | AT Recoilless Rifle |
| CE_Gun_LaserCarbine | CE Armory | LAS-40C | Laser Carbine |

### Undone Renames

> [!NOTE]
> Unfortunately, Rimworld doesn't allow for resetting an object's attribute (eg. name) to default, which is what was meant to be done here. Therefore, the weapons' names had to be literally re-set to their English counterparts, breaking whatever localization the base game had.

| ID | Source | Name | Original Weapon |
| --- | --- | --- | --- |
| Gun_Revolver | CE Guns | Ruger Redhawk | Revolver |
| Gun_Autopistol | CE Guns | M1911 | Autopistol |
| Gun_PumpShotgun | CE Guns | Mossberg 500 | Pump Shotgun |
| Gun_ChainShotgun | CE Guns | Saiga 12K | Chain Shotgun |
| Gun_BoltActionRifle | CE Guns | Lee-Enfield | Bolt-Action Rifle |
| Gun_AssaultRifle | CE Guns | M16A4 | Assault Rifle |
| Gun_SniperRifle | CE Guns | M24 | Sniper Rifle |
| Gun_MachinePistol | CE Guns | MAC-10 | Machine Pistol |
| Gun_HeavySMG | CE Guns | UMP45 | Heavy SMG |
| Gun_IncendiaryLauncher | CE Guns | T-9 | Incendiary Launcher |
| Gun_LMG | CE Guns | Bren Mk4 | LMG |
| Gun_ChargeRifle | CE Guns | R-6 | Charge Rifle |
| CE_Gun_GrenadeLauncher | CE + CE Guns | M79 | Grenade Launcher |
| CE_DisposableRocketLauncher | CE + CE Guns | M72 LAW | Disposable Rocket Launcher |

### Removed Weapons

| ID | Source | Caliber | Name |
| --- | --- | --- | --- |
| CE_Gun_SWGovernor | CE Guns | .45/.410 Bore | S&W Governor |
| CE_Gun_WinchesterNintyFour | CE Guns | .44 Magnum | Winchester 94 |
| CE_Gun_USASTwelve | CE Guns | 12 Gauge | USAS-12 |
| CE_Gun_SigMCX | CE Guns | 5.56x45mm NATO | SIG MCX |
| CE_Gun_AKMSU | CE Guns | 7.62x39mm Soviet | AKMS-U |
| CE_Gun_FNFAL | CE Guns | 7.62x51mm NATO | FN FAL |
| CE_Gun_MiniFourteen | CE Guns | 5.56x45mm NATO | Ruger Mini-14 |
| CE_Gun_SKS | CE Guns | 7.62x39mm Soviet | SKS |
| CE_Gun_AKM | CE Guns | 7.62x39mm Soviet | AKM |
| CE_Gun_SVD | CE Guns | 7.62x54mmR | SVD |
| CE_Gun_HecateTwo | CE Guns | .50 BMG | Hecate II |
| CE_Gun_PTRS | CE Guns | 14.5x14mm | PTRS-41 |
| CE_Gun_MTwoFourNine | CE Guns | 5.56x45mm NATO | M249 |
| CE_Gun_MSixty | CE Guns | 7.62x51mm NATO | M60E6 |
| CE_Gun_RPD | CE Guns | 7.62x39mm Soviet | RPD |
| CE_Gun_PKM | CE Guns | 7.62x54mmR | PKM |
| CE_Turret_M2HB | CE Armory | .50 BMG | M2 Browning Machine Gun |
| CE_Turret_M1919Browning | CE Armory | .30-06 Springfield | M1919 Machine Gun |
| CE_Turret_PKM | CE Armory | 7.62x54mmR | PKM Machine Gun |
| CE_Gun_AKTwelve | CE Armory | 5.45x39mm Soviet | AK-12 |
| CE_Gun_AK74GL | CE Armory | 5.45x39mm Soviet | AK-74 + GP-25 |
| CE_Gun_AKSSeventyFourU | CE Armory | 5.45x39mm Soviet | AKS-74U |
| CE_Gun_AmericanOneEighty | CE Armory | .22 LR | American-180 |
| CE_ATFour | CE Armory | Single-Use | AT-4 |
| CE_Gun_AVB | CE Armory | 7.62x54mmR | AVB-7.62 |
| CE_Gun_BAR | CE Armory | .30-06 Springfield | Browning Automatic Rifle |
| CE_Gun_BoysRifle | CE Armory | .50 BMG | Boys Anti-Tank Rifle |
| CE_Gun_Deagke | CE Armory | .44 Magnum | Desert Eagle |
| CE_Gun_DPtwentySeven | CE Armory | 7.62x54mmR | DP-27 |
| CE_Gun_FightLiteMCR | CE Armory | 5.56x45mm NATO | FightLite MCR |
| CE_Gun_FNFiveSeven | CE Armory | FN 5.7x28mm | Five-seveN |
| CE_Gun_PNinety | CE Armory | FN 5.7x28mm | P90 |
| CE_Gun_BigBoy | CE Armory | .45 Colt | Henry Big Boy |
| CE_Gun_HenrySideGate | CE Armory | .410 Bore | Henry Side Gate |
| CE_Gun_Jericho | CE Armory | 9x19mm Para Subsonic | Jericho 941 |
| CE_Gun_KelTecCPThirtyThree | CE Armory | .22 LR | KelTec CP33 |
| CE_Gun_KSTwentyThree | CE Armory | 23x75mmR Shell | KS-23 |
| CE_Gun_Lewis | CE Armory | .30-06 Springfield | Lewis Gun |
| CE_Gun_M1Garand | CE Armory | .30-06 Springfield | M1 Garand |
| CE_Gun_MSeven | CE Armory | .277 Fury | M7 |
| CE_Gun_MTwoFifty | CE Armory | .277 Fury | M250 |
| CE_Gun_M1903Springfield | CE Armory | .30-06 Springfield | M1903 Springfield |
| CE_Gun_M1917Enfield | CE Armory | .30-06 Springfield | M1917 Enfield |
| CE_Gun_MadsenLMG | CE Armory | 7.62x51mm NATO | Madsen Machine Gun |
| CE_Gun_MGThreeThreeEight | CE Armory | .338 Norma Magnum | MG 338 |
| CE_Gun_MicroUzi | CE Armory | 9x19mm Para Subsonic | Micro Uzi |
| CE_Gun_MosinNagant | CE Armory | 7.62x54mmR | Mosin-Nagant |
| CE_Gun_MosqueFAL | CE Armory | 7.62x51mm NATO | MosqueFAL |
| CE_Gun_RPKSixteen | CE Armory | 5.45x39mm Soviet | RPK-16 |
| CE_Gun_SawedOff | CE Armory | 12 Gauge | Sawed-Off Shotgun |
| CE_Gun_SRTweintyFive | CE Armory | 7.62x51mm NATO | SR-25 |
| CE_Gun_SRS | CE Armory | .338 Norma Magnum | SRS |
| CE_Gun_KordPortable | CE Armory | .50 BMG | Kord 6P50 Machine Gun |
| CE_Gun_TacFifty | CE Armory | .50 BMG | Tac-50 |
| CE_Gun_TaurusJudge | CE Armory | .45 Colt/.410 Bore Shell | Taurus Judge |
| CE_Gun_TavorSeven | CE Armory | 7.62x51mm NATO | Tavor 7 |
| CE_Gun_Uzi | CE Armory | 9x19mm Para Subsonic | Uzi |
| CE_Gun_WinchesterEightySix | CE Armory | .45-70 Govt. | Winchester Model 1886 |

### Removed Apparel

Even though slimming down apparel is not the main purpose of this mod, reducing redundancy/bloat also applies to them.

| ID | Source | Name |
| --- | --- | --- |
| CE_Apparel_AssaultShield | CE Armory | Assault Shield |
| CE_Apparel_Buckler | CE Armory | Buckler |
| CE_Apparel_Pavise | CE Armory | Pavise |
| CE_Apparel_WickerShield | CE Armory | Wicker Shield |
| CE_Apparel_CompositeArmor | CE Armory | Composite Armor |
| CE_Apparel_Gorka | CE Armory | Gorka Combat Bodysuit |

### Removed Melee Weapons

Although most of the melee weapons that were removed are of Medieval tech level, they are virtually similar to their Vanilla counterparts, therefore justifying their removal in my opinion.

| ID | Source | Name |
| --- | --- | --- |
| CE_Melee_BecDeCorbin | CE Armory | Bec de Corbin |
| CE_Melee_Machete | CE Armory | Machete |
| CE_Melee_Pollaxe | CE Armory | Pollaxe |
| CE_Melee_QuarterStaff | CE Armory | Quarterstaff |
| CE_Melee_Saber | CE Armory | Saber |

### Changed Calibers

For simplicity's sake, some of the weapons' calibers were changed to consolidate already existing calibers of similar power.

| ID | Source | Name | Old Caliber | New Caliber |
| --- | --- | --- | --- | --- |
| CE_Gun_GatlingGun | CE Armory | Gatling Gun | .45-70 Govt. | .44 Magnum[^1] |
| CE_Gun_MkNineteenGL | CE Armory | HGL Emplacement | 40x53mm Grenades | 40x46mm Grenades |

## Closing Notes

This mod was primarily done due to personal preference but I chose to publish it anyways in case that someone else had the same thoughts that I did. You're free to fork it in any way you wish or even contribute to this repository directly - just ask me first if you intend to do so.

### Technical

This patcher is entirely built on whatever CE, CE Guns and CE Armory implements. No item IDs were changed so this patcher can be safely removed if you intend to use said mods without it.

> [!Caution]
> Even though removing this mod mid-game won't affect your save negatively, APPLYING it might since it removes multiple items from the game.

> [!Note]
> Should be loaded after Combat Extended, Combat Extended Guns and Combat Extended Armory.

### Credits

All credits go to the Combat Extended team for creating the core mod itself and all the weapons that were referenced by this patcher.

#### Referenced Repositories
Combat Extended: https://github.com/CombatExtended-Continued/CombatExtended
Combat Extended Guns: https://github.com/CombatExtended-Continued/CombatExtendedGuns
Combat Extended Armory: https://github.com/CombatExtended-Continued/CombatExtendedArmory

### License
This mod falls under the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/) and may only be shared or modified under the specified terms.

[^1]: Although the .44 Magnum is mostly a revolver-only caliber, I personally found it the best match with the Gatling Gun since the machine gun emplacement above it (Vickers/LMG Emplacement) uses the .303 British, which was the Gatling Gun's most likely caliber that I had idealized. In order to maintain uniqueness among the different emplacements, I downgraded the Gatling Gun to use the .44 Magnum while also expanding said caliber's usage.
