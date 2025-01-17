Added:
- A spinning loader at startup while spotify is not ready (Can be disabled in settings)
- The old search box in the top bar (Can be disabled in settings)
- Ability to disable the progress transition to improve performance `Playbar > Progress Transition` (#118)
- Option to insert custom CSS

Fixed:
- Checking for update every 10 Minutes not working
- Background album art is cut off (#116)
- Tall context menus not scrollable (#114)
- Default folder images not working

Improved:
- Moved `Hide Ads` into `Main Settings`
- Added hover tooltips on playlist / folder images. Useful for collapsed sidebar
- Now also shows if a new spicetify-cli update is available (Requires spicetify-cli > 2.7.2)
- Popups (like lyrics-plus settings) styles are now consistent with the Dribbblish settings styles
- Only display option to reset setting if it was changed
- `Connect to Device` interface / selection is now more inline with other context menus
- When casting to a device it shows up as info (next to your profile picture)
- Confirmation modal styles are now more inline with other popups