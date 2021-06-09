<h1>Prisonbreak Gamemode (PB) by Yoshey for Pavlov VR</h1>
<h3>Version 2.1c - 2020</h3>
<h2>Note: This project is not being worked on actively anymore</h2>
<br>
All gamemode logic, art assets, models and sound assets are ultimately owned by Yoshey.<br>
Exceptions:
<ul>
  <li>Assets owned by Mottflyer</li>
  <li>Assets owned by Valve</li>
  <li>Other assets as mentioned in Credits.txt</li>
</ul>
<br>
<br>
<b>BE SURE TO READ <i>"License - ReadMe.txt"</i></b>
<br>
<br>
<h3>Special thanks to all my Donators at https://www.patreon.com/Yoshey for supporting me to create these modules!</h3>
<br>
<br>
If you do not have the Pavlov Workshop Plugin, you must link your UE4 account with your
GitHub account to get access to the plugin.
<br>
<h5>The Prisonbreak modification is Licensed under the Creative Commons Attribution 4.0 International License. (CC-BY 4.0)
https://creativecommons.org/licenses/by/4.0/</h5>
<br>
<br>
<br>
<br>
<h3>Version History:</h3>
<b>2.1c</b>
<ul>
  <li>Fixed Scoreboards disappearing during games</li>
  <li>They now appear nearly instantaneously after spawning</li>
  <li>Fixed the example cardscanner mesh</li>
</ul>
<b>2.1</b>
Note: When Updating, I recommend first renaming the old paths to the new ones, then following the update instructions to preserve most of your map's logic that works with Prisonbreak Logic from breaking
<br>
<br>
<ul>
  <li>Updated to the newest AMM Module version</li>
  <li>Changed file paths to shorten overall file lengths</li>
  <ul> 
    <li>Content\DeveloperMode -> Plugins\Prisonbreak\DeveloperMode</li>
    <li>Content\Prisonbreak\AdvancedMovement -> Content\AdvancedMovement</li>
    <li>Content\Prisonbreak\AdvancedMovementExamples -> Content\AdvancedMovementExamples</li>
    <li>Content\Prisonbreak\PrisonbreakGamemode -> Content\PB</li>
    <li>Content\Prisonbreak\PrisonbreakTemplates -> Content\PBTemplates</li>
    <li>PB\Items\Admin\Teleport_Destinations -> PB\Spawns\Admin\Teleport_Destinations</li>
  </ul>
  <li>Renamed/shortened many donator asset paths and names</li>
</ul>
<b>2.0</b>
<ul>
  <li>Added Advanced Movement Module (Climbing and BHopping)</li>
  <li>Reworked Screwdriver and IDCard overlap system</li>
  <li>Map Makers now receive limited access to the donator module and can receive the donator rewards for themselves on their maps for free</li>
  <li>Implemented new pavlov workshop features such as</li>
  <ul>
    <li>Native Pavlov inventory system</li>
    <li>Server controlled staff team and ban lists</li>
    <li>Server settings and saved settings</li>
    <li>Donator settings are now saved</li>
    <li>Took advantage of PlayerProxy, PlayerInfo and Interactors</li>
  </ul>
  <li>Changed Announcer voiceactor to lines recorded by @Big Bill Hell's</li>
  <li>Ghosts now show when the round ends</li>
  <li>Prisoners and Guards now have different audio-distances(Radio is still Global.)</li>
  <li>Added Limited Ammo</li>
  <li>Added Prisoner Skins</li>
  <li>Breakables cooldown is on the Screwdriver now, not the Breakable</li>
  <li>Cleaned up some Assets and utilized UE4's Parenting System</li>
</ul>
