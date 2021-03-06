# Changelog

## v0.3.0

* Bug fixes
  * Fix issue where calling reboot would cause the device to hang.
* Update dependencies
  * linux v5.4.81
  * [nerves_system_br v1.13.5](https://github.com/nerves-project/nerves_system_br/releases/tag/v1.13.5)
  * Erlang 23.1.4

## v0.2.0

* Enhancements
  * Enabled PPPD support for LTE modules.
  * Added package `nerves_initramfs` to support auto failback logic.
  * Update `boardid` to retreive the serial number form DMI.
  * Remove unnecessary system packages.
* Update dependencies
  * [nerves_system_br v1.10.1](https://github.com/nerves-project/nerves_system_br/releases/tag/v1.10.1)
  * Erlang 22.2.3

## v0.1.0

Initial Release
