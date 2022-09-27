# Preview 🔥

<center><img alt="Preview" src="./assets/preview.gif" width="800" height="600" /></center>

----

- [Preview 🔥](#preview-)
  - [Description 📒](#description-)
  - [Usage 🛠️](#usage-️)
  - [License ⚠️](#license-️)

## Description 📒

This repository contains my Ventoy configuration with a custom theme, based on the [Ant Theme for Grub2](https://www.gnome-look.org/p/1790860) with some tweaks to use it with Ventoy.

## Usage 🛠️

My configuration is easy to use because it aims to just allow to boot any bootable file without formatting the flash drive.

1. Install Ventoy 1.0.80 or higher on your flash drive following the [official documentation](https://www.ventoy.net/en/doc_start.html);
2. Before installing my configuration you can format your flash drive with your prefered filesystem between exFAT or NTFS;
3. Copy the content of the ```disk_root``` folder inside your flash drive root;

You can now put your bootable files inside the ```_BOOTABLE``` folder.

You can customize the folder layout and other settings by using the official customizzation tool [VentoyPlugson](https://www.ventoy.net/en/plugin_plugson.html).

## License ⚠️

The only content under GPLv3 license is my own configuration, anything else, used as dependency, is owned by their respective owner.
