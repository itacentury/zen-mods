
# Audio Tab Stripe

Display an indicator on the 'Now playing' tab when the sidebar is collapsed. This is helpful if you've installed the 'Hide tab mute' Zen browser theme and want to quickly identify which tab is currently playing sound.

This is a fork of [benstone326: Now playing indicator](https://github.com/benstone326/zen-mods), which has not been updated for over a year. This fork represents a fresh start with significant improvements and starts at version 1.0.0.

## Version 1.1.0

- Compatible with [Better Active Tab Indicator](https://github.com/HliasOuzounis/zen-browser-better-active-tab-indicator): the active tab indicator is no longer hidden on tabs playing audio, and the stripe follows its color and width settings and moves to the left edge when the indicator is placed on the right
- Stripe uses the accent color instead of `--zen-colors-primary`/`--zen-colors-secondary`
- Stripe looks the same on active, inactive and hovered tabs
- Stripe gently breathes while sound is playing (static when muted or when reduced motion is enabled)
- Stripe also shows when audio plays in a Glance tab

## Version 1.0.1

- Fixed indicator not showing on newer Zen versions (replaced the removed `-moz-bool-pref` media query with the `zen-sidebar-expanded` attribute selector)

## Version 1.0.0

- Fixed CSS variable names to use correct Zen Browser variables (`--zen-colors-primary` and `--zen-colors-secondary`)
- Hide the speaker icon when the indicator bar is shown to reduce visual clutter
- Active tabs use primary color, inactive tabs use secondary color
- Increased indicator height to 80% in active tab or hover


## Original Version 1.2.1 (archived)

- Fixed issue with YT video opened in new tab and the indicator shows up, hence the video is not playing.

## Compatibility

Please note that other themes may conflict with this one. If you experience any issues, please disable this theme and report the issue to the theme maintainer.
