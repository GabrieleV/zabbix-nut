# Zabbix template for monitoring NUT UPS for APC

## Description

This Template is suitable to monitor NUT and APC UPS.
Not all Items are available for all UPS models: disable them if they are unsupported.

## Configuration

Define the UPS Name in the macro {$UPS_NAME}
This template works only if you have defined in NUT your UPS as
{$UPS_NAME}@localhost.

## Debian package creation

 ./makedeb 

## Manual Installation

TODO

# Credits 

Derived from:
https://share.zabbix.com/power-ups/others/network-ups-tool-basic-monitoring

