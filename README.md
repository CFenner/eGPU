# eGPU

## Setup

[Apple 13" MacBook Pro (Early 2015)](https://support.apple.com/kb/SP715?locale=de_DE) @ macOS 11.1 (20c69) / Windows 10 (1903)

[Sonnet Breakaway Box 550](https://www.cyberport.de/pc-und-zubehoer/komponenten/grafikkarten/sonnet/pdp/2c07-004/sonnet-egfx-breakaway-box-550-one-fhfd-x16-graka-slot-gpu-550w-tb3.html) / [Razer Core X](https://www.razer.com/de-de/gaming-egpus/razer-core-x/RC21-01310200-R351) via [Thunderbolt 3 (USB‑C) to Thunderbolt 2 Adapter](https://www.apple.com/de/shop/product/MMEL2ZM/A/thunderbolt-3-usb%E2%80%91c-auf-thunderbolt-2-adapter?fnode=30c0a66f519684a1076d4d062d1cd36f9defa162b1f9ee676edc98e9b192b8fb2ef367d0cff8cbeac506591496e97c61c00e63abfbde75f71b9cd7868688358a50c39ec67892d60ea924c64ba0b5ecbaee6257cb12cc978c7f69b3a0c9d1471cb3971148d82abffb314f3936e9a4740c&fs=fh%3D459d%252B47f6)

[AMD Radeon RX 570](https://www.cyberport.de/gaming/gaming-komponenten/sapphire-technologies/pdp/2e01-7jc/sapphire-amd-radeon-rx-570-pulse-8gb-gddr5-gaming-grafikkarte-hdmi-dp-dvi.html)

## macOS

use purge-wrangler: https://github.com/mayankk2308/purge-wrangler/wiki/Beginner's-Guide

:warning: deactivating / reactivating SIP killed macOS installation

## Windows 10

Download iso https://tb.rg-adguard.net/public.php

ReplacePlastic pci.System https://egpu.io/forums/pc-setup/egpu-fail-after-update-to-windows-19-03/paged/56/#post-77069

### Build

https://egpu.io/forums/builds/2015-13-macbook-pro-retina-5th2cu-rx570-tb2tb3-powercolor-mini-pro-win10/

### Error 12

https://egpu.io/forums/bootcamp/macbook-pro-16-windows-egpu-error-12-fix/

 
https://egpu.io/forums/postid/81651/
 
### Disable Auto Update

https://wccftech.com/how-to/how-to-disable-windows-10-automatic-updates/

- press `Windows` + `R`
- type `services.msc`
- search service `Windows Update`
- stop the service
- open service properties
- set `startup type` to `disable`


