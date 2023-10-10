<h1>Trizeal</h1>
<img width="165" height="165" align="right" src="https://github.com/DerekPascarella/Trizeal-EnglishPatchDreamcast/blob/main/images/cover.jpg?raw=true">Download the English translation patch (more information in the <a href="#patching-instructions">Patching Instructions</a> section).
<br><br>
<ul>
 <li><b>GDI Format (Users of ODEs or Emulators)</b><br>Download <a href="https://github.com/DerekPascarella/Trizeal-EnglishPatchDreamcast/releases/download/1.0/Trizeal.English.v1.0.dcp">Trizeal (English v1.0).dcp</a> for use with <a href="https://github.com/DerekPascarella/UniversalDreamcastPatcher">Universal Dreamcast Patcher</a> v1.3 or newer.</li>
 <br>
 <li><b>CDI Format (Users Burning to CD-R)</b><br>Download <a href="https://github.com/DerekPascarella/Trizeal-EnglishPatchDreamcast/releases/download/1.0/Trizeal.English.v1.0.xdelta">Trizeal (English v1.0).xdelta</a> for use with <a href="https://www.romhacking.net/utilities/704/">Delta Patcher</a> (or equivalent tools).</li>
</ul>

<h2>Table of Contents</h2>

1. [Patching Instructions](#patching-instructions)
2. [Release Changelog](#release-changelog)
3. [What's Changed](#whats-changed)
4. [About the Game](#about-the-game)
5. [Unlimited Continues Feature](#unlimited-continues-feature)
6. [Fully Unlocked Save](#fully-unlocked-save)

<h2>Patching Instructions</h2>
<ul>
 <li><b>GDI Format (Users of ODEs or Emulators)</b><br><img align="right" width="250" src="https://github.com/DerekPascarella/UniversalDreamcastPatcher/blob/main/screenshots/screenshot.png?raw=true">The DCP patch file shipped with this release is designed for use with <a href="https://github.com/DerekPascarella/UniversalDreamcastPatcher">Universal Dreamcast Patcher</a> v1.3 or newer.  Note that Universal Dreamcast Patcher supports both TOSEC-style GDI and Redump-style CUE disc images as source input.<br><br><ol type="1"><li>Click "Select GDI or CUE" to open the source disc image.</li><li>Click "Select Patch" to open the DCP patch file.</li><li>Click "Apply Patch" to generate the patched GDI, which will be saved in the folder from which the application is launched.</li><li>Click "Quit" to exit the application.</li></ol></li>
 <br>
 <li><b>CDI Format (Users Burning to CD-R)</b><br><img align="right" width="250" src="https://i.imgur.com/r4b04e7.png">The XDelta patch file shipped with this release can be used with any number of Delta utilities, such as <a href="https://www.romhacking.net/utilities/704/">Delta Patcher</a>. Ensure the source CDI has an MD5 checksum of <tt>93631A0B74CAA201964C519705066715</tt>.<br><br><ol type="1"><li>Click the settings icon (appears as a gear) and enable "Backup original file" and "Checksum validation".</li><li>Click the "Original file" browse icon and select the unmodified CDI.</li><li>Click the "XDelta patch" browse icon and select the XDelta patch.</li><li>Click "Apply patch" to generate the patched CDI in the same folder containing the original CDI.</li><li>Verify that the patched CDI has an MD5 checksum of <tt>B90B6E28F98A079F3442D7E3CE2799FE</tt>.</ol></li>
</ul>

<h2>Release Changelog</h2>
<ul>
 <li>Version 1.0 (2023-10-XX)</li>
 <ul>
  <li>Initial release.</li>
 </ul>
</ul>

<h2>What's Changed</h2>
<img align="right" width="267" height="200" src="https://github.com/DerekPascarella/Trizeal-EnglishPatchDreamcast/blob/main/images/screenshot.png?raw=true">Below is a high-level list of changes implemented for this English translation patch.
<br><br>
<ul>
 <li>A half-width font has been implemented.</li>
 <li>An in-game button combination has been implemented to toggle unlimited continues on/off (see <a href="#unlimited-continues-feature">Unlimited Continues Feature</a>).</li>
 <li>All textures/graphics have been translated into English and re-rendered.</li>
 <li>All in-game text has been translated and appears in English.</li>
 <li>English language inconsistencies and errors have been corrected.</li>
 <li>A 100% fully unlocked save has been provided (see <a href="#fully-unlocked-save">Fully Unlocked Save</a>).</li>
 <li>VMU save file metadata has been translated and appears in English.</li>
 <li>VMU save icon has been translated into English.</li>
</ul>

<h2>About the Game</h2>
<table>
<tr>
<td><b>Title</b></td>
<td>Trizeal (トライジール)</td>
</tr>
<tr>
<td><b>Developer</b></td>
<td>Triangle Service</td>
</tr>
<tr>
<td><b>Publisher</b></td>
<td>SEGA</td>
</tr>
<tr>
<td><b>Release Date</b></td>
<td>2005-06-05</td>
</tr>
<tr>
<td><b>Supported Peripherals</b></td>
<td>VGA Box, Controller, Arcade Stick, VMU</td>
</table>
<br>
"Trizeal" (トライジール) is a sci-fi vertical-scrolling shooter directly ported from its arcade incarnation.
<br><br>
Using polygonal graphics, but retaining a completely 2D gameplay, "Trizeal" puts you in command of two tiny starfighter as you attempt to clear several stages filled with enemy ships and creatures gunning for you.
<br><br>
Your ship is able to morph into three distinct configurations, each with their own speed and armor as well as unique weapon system (basic machine gun, homing missiles, and laser), by picking up power-ups you can upgrade each form and increase its abilities and the point of the game is to keep your ship balanced enough to survive in all situations.
<br><br>
Features a unique Bonus mode with additional stages not included in the arcade original, and two-player cooperative gameplay.

<h2>Unlimited Continues Feature</h2>
As a special feature of this English translation patch, a new unlimited continues option has been implemented via an in-game button combination. At any point during gameplay, players can press the L and R Trigger buttons to toggle unlimited continues on or off. A visual indicator, shown below, alerts players to this toggle's status. This indicator appears as an asterisk to the right of "1P SCORE" during Stage gameplay.
<br><br>
Note that Trigger buttons can be mapped to action commands (e.g., bomb), and therefore players should activate/de-active unlimited continues outside of normal gameplay, such as at the title screen or while in the pause menu.
<br><br>
<img width="308" height="62" src="https://github.com/DerekPascarella/Trizeal-EnglishPatchDreamcast/blob/main/images/unlt_cont_toggle.png?raw=true">

<h2>Fully Unlocked Save</h2>
A <a href="https://github.com/DerekPascarella/Trizeal-EnglishPatchDreamcast/tree/main/save">100% unlocked save</a> is provided with this watch release, unlocking the following items:
<br><br>
<ul>
 <li>"Score Attack" Stage 1</li>
 <li>"Score Attack" Stage 2</li>
 <li>"Score Attack" Stage 3</li>
 <li>"Score Attack" Stage 4</li>
 <li>"Score Attack" Stage 5</li>
 <li>"Score Attack" Stage 6</li>
 <li>"Score Attack" Lifting Stage</li>
 <li>"Score Attack" Bonus Stage</li>
</ul>
