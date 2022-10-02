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

Here is a Table with the Soundbank Soundsets and Audiostrings used in this resource: https://github.com/fk-1997/Server-Sided-Sounds-and-Sirens/blob/main/IDTABLE.md#table-with-soundbank-soundset-and-audiostring

## Luxart Vehicle Control

There is a great wiki over on their github: https://docs.luxartengineering.com/v3/resource-installation/server-sided-siren-integration

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

# Testing 
To test server sided sirens without configuring another resouce check out: https://github.com/TrevorBarns/Server-Side-Audio-Tester

# Thanks ❤️

Thanks to our server staff, mk7a and the guys on the CodeWalker Discord for the work, support and overall kindness!
