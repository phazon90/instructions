# Step 1: Install sidequest advanced and backup scores/data for BS

Download sidequest advanced:

https://objects.githubusercontent.com/github-production-release-asset-2e65be/254852798/64b96ab3-f2d5-4a6a-a6f7-d115b476a668?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20230407%2Fus-east-1%2Fs3%2Faws4\_request&X-Amz-Date=20230407T145923Z&X-Amz-Expires=300&X-Amz-Signature=bc8bbd23f2067aaf03c4d8268b10882f65b1e4815efa8751414201120f8e2377&X-Amz-SignedHeaders=host&actor\_id=0&key\_id=0&repo\_id=254852798&response-content-disposition=attachment%3B%20filename%3DSideQuest-Setup-0.10.33-x64-win.exe&response-content-type=application%2Foctet-stream

Install sidequest advanced

Open SideQuest and CONNECT your Quest to your PC (quest should have developer mode enabled)

Navigate to sdcard/Android/data/com.beatgames.beatsaber/files using the SideQuest file explorer.

Save the files: AvatarData.dat, PlayerData.dat and settings.cfg into a folder on your PC. Do not lose these, as they contain your scores and other settings

Leave quest connected

# Step 2: Install BS downgrader tool and downgrade BS version

Download oculus BS downgrader

https://github.com/ComputerElite/Oculus-Downgrader/releases/latest/download/Oculus.Downgrader.zip

Unzip

Run exe

Select 'n' for access token mode

Get personal access token:

Go to link below and SIGN IN

https://www.oculus.com/experiences/quest

hit ctrl + shift + i (dev tools)

go to the network tab

Reload the page next to your address bar

Then in the network tab type graphql into the filter box

Next click the last request (graphql?forced\_locale=en\_US) and open the payload tab (if payload is not present go to the header tab). Then search for a label named access\_token. Copy the text after that. You can copy it by right clicking and pressing copy value

Go back to BS downgrader CMD prompt, paste access token

Change headset version to Quest

Download this version

***1\.28.0\_4124311467***

Install to quest option

No to mod before install

Leave quest connected

# Step 3: Install BMBF from sidequest store on pc

Search for BMBF on sideload app store

Click download app and then Install when prompted

# Step 4: Install modded BS

LAUNCH BEAT SABER and play a level and fail

After running Beat Saber once, open BMBF from unknown sources in Apps page in quest (dropdown option for unknown sources)

# Step 5: Prep for adding songs

Once opened, follow each step in BMBF exactly as you're told to mod your game. Once completed, you should see QuestBoard with BeastSaber loaded inside of the BMBF app. This is where you can download any custom songs available. You can also click the BeatSaver button to download songs too

After successfully modding your game, the Restore App popup will appear. You can just click Close

When trying to launch Beat Saber after modding it, you will likely get the Restore App popup again. This time, select Open App instead
