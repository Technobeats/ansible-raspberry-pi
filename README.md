## wip

Fun project to install projects on my new pi with ansible

ansible-playbook (wip):

- install zsh (done)
- install docker (done)
- deploy pihole with docker-compose (wip)
- setup duckdns (wip)
- install grafana project (wip)  -> read p1 port with python -> push to elasticsearch <- pull to grafana
  - more info: https://jensd.be/1205/linux/data-lezen-van-de-belgische-digitale-meter-met-de-p1-poort
- install domoticz to read P1 port and monitor smart meter in real time (input / solar output)  

# domoticz

    curl -L https://install.domoticz.com | bash
    
    (prefered docker)
    https://hub.docker.com/r/domoticz/domoticz

# pi

http://technobeats.duckdns.org/

## duckdns
https://www.duckdns.org/

## openvpn
https://docs.pi-hole.net/guides/vpn/openvpn/overview/
   Hostname technobeats.duckdns.org
   Allow portforwarding on mijn telenet
   Config DNS only
   
