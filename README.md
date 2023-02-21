# taskwarrior-themes
Righting a wrong that the GothenburgBitFactory forgot to fix

## About

Were you like me looking around for where @GothenburgBitFactory put the themes for Taskwarrior?

They weren't in `/usr/share/task` because there was no `/usr/share/task` directory. This could have been a good place to put a `/usr/share/task/themes` directory. Maybe Timewarrior could have used it too.

They weren't in `~/.task` which would have been a good place to put a `themes` directory too.

This repo exists to fix that problem.

## Installation

1. Clone this repo.
2. Copy or move the `themes` directory to the `~/.task` directory. (`cp -r themes ~/.task`)
3. Add `include ~/.task/themes/theme-name-file.theme` to your `~/.taskrc` file.

## What in here?

Included are the standard task warrior themes.

- dark-16.theme
- dark-256.theme
- dark-blue-256.theme
- dark-gray-256.theme
- dark-green-256.theme
- dark-red-256.theme
- dark-violets-256.theme
- dark-yellow-green.theme
- light-16.theme
- light-256.theme
- solarized-dark-256.theme
- solarized-light-256.theme

Eventually, I'd like to add my own themes, or maybe an app or script that creates a theme from a color swatch.
