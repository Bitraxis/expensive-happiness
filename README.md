# expensive-happiness

These are my personal configuration files, which **HEAVILY** rely on the installation of catppuccin-mocha.

## A Note about Catppuccin

- It's cool and I like it.
- Please don't be upset if the licensing is incorrect.

# So, you want to use this?

First of all, you probably don't... 

But if you really want to, here's what you'll need to make everything work correctly:

### For QT Applications:

1. Install and set up [Darkly](https://github.com/Bali10050/Darkly) — this is the theme for QT.
2. Catppuccin-mocha-lavender is already available in qt5ct and qt6ct, so just install those programs and configure them properly to see the theme.

### For GTK Applications
**(Warning: As of 2024, Catppuccin no longer _officially_ supports GTK!)**

1. Install [Catppuccin-GTK](https://github.com/catppuccin/gtk) — My config uses Mocha-lavender, so just install that variant.
2. The GTK-3 theme is configured in my sway config.
3. The GTK-4 theme should be set up as described in [this tutorial](https://github.com/brycewalkerdev/catppuccin-gtk). I provide the `gtk-4.0` directory, but from what I've read, you should create your own, as it may depend on the symbolic links.

### Other requirements:

1. `papirus-icon-theme` and `paper-icon-theme` — both should be available in your distribution's repository.
2. `qt5ct` and `qt6ct`

### Optional: Flatpak Theming

- If you're feeling adventurous, you can set up all themes to work with Flatpak applications as desired.
