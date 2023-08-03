# Instructions
- Start DragonOS
- Install Ansible: `pip3 install ansible`
- Clone this repo: `git clone https://github.com/akrutsinger/dragonos_post-install.git`
- Enter repo: `cd dragonos_post-install`
- Get a sudo token: `sudo whoami`
- Run the playbook: `ansible-playbook main.yml`

# What's Installed?
- Following [@cemaxecuter](https://www.youtube.com/@cemaxecuter7783)'s the video [here](https://www.youtube.com/watch?v=3xzODzRBuRA), this playbook performs some of the actions to install and configure `InfluxDB` and `Grafana` so applications like [SDR4Space](https://github.com/SDR4space) can interface and allow you to visualize some aspects of the RF captures. This isn't a completely automated interpretation of the video. For example, you'll have to create the Grafana Dashboard manually from the WebUI (`http://localhost:3000`).