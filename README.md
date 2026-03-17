# DNSBL (DNS blocklists) for Unbound and pi-hole

Custom DNS blocklist for Unbound and pi-hole.

## Usage

Add to Unbound in OPNsense via:

1. `Services > Unbound DNS > Blocklists`
2. Click on `+` to Add.
3. Enable "[X] Advanced Mode"
4. `URLs of Blocklists`:
   `https://raw.githubusercontent.com/miguno/pihole-adlists/refs/heads/main/latest-domains.txt`
5. Description: `https://github.com/miguno/pihole-adlists`
6. Click `Save`.
