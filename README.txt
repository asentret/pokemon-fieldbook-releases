POKEMON FIELDBOOK
User Guide
======================================================================
Windows version: 1.8.9
Android version: 1.8.9
Guide revision: 3.9 - October 13, 2026

WELCOME
----------------------------------------------------------------------
Pokemon Fieldbook helps you keep track of the Pokemon you have collected
across nine game groups. Choose a game, browse its Pokedex, and mark each
species as acquired. Progress bars show how much you have completed, while
encounter hints and evolution instructions help you plan what to get next.

The app also includes a separate Pokemon HOME inventory for recording
individual Pokemon, quantities, moves, natures, IVs, and source games.

The Windows program and Android app work offline with their included
Pokedex data and sprites. Both use a lavender/purple appearance with light
and dark modes, rounded controls, and an animated Crystal Sentret header.
Your collection saves locally. You can transfer it between a computer and
phone by exporting and importing backup files.

Fieldbook is a manual tracker. It does not connect to Nintendo accounts,
read your actual game saves, catch or transfer Pokemon, or synchronize
with the official Pokemon HOME service. Marking a species here records
your own progress without changing anything in your games.

NEW IN 1.8.9: INLINE 3D DETAILS
----------------------------------------------------------------------
A downloaded model automatically replaces the detail sprite. On Windows,
drag the model directly inside the bottom details panel; scroll to zoom.
On Android, rotate and pinch to zoom inside the Pokemon guide. There is no
View 3D button and no separate model window. The static image stays visible
while loading or when this exact form has no verified model.
Sprite-description text has been removed from the full guide. Variation
information stays available in the checklist and Forms view.

CONSISTENT ART AND OPTIONAL 3D
----------------------------------------------------------------------
Progress markers are larger and move smoothly, including during rapid
checkbox changes. Hidden progress bars stop animating to save resources.

Every checklist image now uses a 512 x 512 Pokemon HOME render from the
same source family. The animated Crystal Sentret header remains unchanged.
The detail panel shows the matching HOME image until its model is ready.
Regional forms, genders and other variants keep separate, game-specific
checks. Some distinctions cannot be seen in a front image: Torchic's tail
spot, the underside authenticity marks on tea Pokemon, and Minior's core
colors inside its shell. Read the Variation field for these differences.

Select a Pokemon to see its available 3D model directly in the detail
picture area, on Windows and inside the Android guide. Drag to rotate,
scroll or pinch to zoom, and use Reset view to return to the front. Animated
models offer Pause / Play. The viewer stops rendering while hidden.
Windows 3D viewing needs Microsoft Edge WebView2 Runtime. If it is missing,
Settings > 3D models includes a link to Microsoft's installer. Android uses
the device's WebView; keep Android System WebView updated for 3D support.
The native checklist and included images do not require the 3D viewer.

Downloads are optional. Automatic downloading fetches that exact model the first
time you open it, checks its size and SHA-256 checksum, and saves it locally.
Later views use the verified cached model without needing a connection.
Settings > 3D models on Windows, or 3D models in Android's side menu, shows
the cached count and storage size. Choose Download all models to cache every
available exact model. It shows the total size and progress, skips verified
files already downloaded, and lets you cancel. Completed models remain saved;
choose Download all models again to resume or retry missing files. Closing
the settings dialog cancels the batch without deleting completed downloads.
Turn off new downloads to use cached
models only, or clear downloaded models to reclaim space. Clearing models
does not remove any checklist, HOME record, or included image.

Models missing an exact form match are labeled unavailable; the app does
not substitute another form. A download error leaves the offline image
and collection usable. Reselect the Pokemon after the connection or host recovers.
Models come from the app's GitHub repository under model-downloads/v1.
They must be published there before a new installation can download them.
The catalog records each source and checksum. Models are separate from the
installer and from your collection backups: each device downloads its own
cache. Updating the app keeps compatible cached models and collection saves.

App code © 2026 Tristan (asentret). This credit appears in both apps.
Pokemon artwork/models remain third-party assets, not covered by the code's
MIT license. Full attribution is in THIRD-PARTY-NOTICES.txt.

POKEDEX NOTES AND HOENN GAMES
----------------------------------------------------------------------
The sidebar (Windows) and three-line drawer (Android) have collapsible
Switch, Game Boy Advance, and DS / 3DS sections. Click or tap a section
heading to expand it, then select a game. Each game keeps its progress bar.
Expanded sections are remembered on that device. Scroll the game list if
needed. Pokemon HOME remains a separate item outside these sections.

Game Boy Advance: FireRed / LeafGreen (Kanto 151 + National 386),
Ruby / Sapphire (Hoenn 202 + National 386), and a separate Emerald
collection (Hoenn 202 + National 386).
DS / 3DS: Sun / Moon, original 302-entry Alola Dex (not Ultra Sun/Moon).
Switch: all five previously included game groups and their DLC Pokedexes.
FireRed and LeafGreen share one game-group checklist, like the other paired
games. Use the version filter for edition-specific locations and rates.
Deoxys displays Attack Forme in FireRed and Defense Forme in LeafGreen;
select an edition to switch its picture. Both forms can be tracked separately.

There are now 18 Pokedexes and 4,929 official Pokedex entries, before forms.
National Dex coverage includes trades and historical event Pokemon; it
does not mean all 386 species can be caught in LeafGreen's grass.

Field Notes display the Pokedex description from the selected game. In
paired games, select an edition to read its text, or Both versions to see
both labeled entries. Form-specific text is used where recorded; species
text and missing form entries are labeled. No other game's entry is silently
substituted. Previous acquisition advice is preserved under GUIDE NOTES.
The separate Important Requirements section has been removed.
Regional and National dexes share checks within each game group. Emerald
is independent of Ruby/Sapphire, including backup progress.

Open a Pokemon's full guide and scroll to ENCOUNTER RATES. Rates are
specific to the edition, location, method, form and listed conditions.
They describe that encounter table, not the chance a ball catches it.
The bundled numerical tables cover Ruby/Sapphire, Emerald, FireRed/LeafGreen,
Sun/Moon and Sword/Shield
including its expansions. Other games show that verified rates are not
available. Gifts/fixed encounters do not receive a random spawn percentage.
SOS caller-specific odds are not verified, so no percentage is claimed.
Missing data is never treated as a 0% chance. Sources are in each guide.

Day/night encounter restrictions appear at the start of the checklist hint
and under ENCOUNTER TIME in the full guide. Labels follow the selected
edition, location and form. Search for daytime, nighttime, or an area name.
A missing time label does not mean that every encounter is available all
day. Timing for ordinary wild spawns does not automatically apply to raids,
Alpha Pokemon, scripted encounters, gifts, trades or DLC areas. Evolution
time requirements remain in the evolution steps. Moon uses its reversed
in-game clock; the label refers to the phase inside the game.

Update BOTH devices to 1.8.9 or newer before transferring checks for the
new games/forms. Backup format 1 is retained; old backups import into this
release. Older app versions cannot recognize the new game/form IDs. HOME
inventory and existing game registrations remain separate and unchanged.

CONTENTS
----------------------------------------------------------------------
  1. Install and open the Windows program
  2. Install and open the Android app
  3. Your first collection checklist
  4. Included games and Pokedexes
  5. Understand progress and overlapping entries
  6. Search, filters, encounters, and evolution instructions
  7. Use the Pokemon HOME inventory
  8. Save, export, and restore your collection
  9. Transfer between a computer and phone
 10. Appearance, menus, and keyboard controls
 11. Check for and install updates
 12. Share the app with someone else
 13. Troubleshooting and common questions
 14. Credits and guide history


1. INSTALL AND OPEN THE WINDOWS PROGRAM
======================================================================
The Windows release is built for Windows 10 and Windows 11 x64. You do not need to
install Python or any programming tools to use the packaged program.

Recommended: use the installer

  1. Locate Pokemon-Fieldbook-Setup-1.8.9.exe.
  2. Double-click it and follow the Setup instructions.
  3. Choose a desktop shortcut if you want one.
  4. Open Pokemon Fieldbook from the Start menu or your shortcut.

Setup installs for your current Windows account. The usual location is:
  %LOCALAPPDATA%\Programs\Pokemon Fieldbook

Alternative: use the portable ZIP

  1. Locate Pokemon-Fieldbook-Windows.zip.
  2. Extract the entire ZIP to a folder you want to keep.
  3. Open that folder and run Pokemon-Fieldbook.exe.

Keep the _internal folder beside that executable. It contains required
runtime files. Do not run the program directly from inside the ZIP or
copy only the executable out of this version of the package.

An optional single-file executable is also available. It bundles its
runtime into one file, but can take longer to start. Use Setup or the
Windows ZIP if startup speed matters to you.

All these Windows distributions use the same local collection folder
for the same Windows account. Switching between them does not create
an independent collection. Close the current copy before opening another.


2. INSTALL AND OPEN THE ANDROID APP
======================================================================
The Android app requires Android 8.0 or newer.

  1. Transfer Pokemon-Fieldbook-Android-1.8.9.apk to your phone.
  2. Open the APK using your phone's file manager or download screen.
  3. If prompted, allow that file manager or browser to install apps.
     The exact wording depends on the phone.
  4. Confirm installation, then open Pokemon Fieldbook.

Use the three-line menu to access file and settings actions. Choose
User guide under Settings to read this complete guide inside the app,
even when offline. Scroll to read, or select text to copy it. Use Close
or the Android Back control to return to your collection. Tap a
Pokemon entry to open its detailed description and animated sprite.

When installing a newer compatible APK, Android can update the existing
app and retain its data. You normally do not need to uninstall first.

IMPORTANT: Uninstalling the Android app or clearing its app storage
removes its local collection. Export both kinds of backup first if you
want to restore your checklist and HOME inventory afterward.


3. YOUR FIRST COLLECTION CHECKLIST
======================================================================
  1. Open Fieldbook and choose the game you want to track.
  2. Choose one of that game's Pokedexes.
  3. If applicable, choose the version of the paired games you play.
  4. Find a Pokemon by browsing or using the search box.
  5. Mark it acquired using its checkbox.
  6. Watch the completion count and progress bar update.

Your changes save locally as you make them. You do not need to export
a file after every checkmark. Export is for making a separate backup
or moving your collection to another device.

On Windows, double-click anywhere on a checklist row to mark that
Pokemon acquired. Double-clicking an already acquired Pokemon leaves
it acquired. To remove the checkmark, click its checkbox or select the
row and press Space to toggle its state.

Selecting a row shows its details at the bottom of the Windows app.
Drag the divider above the detail panel to give it more or less room.
Drag the divider above the bottom panel upward when you want more room to read.

If you make an accidental checklist change, use Undo where available.
Reset game clears registrations for the selected game after confirmation;
it is not needed for switching games or clearing a search. Export a
backup before resetting progress that you might want later.


4. INCLUDED GAMES AND POKEDEXES
======================================================================
Pokemon Legends: Z-A
  Lumiose Pokedex ....................................... 232 entries
  Hyperspace Pokedex .................................... 132 entries

Pokemon Scarlet / Violet
  Paldea Pokedex ........................................ 400 entries
  Kitakami Pokedex ...................................... 200 entries
  Blueberry Pokedex ..................................... 243 entries

Pokemon Legends: Arceus
  Hisui Pokedex ......................................... 242 entries

Pokemon Brilliant Diamond / Shining Pearl
  Sinnoh Pokedex ........................................ 151 entries
  National Pokedex ...................................... 493 entries

Pokemon Sword / Shield
  Galar Pokedex ......................................... 400 entries
  Isle of Armor Pokedex ................................. 211 entries
  Crown Tundra Pokedex .................................. 210 entries

Pokemon Ruby / Sapphire (Game Boy Advance)
  Hoenn Pokedex ......................................... 202 entries
  Generation III National Pokedex ....................... 386 entries

Pokemon Emerald (Game Boy Advance; separate collection)
  Hoenn Pokedex ......................................... 202 entries
  Generation III National Pokedex ....................... 386 entries

Pokemon FireRed / LeafGreen (Game Boy Advance)
  Kanto Pokedex ......................................... 151 entries
  Generation III National Pokedex ....................... 386 entries

Pokemon Sun / Moon (DS / 3DS section)
  Original Alola Pokedex ................................ 302 entries

Together these contain 4,929 numbered entries in 18 Pokedexes. Species
that appear in multiple Pokedexes for one game group overlap, producing
3,807 independently tracked game/species combinations.

These are species checklists. They do not separately track every form,
gender, shiny variant, Mega Evolution, or Arceus research task. Mythical
and event entries are included in the totals; inclusion does not mean
an event is currently running or a Pokemon is obtainable without trades,
transfers, DLC, or another stated requirement.


5. UNDERSTAND PROGRESS AND OVERLAPPING ENTRIES
======================================================================
The selected Pokedex shows registered and still-to-discover counts,
with a lavender gradient completion bar, soft shine and a purple/lavender ball
marker. The two-tone marker has a diamond-shaped clasp and crescent highlight.
The marker glides to the new position when progress changes. Each game also has a sidebar progress bar so
you can see how your collections compare at a glance.

Within one game group, a species shares its registration across any
Pokedexes in which it appears. For example, if a species is listed in
both a base-game dex and that game's DLC dex, you only need to register
it once. Its other overlapping entries update too.

Different game groups stay independent. Registering a Pokemon for
Sword / Shield does not register it for Scarlet / Violet.

Because of overlap, adding the regional and DLC totals is not the same
as counting unique species for the game. This is why a game-level total
can differ from the sum of its individual Pokedex totals.

HOME inventory is separate again: adding a Pokemon to HOME does not
check it off in a game, and checking it off does not create a HOME entry.


6. SEARCH, FILTERS, ENCOUNTERS, AND EVOLUTION INSTRUCTIONS
======================================================================
Use search to find a name, Pokedex number, location, item, move, or
evolution requirement. Filters can narrow the list to registered or
missing Pokemon and acquisition methods. Use the available sorting
controls to change the order of the list.

Switching Pokedexes within the same game (including regional, National and
DLC dexes) keeps your search, registration and acquisition filters, sort
order, edition and variant visibility active. Clear filters when you want
to browse the full list again. A filter can legitimately return no matches
in a different Pokedex.

If you cannot find an expected entry, first check the selected game
and Pokedex. Then use Clear filters and remove any search text. A
registered/missing filter can hide an entry you just changed.

For paired games, choose your version so that encounter information
matches the version you play. Read the full guide for version-specific
locations and conditions rather than relying only on the short row hint.

Evolved species have evolution instructions. Depending on the species
and game, these may include levels, items, friendship, time of day,
trades, moves, or other conditions. Follow the instructions for the
selected game; requirements can differ between games. Pre-evolution
hints help you start with the Pokemon needed for the evolution.

On desktop, the complete guide appears in the bottom detail panel.
The redundant Full guide button has been removed. Android opens the guide
when you tap a Pokemon row; the Pokedex selector has a dropdown arrow.
The full guide omits the Sources section to keep the description concise.
The detailed guides and included sprites work offline. An Online source
button opens an external reference in your browser and needs internet
access to load that page. The app's bundled information does not refresh
itself when an external website changes.

The checklist uses static Pokemon HOME renders. Detail views automatically
show the matching downloaded 3D model when available; otherwise they keep
the same static picture. The header uses animated Sentret from Pokemon
Crystal. Read the Variation field for differences hidden from the front.


7. USE THE POKEMON HOME INVENTORY
======================================================================
Open the Pokemon HOME tab to maintain a manual inventory of the Pokemon
you keep in that service. No account sign-in is required or available.

To add an entry, choose Add Pokemon, enter its details, then select
Save entry. Fields include:

  Species          The Pokemon's species. You can type a species if
                   it is not offered in the list.
  Form / nickname  Optional details that distinguish this Pokemon.
  Quantity         How many copies the entry represents, from 1 to 9,999.
  Moves            Up to four move names, entered as text.
  Nature           The Pokemon's recorded nature.
  IVs              HP, Attack, Defense, Special Attack, Special Defense,
                   and Speed. Each is 0-31, or blank if unknown.
  Source game      The game the Pokemon came from. You can type a source
                   when the one you need is not listed.

Use one entry with a larger quantity for identical copies. Use separate
entries when their moves, nature, IVs, source, or other details differ.
For example, two Pokemon of the same species with different movesets
should be separate entries if you want to preserve both builds.

Select an existing entry to edit it. On Windows, double-clicking a HOME
row opens editing; it does not mark a game checklist entry acquired.
Duplicate is useful for creating a similar entry, then changing the
details. Delete entry removes the selected record after confirmation.

Search the inventory by Pokemon, move, nature, or source game, and use
the source filter to narrow it further. The inventory supports up to
10,000 entries. Entry count and total quantity are different: an entry
with quantity 5 represents five Pokemon but occupies one record.

Fieldbook stores what you enter. It does not verify move legality,
retrieve IVs from your games, or confirm that the Pokemon is in your
actual HOME account. Update your records when your real collection changes.


8. SAVE, EXPORT, AND RESTORE YOUR COLLECTION
======================================================================
Automatic local saving

Checklist changes save automatically. HOME edits save when you confirm
Save entry. These local saves let you close and reopen the app without
re-entering your collection.

Windows stores collection and preferences under:
  %LOCALAPPDATA%\PokemonFieldbook

To open that folder, press Windows+R, paste the path above, and press Enter.
The main files include progress.json for checklists and
home-collection.json for HOME. Appearance and updater preferences are
stored separately in settings.json and update-settings.json.

The app retains previous valid collection saves for recovery. Exported
backups are still useful because they can be kept away from the device.
Android uses app-private storage; use Export to obtain transferable files.

Exporting a complete backup

  1. On Windows, open File. On Android, open the three-line menu.
  2. Choose Export checklist backup and save the JSON file.
  3. Choose Export HOME backup and save that JSON file too.
  4. Keep both files somewhere you can recover them later.

The checklist backup includes all nine games, not just the currently
selected Pokedex. The HOME backup includes the full HOME inventory.
Export both even if you normally spend most of your time on one tab.
Use dated folders or filenames to keep multiple snapshots organized.

Importing and choosing Merge or Replace

Open the matching Import action and select the backup file. Read the
preview before applying it. Checklist files and HOME files have different
purposes and must be imported using their corresponding commands.

For checklists:
  Merge keeps your current registrations and adds those in the backup.
  Replace all restores registrations exactly as recorded in the backup
  across all nine games. Current checks missing from that backup are removed.

For HOME:
  Merge adds entries with new record IDs. If an ID already exists, the
  current entry's details and quantity are kept. Importing the same
  backup twice therefore does not double its quantities.
  Replace HOME inventory restores exactly the selected backup, including
  its details and quantities, and removes entries absent from that backup.

Merge is useful for adding records without discarding what you already
have. Replace is useful when the backup should become the complete source
of truth, including edits and deletions. Export the destination's current
collection first if you may want to return to it.

HOME matching uses record IDs rather than species names. Two separately
created records of the same species can remain separate after a merge.
An edited record with an existing ID will not overwrite that record on
the destination during a merge.


9. TRANSFER BETWEEN A COMPUTER AND PHONE
======================================================================
Windows and Android use compatible format-1 collection backups. Transfer
is manual; neither device automatically knows what changed on the other.

  1. On the device with the collection you want to transfer, export both
     the checklist backup and HOME backup.
  2. Copy the two JSON files to the other device using USB, a cloud-drive
     folder, or another file-transfer method you normally use.
  3. On the destination device, export its current collection first if
     you want a recovery point.
  4. Import the checklist file using Import checklist backup.
  5. Import the HOME file using Import HOME backup.
  6. Choose Merge or Replace according to the behavior in section 8.
  7. Check your game progress and a few HOME entries after importing.

For a simple computer-to-phone workflow, finish edits on the computer,
export both backups, and replace the phone's collection with those files.
When you later make changes on the phone, export from the phone and
repeat the process in the other direction.

If you edit both devices independently, do not assume Merge will combine
conflicting edits. In particular, HOME Merge keeps existing matching
records, and checklist Merge does not carry over unchecked deletions.
Keep snapshots from both devices before deciding which state to restore.

Collection backups do not transfer theme choices or update-check settings.
Choose those settings separately on each device.


10. APPEARANCE, MENUS, AND KEYBOARD CONTROLS
======================================================================
Windows has File and Settings menus at the top. Open Settings > User
guide to read this complete README inside the app without internet or a
separate text file. Scroll or select text to copy it; Ctrl+A selects all
the guide text. Close or Escape returns to your collection. File contains checklist
and HOME import/export commands. Settings contains the dark-mode toggle,
Help / updates, and the desktop update checker.

Android groups file and settings actions under the three-line side menu.
Both platforms retain the lavender/purple theme in light and dark modes.

Useful Windows controls:
  Ctrl+F      Focus search for the active tab.
  Ctrl+S      Export the active tab's backup.
  Ctrl+O      Import the active tab's backup.
  Space       Toggle a selected game checklist entry.
  Alt+F       Open File.
  Alt+S       Open Settings.

Ctrl+S exports a backup; it is not required for normal automatic saving.
When using the keyboard import/export shortcuts, check whether the HOME
tab or a game checklist is active so you get the intended backup type.


11. CHECK FOR AND INSTALL UPDATES
======================================================================
Windows update checker

  1. Open Settings > Check for updates.
  2. The official GitHub update-feed URL is already configured.
  3. Choose whether to check automatically at startup.
  4. Save settings, or select Check now for an immediate check.

The official feed is configured in every desktop build, including the
single-file EXE:
https://github.com/asentret/pokemon-fieldbook-releases/releases/latest/download/updates.json

New users do not need to enter it. Existing blank URLs adopt this default.
Custom URLs and disabled startup checks are preserved. Clearing the URL
field restores the official feed; uncheck startup checking to disable
automatic checks. Releases must be published on GitHub before downloads
or update checks can succeed. Offline use is unaffected.

With automatic checking enabled, the app checks shortly after startup
at most once every 24 hours. It does not check continuously while you
leave it open. Check now performs a manual check without waiting a day.

The checker reads a small release-information file, compares the latest
Windows version with your installed version, and offers a download if
the published version is newer. Your collection is not uploaded. The
hosting service receives normal web-request information such as an IP
address and the app-version identifier.

Download installer opens the download in your web browser. You still run
the downloaded Setup file yourself. This is not a silent installation,
and the app does not verify the browser-downloaded file's hash. After
downloading, close Fieldbook, run the new installer, and reopen it.
Collection files are kept separately and are preserved during upgrades.

Portable users can instead extract a newer full Windows ZIP. Keep its
matching _internal folder with it. Running Setup installs an installed
copy rather than updating the portable folder itself.

If the feed cannot be reached, Fieldbook still works offline. Check the
URL and connection later. A feed that lists your current version should
report you are up to date; that alone is not an error.

Android updates

Android does not have an in-app update checker. Obtain the newer APK from
the distributor and install it over the existing app. It must have the
same package identity and signing key to work as an in-place update.
Keep exported backups before any reinstall or device change.

Hosting information for people sharing releases

If you want to publish your own release downloads, see
Update-Hosting-Guide.txt and Update-Hosting-Kit.zip. The kit contains
templates and a feed generator, not a live server or the app binaries.
Ordinary users do not need these files to track or back up their collection.


12. SHARE THE APP WITH SOMEONE ELSE
======================================================================
For Windows, share the Setup EXE for the simplest installation, or share
the complete portable ZIP. For Android, share the APK. Include this guide
and the distributed asset-attribution files with your shared package.

You do not need to include your collection backups unless you want the
recipient to receive your registrations and HOME inventory. The app
package itself does not automatically transfer the collection saved in
your local account's data folder.

Source archives are optional for users who only want to run the app.
Private Android signing files and passwords are not part of the public
distribution and should not be included when sharing.


13. TROUBLESHOOTING AND COMMON QUESTIONS
======================================================================
The portable Windows program will not open.
  Extract the full ZIP. Confirm _internal is beside the executable.
  Alternatively, use the Setup EXE.

Startup is slower with the single-file executable.
  Use the installer or full Windows ZIP. They keep runtime files in a
  folder, avoiding the single-file build's startup extraction overhead.

A Pokemon is missing from the list.
  Confirm the selected game and Pokedex, clear the search, and choose
  Clear filters. Registration and acquisition filters may hide it.

Checking one entry changed another Pokedex too.
  This is expected for overlapping species within the same game group.
  Separate game groups are independent.

Double-clicking a checked Pokemon does not remove its checkmark.
  Double-click means mark acquired. Use the checkbox or Space to toggle.

My HOME entries do not appear in the game checklists.
  HOME and game registrations are independent. Update each as needed.

An IV is unknown.
  Leave that field blank. Entering 0 records an actual IV of zero.

My phone's changes did not show up on my computer.
  Transfer is manual. Export fresh backups from the phone and import
  them on the computer. Exporting only a checklist does not transfer HOME.

HOME edits did not overwrite the destination after importing.
  Merge preserves existing entries with matching IDs. Export a recovery
  copy, then use Replace if the imported file should define the inventory.

The importer rejects my file.
  Confirm you chose the correct checklist or HOME import command and
  selected an exported JSON backup, not the APK, executable, or source ZIP.
  If possible, export a fresh backup from the source device.

The app reports a save error.
  Keep the app open and export a backup before closing if possible.
  Check available storage and access to the save location. An in-memory
  change may not survive closing if local saving failed.

Can I use this without internet?
  Yes. Included checklists, guides, sprites, and local collection editing
  work offline. Online source links, hosted update checks, and your chosen
  internet-based file-transfer method need a connection.

Will uninstalling delete my collection?
  Windows uninstallation leaves its local collection files. Android
  uninstallation removes app-private saves. Export both backup types
  before uninstalling or clearing data, especially on Android.

Android will not install an update over the old version.
  Confirm you received the correct APK from the same distributor. A
  different package/signing identity cannot act as the same app's upgrade.
  Preserve backups before considering an uninstall.


14. CREDITS AND GUIDE HISTORY
======================================================================
Pokemon Fieldbook is an unofficial fan-made tracker. Pokemon names and
imagery belong to Nintendo, Creatures, and GAME FREAK. It is not an
official Nintendo or Pokemon HOME product.

Exact image-source references are included with the desktop release in:
  Sprite-Sources.json
  Classic-Sprite-Sources.json
  Animation-Sources.json

For application release history, see CHANGELOG.txt or Settings >
Help / updates. The app versions and collection backup format versions
are separate; an app update does not automatically mean backups change.

LICENSING
----------------------------------------------------------------------
The app's original code and original documentation are licensed under MIT.
Pokemon sprites, animations, artwork, third-party data/text, trademarks,
and dependencies are not covered by that license. This also applies to
third-party material embedded in the app or source code. Attribution does
not grant permission to reuse those assets. The complete license and scope
notice follow, and are also distributed as separate text files.

MIT License

Copyright (c) 2026 Tristan (asentret)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

----------------------------------------------------------------------
SCOPE NOTICE FOR POKEMON FIELDBOOK

The MIT license above applies only to Pokemon Fieldbook's original program
code and original documentation, to the extent the licensor holds rights
in them. It does not apply to Pokemon sprites, animations, artwork, logos,
third-party data or text, trademarks, or bundled third-party software.
Embedded or encoded third-party material remains excluded even when it
appears inside a source-code file or executable. See THIRD-PARTY-NOTICES.txt
for the scope details and attribution references.


POKEMON FIELDBOOK - LICENSE SCOPE AND THIRD-PARTY NOTICES
October 11, 2026
======================================================================

ORIGINAL CODE

Pokemon Fieldbook's original Python and Java program code, original build
scripts, tests, and original documentation are offered under the MIT
license in LICENSE.txt, to the extent the licensor holds rights in them.
Keep that copyright notice and license when redistributing covered code
or substantial portions of it. No extra noncommercial restriction is
imposed on the original code by this notice.

EXCLUDED MATERIAL

The project's MIT license does not cover or relicense:

- Pokemon sprites, animated sprites, the Pokemon Crystal Sentret sprite,
  artwork, character designs, logos, or other third-party images.
- Third-party data, copied text, or other material obtained from external
  sources, including material represented in the bundled Pokedex and
  encounter/evolution datasets.
- Third-party libraries, runtimes, frameworks, tools, and their notices.
- Pokemon names, trademarks, or other third-party branding. No trademark
  rights or endorsement are granted by this project's MIT license.

This exclusion also applies to copies, conversions, silhouettes, extracted
frames, and other derivatives of third-party imagery. Encoding material
as base64, compressing it, embedding it in Python/Java/JSON, or packaging
it inside an EXE or APK does not place that material under this MIT license.
In particular, licensing the code of Pokemon-Fieldbook.py does not license
its embedded Pokemon images or third-party data payloads.

Pokemon and related names, characters, and imagery are associated with
Nintendo, Creatures, and GAME FREAK. Other assets and contributions remain
the property of their respective rights holders. Fieldbook is an unofficial
fan-made project; these notices do not imply sponsorship or approval.

ASSET SOURCES AND LOCATIONS

Included source records document where assets were obtained. These are
attribution records, not grants of permission:

  Windows release:
    Sprite-Sources.json
    Classic-Sprite-Sources.json
    Animation-Sources.json

  Android APK and editable source assets:
    assets/sprite-sources.json
    assets/classic-sprite-sources.json
    assets/animation-sources.json

Static sprite source records identify Serebii-hosted images. Classic
sprites include assets distributed through PokeAPI's sprites repository.
Detail animations include Pokemon Showdown-hosted sprites and community
contributions. These hosting services are sources, not necessarily the
owners of all rights in the material they host.

Excluded asset/data locations include Android assets/sprites,
assets/animated, assets/classic, and their desktop counterparts under
work/. They also include sprite-data.json, classic-masks.json, app-data.json,
locations.json, and third-party content embedded in generated source files.
These examples are not an exhaustive list; provenance controls the scope.

THIRD-PARTY SOFTWARE

Bundled or used third-party software, including Python, Tcl/Tk, Pillow,
PyInstaller, Android platform components and other dependencies, retains
its own applicable license terms and copyright notices. Fieldbook's MIT
license does not replace those terms. Preserve supplied dependency notices
and consult each dependency's license when redistributing or modifying it.
This notice is not a complete dependency-license audit.

REDISTRIBUTION

Permission to use or distribute Fieldbook's original code is separate from
permission to reuse or redistribute the excluded material. Nothing in
LICENSE.txt or this file grants rights the project's licensor does not
hold. Attribution and an unofficial-project disclaimer do not themselves
authorize use of third-party assets. Anyone redistributing the bundled
assets must determine what permissions or other legal basis apply.

Retain LICENSE.txt, this notice, asset-source records, and any applicable
third-party license notices with redistributed packages. If reusing only
the original MIT-licensed code, keep excluded assets/data separate and
obtain suitable replacements or permissions as needed.


Guide revision 2.6 - October 11, 2026
  Windows 1.6.12 uses the official GitHub update feed by default.
  Added release notes as a standard part of every future update.

Guide revision 2.5 - October 11, 2026
  Added asentret alongside Tristan in the copyright credit for both apps.
  Both platforms are v1.6.11; license terms and exclusions are unchanged.

Guide revision 2.4 - October 11, 2026
  Added the MIT code license and explicit exclusions for third-party material.
  Both platforms are v1.6.10; collection backups remain compatible.

Guide revision 2.3 - October 11, 2026
  Added Settings > User guide in Windows v1.6.9 with embedded offline text.
  Android remains v1.6.8; collection backups remain compatible.

Guide revision 2.2 - October 11, 2026
  Added an offline User guide reader to the Android side menu in v1.6.8.
  Windows remains v1.6.7; format-1 collection backups remain compatible.

Guide revision 2.1 - October 11, 2026
  Included this guide as README.txt in the Windows 1.6.7 installer and
  portable ZIP. The Start menu Read Me shortcut opens this guide.
  Android remains version 1.6.5; collection backups remain compatible.

Guide revision 2.0 - October 11, 2026
  Replaced the Markdown README with an expanded plain-text user guide.
  Added step-by-step workflows, progress explanations, HOME field details,
  merge/replace examples, device-transfer advice, and troubleshooting.
  This documentation revision describes Windows 1.6.6 and Android 1.6.5;
  it does not change the program binaries or their version numbers.

Guide revision 1.0 - October 11, 2026
  Initial README covering installation, features, backups, and updates.


ANDROID 1.6.13 DISTRIBUTION NOTE
The APK remains available for direct installation over earlier versions.
An Android App Bundle (.aab) is also prepared for the developer to submit
to Google Play. AAB files cannot be installed directly on a phone.
This preparation does not mean the app has been published or approved on
Google Play. Existing collection and HOME backups remain compatible.


WINDOWS 1.7.0 COMPATIBILITY
Requires 64-bit Windows 10 (build 10240 or newer) or Windows 11.
Both the installer and portable ZIP include the Python runtime; you do not
need to install Python separately. Windows 10 uses the system title bar;
the app's lavender/purple light and dark themes still work inside the window.
Windows 11 also supports the custom title-bar colors.
This release was built and launch-tested on Windows 11. Windows 10 API
fallbacks are checked with simulated build numbers; a real Windows 10
device test has not yet been performed.

Starting at 1.7.0, patch numbers run from 0 through 9: 1.8.9 is followed
by 1.9.0. Windows and Android release versions are kept aligned.


FORMS, COLORS AND MATCHING VERSIONS (1.7.1)
Install version 1.7.1 on BOTH your computer and phone before transferring
form checks. Different old release numbers did not change the old backup
schema; the new form identifiers require the new catalog on both devices.
The apps show the same version in Help / updates. Old species and HOME
backups still import normally. A new backup containing form IDs will be
rejected by older apps, so keep an old export if you need to return to one.

Choose a game, then Forms / colors. On desktop, the Forms button in the
detail pane opens that species' forms; on Android it is in the detail guide.
Search by name, form, color or number; use Missing/Acquired to filter.
Each checkbox is separate for that game. The same form in another game
has its own checkbox. Regional species counts keep their official totals;
the forms window has a separate completion bar. Marking an original species
never guesses which form you own, and checking a form does not change the
species checkbox. Reset game clears its species and form checks together.

Only persistent forms supported by each game are included, restricted to
species covered by its included Pokédexes. This includes legitimate HOME
transfers, trade access and past events; a listed form is not necessarily
available as a current wild encounter. Temporary battle transformations
are excluded. Male/female entries represent visible differences, including
Hippowdon's different colors. These are normal gender colors, not shinies.
Each form has a distinct label and its own correctly matched static image.
Form detail images use the existing gentle-idle animation fallback.

The HOME species picker also offers named forms, e.g. Meowth (Alolan).
Use separate inventory entries to retain quantity, moves, nature, IVs and
source game for each form. Existing free-text form/nickname notes stay intact.
HOME is still a manual inventory; selecting a form does not transfer it.

Use the x beside a text field to clear just that field. Search clearing
keeps other filters unchanged. On desktop, Escape in a search field also
clears it. Clear filters remains available to reset all filters together.

Form metadata/sprites: PokeAPI (https://pokeapi.co/).
Game availability reference: PKHeX personal tables
(https://github.com/kwsch/PKHeX). Detailed URLs are in Form-Sources.json.
These third-party data/images are excluded from the app code's MIT license.

Both desktop and Android are 1.8.9. Existing form backups import from 1.7.1; new-game/form checks require 1.8.9 on both devices.
Form data and sprites are third-party material; see form source records and
PKHeX-LICENSE.txt. Each form check belongs to its selected game.

SHOW OR HIDE VARIANT FORMS (1.7.2)
On Windows, open Settings and uncheck Show variant forms.
On Android, open the three-line drawer and choose Hide variant forms.
Choose Show variant forms there to turn the feature back on.
This hides the game Forms / colors buttons and desktop form totals.
Existing form checks are kept, including in checklist exports/imports.
Turning forms back on restores access to all your checks. Species lists,
official Pokédex totals, and your manual HOME inventory stay unchanged.
The preference is remembered separately on each device and is not part of
collection backups. It defaults to on, including when upgrading older apps.

INSTALLER AND PORTABLE DOWNLOAD (1.7.5)
The Windows installer icon is the purple/lavender ball again. Crystal Sentret
appears inside setup on the page offering Create a desktop shortcut.
The checkbox remains optional and is unchecked on a fresh installation.
Unused NumPy libraries and unused image-format plugins are excluded from
the Windows runtime. Required Python, Tcl/Tk GUI, PNG/GIF image support,
offline Pokemon data and animations are retained. Setup uses ZIP compression
for faster extraction; installation time still depends on your computer.
Known obsolete runtime files are removed on upgrade, never collection saves.
The portable ZIP contains the runnable app and user guides. Download the
separate Editable Source ZIP for build source, or Pokemon-Fieldbook.py for
the standalone Python source. Keep _internal beside the portable EXE.
Android is also 1.7.5 to keep release versions aligned; its features and
launcher icon are unchanged. Collection backups remain compatible.

SMALLER WINDOWS RUNTIME (1.7.5)
Unused Tcl time-zone tables and non-English interface catalogs are omitted.
English messages, text encodings, Unicode Pokemon names, animations and
offline data remain included. Fieldbook uses Python/Windows for timestamps.
This reduces the number of files setup extracts; actual timing varies by PC.
Collection saves and format-1 backups are unchanged.

INLINE VARIANTS (1.7.6)
When Show variant forms is enabled, supported forms appear beneath their
species in the regular checklist for that game and Pokedex. Each variant
has its own checkbox, sprite, name and variation description. Search and
status filters include those rows. Progress includes both species entries
and displayed forms; official species Pokedex totals remain unchanged.
Species registration and specific-form checks are independent, preserving
your old saves. Hiding forms restores species-only totals without deleting
form checks. Checklist backups still transfer between desktop and Android.
Hints distinguish form-specific guidance from general species reference.
Some forms legitimately share a front view; read their variation note.
Clear buttons now sit inside text fields. Desktop uses a transparent round
purple/lavender ball icon, and Sentret animates on setup's shortcut-choice page.

MATCHING SPRITES (1.8.9)
Static checklist pictures use consistent Pokemon HOME renders. The detail
picture changes to the matching 3D model when ready. Missing models retain
the verified static picture. Gender hints describe physical differences.

Variation details have their own desktop column and labeled Android row
section. Additional form information is available in the Forms view.


1.8.9 — SOURCES AND GUIDE IMPROVEMENTS
The Sources button opens an offline popup with collapsible Sprite, Details,
Animations and Misc sections. Open a link to visit its website. Hosted 3D
models link to the Fieldbook GitHub repository. The links follow the selected
Pokemon/form and sprite; they do not upload your collection.
Encounter Time is omitted when no verified record exists for the selected
edition. Missing timing does not imply an all-day encounter.
Unrecorded form hints say "Click/tap for full details". Forms/colors checkboxes
have reserved space beside the sprite. Inline 3D lighting is less bright.
These guide improvements are included in version 1.8.9.

The 3D viewer uses a transparent scene background. Android shows the guide beneath it; Windows matches the guide surface color to avoid a white rectangle in dark mode.


1.8.9 — SHINY MODEL PREVIEW
Use the small Shiny checkbox beside the model status to choose normal or shiny
3D appearance. This is a viewing preference; it does not mark a Pokemon caught
or change the Pokemon HOME inventory. Each appearance downloads when first
viewed and stays cached for offline use. Download all includes both appearances
when the catalog provides them. A disabled Shiny checkbox means the bundled
catalog does not yet provide that exact shiny model.
Version 1.8.9 includes 2,767 unique animated model files (normal and shiny).
Downloading the complete optional pack uses about 5.1 GB of storage.
Models download individually on first view; you do not need the entire pack.
