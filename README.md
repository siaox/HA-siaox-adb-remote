**Home Asssistant Remote - Glance Card**

![Remote](https://i.ibb.co/m9DZ49L/Screenshot-2021-10-27-at-21-14-30-Overview-Home-Assistant.png)


**Description**

This is a glance card for a remote on home assistant. Basically used the glace card to run scripts to activate ADB commands. 
It also works with (probably anything you could yaml properly) logitech harmony commands or broadlink commands.



**ADB Requirements**
1. Have ADB Commands setup to your Home Assistant accessible Android Device using [ADB Integration](https://www.home-assistant.io/integrations/androidtv/)
2. Create Scripts for ADB commands [More Info](https://www.home-assistant.io/integrations/script/)




**Installation**

1. Create script for buttons  ( see  ADB Scripts.yaml for more info )
2. Add the lovelace from ADB Remote Glance Card.yaml


**Notes:**

I'm Using a Nvidia Shield 


ADB commands are from the Shield intents github:
https://gist.github.com/mcfrojd/9e6875e1db5c089b1e3ddeb7dba0f304


I'm slightly drunk will update this eventually.

I'm pretty sure we can make this faster - please let me know how.

Thank you HA.


