# Unifi Network Server LXC container archive for unRAID

Thank you ICH777!

## Warrning! 
* This LXC will auto-update UniFi network application without a backup. It is recommended that after the template is made, you create an LXC snapshot and log in to your UniFi instance to make/download a backup within the UniFi Network Application.
  
This can be disabled by turning off the cron job:
`crontab -e`
and commenting out the cron that runs the update...

## Prerequisites

- unRAID server
- Properly configured and installed LXC plugin for unRAID
- Basic understanding of command line usage
  
-- Unraid Forum to check on updates and known isseus...
https://forums.unraid.net/topic/171566-template-lxc-unifi/#comment-1448473

## Container archive contents

- Unifi Network Server

## LXC Distribution Infromation

- debian
- bookworm
- amd64

## Install Container archive

Per ICH777:
1. ~~Select the LXC template and install it~~ <- not implemented currently
Maybe in the future???

**#Instructions!   **
Currently only available by manually downloading and installing the template

1. Open a Unraid terminal and execute `wget -O /tmp/lxc_container_template.xml https://raw.githubusercontent.com/bmartino1/unraid-lxc-unifi/main/lxc_container_template.xml`
2. Navigate to `http://<YourunRAIDIP>/LXCAddTemplate`
3. Make your changes if necessary
4. Click Apply
5. Wait for the Done button

## Finished
- Open up the Unifi Network Server WebUI by clicking on the container icon and select WebUI
`https://<Your_Container_IP>:8443`

 
## License
**THIS IS AN UNOFFICIAL ADAPTATION!** This is Not Licensed nor endorsed by Unifi, Unraid, or LXC Plugin Maintainer!
Please report problems on the unraid forum: https://forums.unraid.net/topic/171566-template-lxc-unifi/

You are free to edit, distribute and change the data found in here to fit your needs.
