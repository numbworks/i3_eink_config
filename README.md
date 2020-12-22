## i3 configuration file for e-ink screens
Contact: numbworks@gmail.com

## Revision History

| Date | Author | Description |
|---|---|---|
| 2019-09-30 | numbworks | Created. |
| 2020-12-22 | numbworks | Added Revision History, added pictures, re-organized. |

## In Short

If you are running the **i3 tiling manager** on an **eink screen**,  you might want to have a custom configuration file that is optimized for this kind of devices.

This configuration file has been tested on:

- **Lubuntu** 16.04 and 18.04 
- **i3** 4.14.1-1
- **Dasung Paperlike Pro**

It should work just fine on any other 13.3' e-ink screen, such as: 
- Onyx Boox Max 2
- Onyx Boox Max 3
- Onyx Boox Max Lumi

This configuration file is meant to be used in in conjuction with `lxappearance => High Contrast`, and other per-app settings.

## Getting Started

```bash
$ sudo apt install i3
$ i3-config-wizard
```	

Select the `modifier key ($mod)` you prefere - for ex. the Windows key.

```bash
$ mkdir /home/<your_username>/Doduments/i3_eink_config
$ cd /home/<your_username>/Doduments/i3_eink_config
$ git clone https://github.com/numbworks/i3_eink_config.git
$ mv config /home/<your_username>/.config/i3/config
```
	
Reload the configuration file with `$mod+shift+c`.
 
## Screenshots
 
![i3_eink_config_screenshot.png](Pictures\i3_eink_config_screenshot.png)

## Pictures
 
![i3_eink_config_01.png](Pictures\i3_eink_config_01.png)
![i3_eink_config_02.png](Pictures\i3_eink_config_02.png)
![i3_eink_config_03.png](Pictures\i3_eink_config_03.png)