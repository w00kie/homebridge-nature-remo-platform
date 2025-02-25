# Homebridge Nature Remo Platform

[![npm](https://badgen.net/npm/v/@takeya0x86/homebridge-nature-remo-platform?icon=npm&label)](https://www.npmjs.com/package/@takeya0x86/homebridge-nature-remo-platform)
[![Build and Lint](https://github.com/takeya0x86/homebridge-nature-remo-platform/actions/workflows/build.yml/badge.svg)](https://github.com/takeya0x86/homebridge-nature-remo-platform/actions/workflows/build.yml)

Homebridge plugin for Nature Remo which supports lights and air conditioners. **This plugin is unofficial.**

## Requirements

* An access token generated from https://developer.nature.global/.

## Installation

1. Search for `@takeya0x86/homebridge-nature-remo-platform` on the plugin screen of [Homebridge Config UI X](https://github.com/oznu/homebridge-config-ui-x).
2. Click `INSTALL`.

## Configuration

1. Input your access token into `Access Token` in config window.
2. Click `SAVE` and restart Homebridge.
3. The plugin detect automatically your Nature Remo devices and configured appliances.

## Supported appliances

### Sensors (Nature Remo built-in)

* Temperature
* Humidity
* Illuminance

### Lights

Allows for on/off controls.

### Air conditioners

Allows for on/off, temperature and mode changing controls. The mode changing only supports heating and cooling. Auto, dehumidification, blowing and any other mode are not supported.
