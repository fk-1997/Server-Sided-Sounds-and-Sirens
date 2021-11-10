# Server Sided Sounds and Sirens
 
We wanted custom sirens, many custom sirens.

How many? 214. Why? Nobody knows.
 
 
But after we finally managed it to do it. Here you go.
 
## Pros
214 Sirens

It's free

## Cons
You have to use our names (in the files), due to the fact that we were to lazy to change the name for the release.

# Usage

Just use and change the audio files (wav.) in the .AWC files in the `dlc_serversideaudio` Folder using OpenIV or other AWC editing tools. The awc files shouldn't be larger than 16MB. Which we honestly never tested ... So you might experience some fivem restrictions we aren't aware of. (But at least 4MB are totally okay, well tested by us.)

## ELS-Plus

These are the current ELS-Plus settings:

`SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new"` or other Soundbanks

`SoundSet="oiss_ssa_vehaud_bcso_new_soundset"` or other SoundSets

`AudioString="oiss_ssa_vehaud_bcso_new_horn"` or other AudioStrings

## FiveM Scripts

Use this native

https://docs.fivem.net/natives/?_0x2F844A8B08D76685

p0 = `"DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_BCSO_NEW"` or other Soundbanks

p1 = `false`

And call the sounds using this native:

https://docs.fivem.net/natives/?_0xE65F427EB70AB1ED

soundId = `-1`

audioName = `"OISS_SSA_VEHAUD_BCSO_NEW_HORN"`

entity = your entity || Most likely `GetVehiclePedIsUsing(PlayerPedId())`

audioRef `"DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_BCSO_NEW"`

isNetwork = `0`

p5 = `0`


# Thanks ❤️

Thanks to our server staff, mk7a and the guys on the CodeWalker Discord for the work, support and overall kindness!

# Table with Soundbank SoundSet and AudioString

|Soundbank|SoundSet|AudioString|
|-------------|-------------|--------------------------|
|New/Modern Sirens of the Los Santos Police Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_lspd_new|oiss_ssa_vehaud_lspd_new_soundset|oiss_ssa_vehaud_lspd_new_horn|
|||oiss_ssa_vehaud_lspd_new_siren_adam|
|||oiss_ssa_vehaud_lspd_new_siren_boy|
|||oiss_ssa_vehaud_lspd_new_siren_charles|
|||oiss_ssa_vehaud_lspd_new_siren_david|
|||oiss_ssa_vehaud_lspd_new_siren_edward|
|Old/Vintage Sirens of the Los Santos Police Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_lspd_old|oiss_ssa_vehaud_lspd_old_soundset|oiss_ssa_vehaud_lspd_old_horn|
|||oiss_ssa_vehaud_lspd_old_siren_adam|
|||oiss_ssa_vehaud_lspd_old_siren_boy|
|||oiss_ssa_vehaud_lspd_old_siren_charles|
|||oiss_ssa_vehaud_lspd_old_siren_david|
|||oiss_ssa_vehaud_lspd_old_siren_edward|
|New/Modern Sirens of the Los Santos Sheriff Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_lssd_new|oiss_ssa_vehaud_lssd_new_soundset|oiss_ssa_vehaud_lssd_new_horn|
|||oiss_ssa_vehaud_lssd_new_siren_adam|
|||oiss_ssa_vehaud_lssd_new_siren_boy|
|||oiss_ssa_vehaud_lssd_new_siren_charles|
|||oiss_ssa_vehaud_lssd_new_siren_david|
|||oiss_ssa_vehaud_lssd_new_siren_edward|
|Old/Vintage Sirens of the Los Santos Sheriff Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_lssd_old|oiss_ssa_vehaud_lssd_old_soundset|oiss_ssa_vehaud_lssd_old_horn|
|||oiss_ssa_vehaud_lssd_old_siren_adam|
|||oiss_ssa_vehaud_lssd_old_siren_boy|
|||oiss_ssa_vehaud_lssd_old_siren_charles|
|||oiss_ssa_vehaud_lssd_old_siren_david|
|||oiss_ssa_vehaud_lssd_old_siren_edward|
|New/Modern Sirens of the Blaine County Sheriff Office|||
|dlc_serversideaudio/oiss_ssa_vehaud_bcso_new|oiss_ssa_vehaud_bcso_new_soundset|oiss_ssa_vehaud_bcso_new_horn|
|||oiss_ssa_vehaud_bcso_new_siren_adam|
|||oiss_ssa_vehaud_bcso_new_siren_boy|
|||oiss_ssa_vehaud_bcso_new_siren_charles|
|||oiss_ssa_vehaud_bcso_new_siren_david|
|||oiss_ssa_vehaud_bcso_new_siren_edward|
|Old/Vintage Sirens of the Blaine County Sheriff Office|||
|dlc_serversideaudio/oiss_ssa_vehaud_bcso_old|oiss_ssa_vehaud_bcso_old_soundset|oiss_ssa_vehaud_bcso_old_horn|
|||oiss_ssa_vehaud_bcso_old_siren_adam|
|||oiss_ssa_vehaud_bcso_old_siren_boy|
|||oiss_ssa_vehaud_bcso_old_siren_charles|
|||oiss_ssa_vehaud_bcso_old_siren_david|
|||oiss_ssa_vehaud_bcso_old_siren_edward|
|New/Modern Sirens of the San Andreas Highway Patrol|||
|dlc_serversideaudio/oiss_ssa_vehaud_sahp_new|oiss_ssa_vehaud_sahp_new_soundset|oiss_ssa_vehaud_sahp_new_horn|
|||oiss_ssa_vehaud_sahp_new_siren_adam|
|||oiss_ssa_vehaud_sahp_new_siren_boy|
|||oiss_ssa_vehaud_sahp_new_siren_charles|
|||oiss_ssa_vehaud_sahp_new_siren_david|
|||oiss_ssa_vehaud_sahp_new_siren_edward|
|Old/Vintage Sirens of the San Andreas Highway Patrol|||
|dlc_serversideaudio/oiss_ssa_vehaud_sahp_old|oiss_ssa_vehaud_sahp_old_soundset|oiss_ssa_vehaud_sahp_old_horn|
|||oiss_ssa_vehaud_sahp_old_siren_adam|
|||oiss_ssa_vehaud_sahp_old_siren_boy|
|||oiss_ssa_vehaud_sahp_old_siren_charles|
|||oiss_ssa_vehaud_sahp_old_siren_david|
|||oiss_ssa_vehaud_sahp_old_siren_edward|
|Motorcycle Sirens of the San Andreas Highway Patrol|||
|dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike|oiss_ssa_vehaud_sahp_bike_soundset|oiss_ssa_vehaud_sahp_bike_horn|
|||oiss_ssa_vehaud_sahp_bike_siren_adam|
|||oiss_ssa_vehaud_sahp_bike_siren_boy|
|||oiss_ssa_vehaud_sahp_bike_siren_charles|
|||oiss_ssa_vehaud_sahp_bike_siren_david|
|||oiss_ssa_vehaud_sahp_bike_siren_edward|
|New/Modern Sirens of the National Office of Security Enforcement |||
|dlc_serversideaudio/oiss_ssa_vehaud_noose_new|oiss_ssa_vehaud_noose_new_soundset|oiss_ssa_vehaud_noose_new_horn|
|||oiss_ssa_vehaud_noose_new_siren_adam|
|||oiss_ssa_vehaud_noose_new_siren_boy|
|||oiss_ssa_vehaud_noose_new_siren_charles|
|||oiss_ssa_vehaud_noose_new_siren_david|
|||oiss_ssa_vehaud_noose_new_siren_edward|
|Old/Vintage Sirens of the National Office of Security Enforcement |||
|dlc_serversideaudio/oiss_ssa_vehaud_noose_old|oiss_ssa_vehaud_noose_old_soundset|oiss_ssa_vehaud_noose_old_horn|
|||oiss_ssa_vehaud_noose_old_siren_adam|
|||oiss_ssa_vehaud_noose_old_siren_boy|
|||oiss_ssa_vehaud_noose_old_siren_charles|
|||oiss_ssa_vehaud_noose_old_siren_david|
|||oiss_ssa_vehaud_noose_old_siren_edward|
|New/Modern Sirens of the Federal Investigation Bureau|||
|dlc_serversideaudio/oiss_ssa_vehaud_fib_new|oiss_ssa_vehaud_fib_new_soundset|oiss_ssa_vehaud_fib_new_horn|
|||oiss_ssa_vehaud_fib_new_siren_adam|
|||oiss_ssa_vehaud_fib_new_siren_boy|
|||oiss_ssa_vehaud_fib_new_siren_charles|
|||oiss_ssa_vehaud_fib_new_siren_david|
|||oiss_ssa_vehaud_fib_new_siren_edward|
|Old/Vintage Sirens of the Federal Investigation Bureau|||
|dlc_serversideaudio/oiss_ssa_vehaud_fib_old|oiss_ssa_vehaud_fib_old_soundset|oiss_ssa_vehaud_fib_old_horn|
|||oiss_ssa_vehaud_fib_old_siren_adam|
|||oiss_ssa_vehaud_fib_old_siren_boy|
|||oiss_ssa_vehaud_fib_old_siren_charles|
|||oiss_ssa_vehaud_fib_old_siren_david|
|||oiss_ssa_vehaud_fib_old_siren_edward|
|New/Modern Sirens of the Rockford Hills Police Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_rhpd_new|oiss_ssa_vehaud_rhpd_new_soundset|oiss_ssa_vehaud_rhpd_new_horn|
|||oiss_ssa_vehaud_rhpd_new_siren_adam|
|||oiss_ssa_vehaud_rhpd_new_siren_boy|
|||oiss_ssa_vehaud_rhpd_new_siren_charles|
|||oiss_ssa_vehaud_rhpd_new_siren_david|
|||oiss_ssa_vehaud_rhpd_new_siren_edward|
|Old/Vintage Sirens of the Rockford Hills Police Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_rhpd_old|oiss_ssa_vehaud_rhpd_old_soundset|oiss_ssa_vehaud_rhpd_old_horn|
|||oiss_ssa_vehaud_rhpd_old_siren_adam|
|||oiss_ssa_vehaud_rhpd_old_siren_boy|
|||oiss_ssa_vehaud_rhpd_old_siren_charles|
|||oiss_ssa_vehaud_rhpd_old_siren_david|
|||oiss_ssa_vehaud_rhpd_old_siren_edward|
|New/Modern Sirens of the Del Perro Police Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_dppd_new|oiss_ssa_vehaud_dppd_new_soundset|oiss_ssa_vehaud_dppd_new_horn|
|||oiss_ssa_vehaud_dppd_new_siren_adam|
|||oiss_ssa_vehaud_dppd_new_siren_boy|
|||oiss_ssa_vehaud_dppd_new_siren_charles|
|||oiss_ssa_vehaud_dppd_new_siren_david|
|||oiss_ssa_vehaud_dppd_new_siren_edward|
|Old/Vintage Sirens of the Del Perro Police Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_dppd_old|oiss_ssa_vehaud_dppd_old_soundset|oiss_ssa_vehaud_dppd_old_horn|
|||oiss_ssa_vehaud_dppd_old_siren_adam|
|||oiss_ssa_vehaud_dppd_old_siren_boy|
|||oiss_ssa_vehaud_dppd_old_siren_charles|
|||oiss_ssa_vehaud_dppd_old_siren_david|
|||oiss_ssa_vehaud_dppd_old_siren_edward|
|New/Modern Sirens of the Los Santos International Airport Police|||
|dlc_serversideaudio/oiss_ssa_vehaud_lsia_new|oiss_ssa_vehaud_lsia_new_soundset|oiss_ssa_vehaud_lsia_new_horn|
|||oiss_ssa_vehaud_lsia_new_siren_adam|
|||oiss_ssa_vehaud_lsia_new_siren_boy|
|||oiss_ssa_vehaud_lsia_new_siren_charles|
|||oiss_ssa_vehaud_lsia_new_siren_david|
|||oiss_ssa_vehaud_lsia_new_siren_edward|
|Old/Vintage Sirens of the Los Santos International Airport Police|||
|dlc_serversideaudio/oiss_ssa_vehaud_lsia_old|oiss_ssa_vehaud_lsia_old_soundset|oiss_ssa_vehaud_lsia_old_horn|
|||oiss_ssa_vehaud_lsia_old_siren_adam|
|||oiss_ssa_vehaud_lsia_old_siren_boy|
|||oiss_ssa_vehaud_lsia_old_siren_charles|
|||oiss_ssa_vehaud_lsia_old_siren_david|
|||oiss_ssa_vehaud_lsia_old_siren_edward|
|New/Modern Sirens of the Los Santos Port Police|||
|dlc_serversideaudio/oiss_ssa_vehaud_lspp_new|oiss_ssa_vehaud_lspp_new_soundset|oiss_ssa_vehaud_lspp_new_horn|
|||oiss_ssa_vehaud_lspp_new_siren_adam|
|||oiss_ssa_vehaud_lspp_new_siren_boy|
|||oiss_ssa_vehaud_lspp_new_siren_charles|
|||oiss_ssa_vehaud_lspp_new_siren_david|
|||oiss_ssa_vehaud_lspp_new_siren_edward|
|Old/Vintage Sirens of the Los Santos Port Police|||
|dlc_serversideaudio/oiss_ssa_vehaud_lspp_old|oiss_ssa_vehaud_lspp_old_soundset|oiss_ssa_vehaud_lspp_old_horn|
|||oiss_ssa_vehaud_lspp_old_siren_adam|
|||oiss_ssa_vehaud_lspp_old_siren_boy|
|||oiss_ssa_vehaud_lspp_old_siren_charles|
|||oiss_ssa_vehaud_lspp_old_siren_david|
|||oiss_ssa_vehaud_lspp_old_siren_edward|
|New/Modern Sirens of the Los Santos Fire Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_lsfd_new|oiss_ssa_vehaud_lsfd_new_soundset|oiss_ssa_vehaud_lsfd_new_horn|
|||oiss_ssa_vehaud_lsfd_new_siren_adam|
|||oiss_ssa_vehaud_lsfd_new_siren_boy|
|||oiss_ssa_vehaud_lsfd_new_siren_charles|
|||oiss_ssa_vehaud_lsfd_new_siren_david|
|||oiss_ssa_vehaud_lsfd_new_siren_edward|
|Old/Vintage Sirens of the Los Santos Fire Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_lsfd_old|oiss_ssa_vehaud_lsfd_old_soundset|oiss_ssa_vehaud_lsfd_old_horn|
|||oiss_ssa_vehaud_lsfd_old_siren_adam|
|||oiss_ssa_vehaud_lsfd_old_siren_boy|
|||oiss_ssa_vehaud_lsfd_old_siren_charles|
|||oiss_ssa_vehaud_lsfd_old_siren_david|
|||oiss_ssa_vehaud_lsfd_old_siren_edward|
|New/Modern Sirens of the Los Santos County Fire Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_lscofd_new|oiss_ssa_vehaud_lscofd_new_soundset|oiss_ssa_vehaud_lscofd_new_horn|
|||oiss_ssa_vehaud_lscofd_new_siren_adam|
|||oiss_ssa_vehaud_lscofd_new_siren_boy|
|||oiss_ssa_vehaud_lscofd_new_siren_charles|
|||oiss_ssa_vehaud_lscofd_new_siren_david|
|||oiss_ssa_vehaud_lscofd_new_siren_edward|
|Old/Vintage Sirens of the Los Santos County Fire Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_lscofd_old|oiss_ssa_vehaud_lscofd_old_soundset|oiss_ssa_vehaud_lscofd_old_horn|
|||oiss_ssa_vehaud_lscofd_old_siren_adam|
|||oiss_ssa_vehaud_lscofd_old_siren_boy|
|||oiss_ssa_vehaud_lscofd_old_siren_charles|
|||oiss_ssa_vehaud_lscofd_old_siren_david|
|||oiss_ssa_vehaud_lscofd_old_siren_edward|
|New/Modern Sirens of the Blaine County Fire Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new|oiss_ssa_vehaud_bcfd_new_soundset|oiss_ssa_vehaud_bcfd_new_horn|
|||oiss_ssa_vehaud_bcfd_new_siren_adam|
|||oiss_ssa_vehaud_bcfd_new_siren_boy|
|||oiss_ssa_vehaud_bcfd_new_siren_charles|
|||oiss_ssa_vehaud_bcfd_new_siren_david|
|||oiss_ssa_vehaud_bcfd_new_siren_edward|
|Old/Vintage Sirens of the Blaine County Fire Department|||
|dlc_serversideaudio/oiss_ssa_vehaud_bcfd_old|oiss_ssa_vehaud_bcfd_old_soundset|oiss_ssa_vehaud_bcfd_old_horn|
|||oiss_ssa_vehaud_bcfd_old_siren_adam|
|||oiss_ssa_vehaud_bcfd_old_siren_boy|
|||oiss_ssa_vehaud_bcfd_old_siren_charles|
|||oiss_ssa_vehaud_bcfd_old_siren_david|
|||oiss_ssa_vehaud_bcfd_old_siren_edward|
|New/Modern Sirens of SanFire|||
|dlc_serversideaudio/oiss_ssa_vehaud_sanfire_new|oiss_ssa_vehaud_sanfire_new_soundset|oiss_ssa_vehaud_sanfire_new_horn|
|||oiss_ssa_vehaud_sanfire_new_siren_adam|
|||oiss_ssa_vehaud_sanfire_new_siren_boy|
|||oiss_ssa_vehaud_sanfire_new_siren_charles|
|||oiss_ssa_vehaud_sanfire_new_siren_david|
|||oiss_ssa_vehaud_sanfire_new_siren_edward|
|Old/Vintage Sirens of SanFire|||
|dlc_serversideaudio/oiss_ssa_vehaud_sanfire_old|oiss_ssa_vehaud_sanfire_old_soundset|oiss_ssa_vehaud_sanfire_old_horn|
|||oiss_ssa_vehaud_sanfire_old_siren_adam|
|||oiss_ssa_vehaud_sanfire_old_siren_boy|
|||oiss_ssa_vehaud_sanfire_old_siren_charles|
|||oiss_ssa_vehaud_sanfire_old_siren_david|
|||oiss_ssa_vehaud_sanfire_old_siren_edward|
|New/Modern Sirens of the San Andreas Medical Services|||
|dlc_serversideaudio/oiss_ssa_vehaud_sams_new|oiss_ssa_vehaud_sams_new_soundset|oiss_ssa_vehaud_sams_new_horn|
|||oiss_ssa_vehaud_sams_new_siren_adam|
|||oiss_ssa_vehaud_sams_new_siren_boy|
|||oiss_ssa_vehaud_sams_new_siren_charles|
|||oiss_ssa_vehaud_sams_new_siren_david|
|||oiss_ssa_vehaud_sams_new_siren_edward|
|Old/Vintage Sirens of the San Andreas Medical Services|||
|dlc_serversideaudio/oiss_ssa_vehaud_sams_old|oiss_ssa_vehaud_sams_old_soundset|oiss_ssa_vehaud_sams_old_horn|
|||oiss_ssa_vehaud_sams_old_siren_adam|
|||oiss_ssa_vehaud_sams_old_siren_boy|
|||oiss_ssa_vehaud_sams_old_siren_charles|
|||oiss_ssa_vehaud_sams_old_siren_david|
|||oiss_ssa_vehaud_sams_old_siren_edward|
|New/Modern Sirens of the United States Forest Services|||
|dlc_serversideaudio/oiss_ssa_vehaud_usfs_new|oiss_ssa_vehaud_usfs_new_soundset|oiss_ssa_vehaud_usfs_new_horn|
|||oiss_ssa_vehaud_usfs_new_siren_adam|
|||oiss_ssa_vehaud_usfs_new_siren_boy|
|||oiss_ssa_vehaud_usfs_new_siren_charles|
|||oiss_ssa_vehaud_usfs_new_siren_david|
|||oiss_ssa_vehaud_usfs_new_siren_edward|
|Old/Vintage Sirens of the United States Forest Services|||
|dlc_serversideaudio/oiss_ssa_vehaud_usfs_old|oiss_ssa_vehaud_usfs_old_soundset|oiss_ssa_vehaud_usfs_old_horn|
|||oiss_ssa_vehaud_usfs_old_siren_adam|
|||oiss_ssa_vehaud_usfs_old_siren_boy|
|||oiss_ssa_vehaud_usfs_old_siren_charles|
|||oiss_ssa_vehaud_usfs_old_siren_david|
|||oiss_ssa_vehaud_usfs_old_siren_edward|
|Miscellaneous Siren and Vehicle Sounds|||
|dlc_serversideaudio/oiss_ssa_vehaud_etc|oiss_ssa_vehaud_etc_soundset|oiss_ssa_vehaud_etc_adam|
|||oiss_ssa_vehaud_etc_boy|
|||oiss_ssa_vehaud_etc_charles|
|||oiss_ssa_vehaud_etc_david|
|||oiss_ssa_vehaud_etc_edward|
|||oiss_ssa_vehaud_etc_frank|
|||oiss_ssa_vehaud_etc_george|
|||oiss_ssa_vehaud_etc_henry|
|||oiss_ssa_vehaud_etc_ida|
|||oiss_ssa_vehaud_etc_john|
|||oiss_ssa_vehaud_etc_king|
|||oiss_ssa_vehaud_etc_lincoln|
|||oiss_ssa_vehaud_etc_mary|
|||oiss_ssa_vehaud_etc_nancy|
|||oiss_ssa_vehaud_etc_ocean|
|||oiss_ssa_vehaud_etc_paul|
