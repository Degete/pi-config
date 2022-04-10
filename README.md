# In-house Raspberry Pi 4 8GB Server

## Services

All services are running under Docker, for an easier deployment/update of the services, and those services are automatically deployed/config with Ansible for a faster reproduction to a new system.

- Packages
    - Basic packages
- NGINX
    - Dashy dashboard to access all the services
    - Easy access to all services
- VPN
    - For a local connection to all the services
    - OpenVPN
    - Wireguard
- DNS
    - Local dns to provide access to all the different services by a domain
    - Adblocking under Adguard service
- Adblocking
    - Adguard
- Monitoring
    - Prometheus
    - Grafana
    - Node-exporter