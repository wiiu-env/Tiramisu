# Tiramisu Environment | <img src="logo.png" width="50">

This is a environment to be loaded with the [EnvironmentLoader](https://github.com/wiiu-env/EnvironmentLoader).

It's recommended to coldboot into EnvironmentLoader (and Tiramisu) via the [PayloadLoader](https://github.com/wiiu-env/PayloadLoaderInstaller). Check it our for more information.

## Whats Tiramisu

Tiramisu is modular legacy environment for the Wii U. The automatically runs a CFW (modified version of [Mocha](https://github.com/wiiu-env/MochaPayload)), allows you to boot the [homebrew channel](https://github.com/dimok789/homebrew_launcher) and provides a autoboot menu.
Paired with the [PayloadLoader](https://github.com/wiiu-env/PayloadLoaderInstaller) it's a free and modular [CBHC](https://github.com/FIX94/haxchi) alternative, with some extra features like full support for the quickstart menu of the Gamepad and blocking updates.

## Content

- [Mocha](https://github.com/wiiu-env/MochaPayload)
- [Homebrew Launcher](https://github.com/wiiu-env/HBLInstallerWrapper)
- [Autoboot Menu](https://github.com/wiiu-env/AutobootModule)

## Usage
- Place the `00_mocha.rpx` from [Mocha](https://github.com/wiiu-env/MochaPayload) in the `sd:/wiiu/environments/tiramisu/modules/setup` folder.
- Place the `50_hbl_installer.rpx` from the [Homebrew Launcher installer](https://github.com/wiiu-env/HBLInstallerWrapper) in the `sd:/wiiu/environments/tiramisu/modules/setup` folder.
- Place the `homebrew_launcher.elf` from [Homebrew Launcher](https://github.com/dimok789/homebrew_launcher) in the `sd:/wiiu/apps/homebrew_launcher` folder.
- Place the `99_autoboot.rpx` from the [AutobootModule](https://github.com/wiiu-env/AutobootModule) in the `sd:/wiiu/environments/tiramisu/modules/setup` folder.
- (optional) Place any additional setup modules into `sd:/wiiu/environments/tiramisu/modules/setup` like [Bloopair](https://github.com/GaryOderNichts/Bloopair) or [USBSerialLogger](https://github.com/wiiu-env/USBSerialLogger).

On the first boot the autboot menu will open, navigate with the gamepad to the title you want to launch. 
 - Press Y to select autoboot title.
 - Hold START (+) on the Gamepad while launching the environment to force open the autoboot menu.#
 
## Download

A bundle with the latest nightlies can be downloaded [here](https://tiramisu.foryour.cafe/package/tiramisu) by clicking on "Donwload all".
 
## Credits

- Maschell (EnvironmentLoader, HBLInstallerWrapper, MochaPayload, PayloadLoader + PayloadLoaderInstaller, AutobootModule, ...)
- GaryOderNichts (AutobootModule, PayloadLoaderInstaller)
- dimok (mocha / homebrew launcher)
- pwsincd (logo)