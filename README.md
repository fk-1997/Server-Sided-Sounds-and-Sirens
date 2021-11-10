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

Just use and change the audio files (wav.) in the .AWP files in the `dlc_serversideaudio` Folder using OpenIV or other AWC editing tools. The awc files shouldn't be larger than 16MB.

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
