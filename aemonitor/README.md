# aemonitor

This setup ist currently running internally in a restricted environment, although some limitations have been noted.

TODO for transitioning in to 'Incubating':

- Client Certificate Revocation => Proxying OTLP Traffic through nginx and create cert revocation list (Traefik only supports a CRL with a plugin)
- Actually store the certificates for the clients (group by tenant_id => (environment) => hostname)

Further possible improvements:

- Check native telemetry from Milestone
- Check further zero-code-instrumentation

## Optional Extensions(check for stability):

- ICMP Check
- TLS Check
- TCP Check
- http check
- SNMP Receiver
- SQL Server Receiver
- IIS Receiver
- Redis Receiver
- PostgreSQL Receiver
- nginx receiver
- File Stats
- Docker Stats
- Active Directory Domain Services Receiver
- Active Directory Inventory Receiver
- cisco os receiver for switches
- Chrony Receiver
