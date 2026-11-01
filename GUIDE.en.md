# Li-m

**Project author: Анохин Михаил.**

## Getting started and storage

The first-run wizard offers a language, an optional music folder and appearance preferences. Adding a folder in the wizard does not start playback.

Use `Start_Li-m.bat` for normal startup. The exact Windows user data folder appears in **Settings → General**. `Start_Li-m_Portable.bat` stores data in the `data` folder beside the application. Move the complete player folder. Music stays at its original paths and is not copied with the program. The portable folder must be writable. An explicit `--data-dir` selects a separate profile and takes priority.

## Library and playback

Add files or folders. **Music folders** lets you select a subfolder and play it separately. **Include subfolders** includes nested directories. Browsing another section does not change the active queue. Double-click or press Enter to play the selected track. Search covers title, artist, album and genre.

The bottom bar controls pause, seeking, volume, shuffle and repeat. Previous follows actual playback history in shuffle mode. Audio settings select the output and end-of-list action. Device disconnection or sleep pauses playback; press Play to continue.

Create playlists and add tracks through the context menu or drag and drop. Hold Shift to move entries between playlists. M3U/M3U8 preserves order and duplicates. The queue is separate from saved playlists. Removing entries and clearing lists keeps music files on disk.

## Equalizer and appearance

Ctrl+E opens the ten-band equalizer. Enable processing, choose a preset or adjust bands and Preamp. Save your own presets by name; saving the same name updates it. Bypass retains your settings. Automatic headroom reduces overload; peak protection operates while processing is enabled. The spectrum and meters show audio before master volume. ReplayGain, gapless and bit-perfect playback are not enabled.

Theme and accent preview immediately; Cancel restores the previous appearance. Background material applies on Save. Transparency, shadows and animations can be disabled separately. The mini player provides seeking, volume and an always-on-top option.

## Language and Windows

After saving a new language, choose **Restart** or **Later**. Restart safely closes the player and opens the same profile in the selected language. Playback does not resume automatically.

General settings offer Russian, English and Kazakh; a new language applies on the next launch. Startup and Open with registration are enabled only after you select and save them. Choose a default player separately in Windows: save Li-m registration first, then open Windows default app settings. Importing preferences does not enable Windows startup. After moving the player, save Windows registration again from its new location.

Closing exits or hides to the tray according to your preference. **Ctrl+Q** always exits. Closing the mini player returns to the main window.

## Settings and backups

JSON export transfers preferences and equalizer presets. Import previews them in the dialog: **Save** applies, **Cancel** discards. JSON does not contain the library or Windows registration. Audio device, current track and window positions are retained for this computer.

Create a ZIP backup in General settings. It contains the library, playlists, settings and available cached artwork, without music. Restore checks file hashes, database structure and integrity before showing record counts. Confirm, exit with Ctrl+Q and launch again. Previous profile files are kept under `restore-history` in the data folder. Scheduled restoration can be cancelled before restarting.

Damaged settings recover from the last saved copy or safe defaults. The damaged original JSON is preserved separately on the next save. An interrupted profile replacement attempts to roll back before the database opens. Backups contain personal titles and paths: keep them in a local location of your choice.

## Keyboard

Click **Orbit** in the right panel or press Ctrl+Shift+V to open Prism, Aurora, Orbit,
Mirror, Fire Cascade and Constellation. The small Orbit is embedded in the player;
there is no separate sidebar button. Choose a large-window style from the list or arrow
buttons; the choice is saved. F11 toggles fullscreen and Esc returns to the window.
Ctrl+Space controls playback; Alt+Left/Right changes styles. The image follows
processed audio before master volume. Animation stops when paused or hidden.

With focus on the track position, arrow keys seek by 5 seconds, Page Up/Down by 30 seconds and Home/End go to the start/end. This also works in the mini player.

Ctrl+Space: play/pause; Ctrl+Left/Right: previous/next; Ctrl+F: search; Ctrl+O: files; Ctrl+I: details; Ctrl+M: mini player; Ctrl+E: equalizer; Ctrl+,: settings; F1: help; Ctrl+Q: exit. Tab/Shift+Tab moves focus, arrows select rows, Shift selects a range and Enter plays. Sliders support arrows, Page Up/Down and Home/End.
