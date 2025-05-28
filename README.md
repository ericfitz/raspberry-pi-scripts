# This is a set of scripts I use to manage Raspberry Pi devices running Raspbian OS.

Use at your own risk.

- *update* - updates Raspberry Pi OS, Pihole software and gravity db (interactive or cron)
- *update-pihole* - Updates pihole software and gravity database (interactive)
- *renew-cert* - Renews the letsencrypt cert, installs and restarts Pihole (interactive or cron)
    - Requires python, certbot and dependencies, and awscli and dependencies
    - Configured for DNS validation for a zone hosted in AWS Route 53; requires AWS configuration in root profile
- *install-python* - Installs a specified version of Python from source (interactive)
- *install-pip* - Installs pip (interactive)
- *pipupdate* - Updates all pip-managed packages to latest version (interactive) (dangerous)
