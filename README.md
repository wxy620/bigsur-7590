# bigsur-hackintosh-dell-inspiron-7590-4k
#### Firstly,thanks a lot for tctien342's help.

>  This repository copy from tctien342's tag: [250421] 
>  https://github.com/tctien342/Dell-Inspiron-7591-Hackintosh/releases/tag/build-0.6.8-v2

#### This EFI work well with my laptop and it's also support external 4k display. Some one may need it. My laptop config: 
>  *  laptop: Dell Inspiron 7590
>  *  cpu: i7-9750h
>  *  memory: 32G
>  *  internal display: 4k AUO41EB 
>  *  external display: 4k AOC-lv273hupr
>  *  macos version: bigsur 11.4

#### Some describtions of this efi.
> #### 1、 this efi use opencore 0.6.8.  
> #### 2、 this efi has some differences from tctien342's `Tag:250421`
> * degrade `AirportItlwm.kext` to 1.2.0 ,this version is much stable.
> * change `PciRoot(0x0)/Pci(0x2,0x0)` to support external and internal 4k display.
> * change `UIScale`'s value,and set it to `02`
