<div align="center">
  <img width="50" height="50" alt="cssharp" src="https://github.com/user-attachments/assets/3393573f-29be-46e1-bc30-fafaec573456" />
	<h3><strong>Killfeed Icons</strong></h3>
	<h4>a plugin to customize the killfeed icons</h4>
	<h2>
		<img src="https://img.shields.io/github/downloads/exkludera-cssharp/killfeed-icons/total" alt="Downloads">
		<img src="https://img.shields.io/github/stars/exkludera-cssharp/killfeed-icons?style=flat&logo=github" alt="Stars">
		<img src="https://img.shields.io/github/forks/exkludera-cssharp/killfeed-icons?style=flat&logo=github" alt="Forks">
		<img src="https://img.shields.io/github/license/exkludera-cssharp/killfeed-icons" alt="License">
	</h2>
	<!--<a href="https://discord.gg" target="_blank"><img src="https://img.shields.io/badge/Discord%20Server-7289da?style=for-the-badge&logo=discord&logoColor=white" /></a> <br>-->
	<a href="https://ko-fi.com/exkludera" target="_blank"><img src="https://img.shields.io/badge/KoFi-af00bf?style=for-the-badge&logo=kofi&logoColor=white" alt="Buy Me a Coffee at ko-fi.com" /></a>
	<a href="https://paypal.com/donate/?hosted_button_id=6AWPNVF5TLUC8" target="_blank"><img src="https://img.shields.io/badge/PayPal-0095ff?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal"  /></a>
	<a href="https://github.com/sponsors/exkludera" target="_blank"><img src="https://img.shields.io/badge/Sponsor-696969?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Sponsor" /></a>
</div>

> [!WARNING]
> add `"include" "panorama/images/icons/equipment"` at the bottom of gameinfo.gi before uploading addon
>
> also don't forget to remove it when you're done or you wont be able to join servers

to make your own icon you have to upload a .svg file to that path in your addon <br>
`"Icon": "YOUR-ICON"` = content/your-addon/panorama/images/icons/equipment/YOUR-ICON.svg

### Requirements
- [MetaMod](https://github.com/alliedmodders/metamod-source)
- [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp)

## Showcase
<details>
	<summary>content</summary>
  <img src="https://github.com/user-attachments/assets/db91d07e-2550-4bf2-b5c2-e4a0f4002873" width="150">
  <details>
<summary>list of cs2 icons & weapon names</summary>
ak47<br>
ammobox<br>
ammobox_threepack<br>
armor<br>
armor_helmet<br>
assaultsuit<br>
assaultsuit_helmet_only<br>
aug<br>
awp<br>
axe<br>
bayonet<br>
bizon<br>
breachcharge<br>
breachcharge_projectile<br>
bumpmine<br>
c4<br>
clothing_hands<br>
controldrone<br>
customplayer<br>
cz75a<br>
deagle<br>
decoy<br>
defuser<br>
disconnect<br>
diversion<br>
dronegun<br>
elite<br>
famas<br>
firebomb<br>
fists<br>
fiveseven<br>
flair0<br>
flashbang<br>
flashbang_assist<br>
frag_grenade<br>
g3sg1<br>
galilar<br>
glock<br>
grenadepack<br>
grenadepack2<br>
hammer<br>
healthshot<br>
heavy_armor<br>
hegrenade<br>
helmet<br>
hkp2000<br>
incgrenade<br>
inferno<br>
kevlar<br>
knife<br>
knife_bowie<br>
knife_butterfly<br>
knife_canis<br>
knife_cord<br>
knife_css<br>
knife_falchion<br>
knife_flip<br>
knife_gut<br>
knife_gypsy_jackknife<br>
knife_karambit<br>
knife_kukri<br>
knife_m9_bayonet<br>
knife_outdoor<br>
knife_push<br>
knife_skeleton<br>
knife_stiletto<br>
knife_survival_bowie<br>
knife_t<br>
knife_tactical<br>
knife_twinblade<br>
knife_ursus<br>
knife_widowmaker<br>
knifegg<br>
m4a1<br>
m4a1_silencer<br>
m4a1_silencer_off<br>
m249<br>
mac10<br>
mag7<br>
melee<br>
molotov<br>
mp5sd<br>
mp7<br>
mp9<br>
negev<br>
nova<br>
p90<br>
p250<br>
p2000<br>
planted_c4<br>
planted_c4_survival<br>
prop_exploding_barrel<br>
radarjammer<br>
revolver<br>
sawedoff<br>
scar20<br>
sg556<br>
shield<br>
smokegrenade<br>
snowball<br>
spanner<br>
spray0<br>
ssg08<br>
stomp_damage<br>
tablet<br>
tagrenade<br>
taser<br>
tec9<br>
tripwirefire<br>
tripwirefire_projectile<br>
ump45<br>
usp_silencer<br>
usp_silencer_off<br>
xm1014<br>
zone_repulsor<br>
</details>

can be found in `game/csgo/panorama/images/icons/equipment` with [Source2 Viewer](https://valveresourceformat.github.io/) <br>
</details>

## Config

<details>
<summary>Killfeed_Icons.json</summary>

Default: `0` (0 = default, 1 = force enable, 2 = force disable)

```json
{
  "Headshot": 0,
  "ThroughSmoke": 0,
  "NoScope": 0,
  "AssistedFlash": 0,
  "AttackerBlind": 0,
  "AttackerInAir": 0,
  "Penetrated": 0,
  "Dominated": 0,
  "SquadWipe": 0,
  "Icons": {
    "knife": {
      "Icon": "prop_exploding_barrel"
    },
    "awp": {
      "Icon": "dronegun",
      "Permission": ["@css/reservation", "#css/vip"],
      "Team": "T"
    },
    "*": {
      "Icon": "movelinear"
    }
  }
}
```
</details>
