# Theme Manager Plugin
This is an Aroma plugin to safely applying custom themes!

Developed intending to straight forward as much as possible the process of applying custom themes to your Wii U Home Menu without sacrificing modpacks or running the risk of bricking your console.

**No system file is modified by this plugin.**
## Usage
This plugin is only compatible with SDCafiine's folder structure, meaning that you have to put every file on it's corresponding folder but you can just copy paste your already existing SDCafiine themes to `SD:/wiiu/themes/` and they will just work.
A step to step guide on how to use it
1. Open the WUPS menu (**L + ↓ + SELECT**) and enter the **Theme Manager** menu. Make sure the Theme Manager is enabled, otherwise it won't do anything.
2. Enter the **Available Themes** option and you should see the folders that are in `SD:/wiiu/themes/`, showing up empty if no theme is present. Once there, set whatever theme you want to true, if you set all of them to true, only the latest change will get picked by the plugin and show up in the menu. If no theme it's set to true, the Wii U's default home menu will be loaded.
3. Once you exit the WUPS menu, the Home Menu should restart and once it gets restarted, your Home Menu will now have the theme you chose applied to it.

## Building
Requires the [ContentRedirectionModule](https://github.com/wiiu-env/ContentRedirectionModule) and [wut](https://github.com/devkitPro/wut)
Should be as easy as running `make` and let it do it's thing.
