# PS4-13.00-.pkg-Backport-13.00-
Payload bins for 13.00 that backports 13.50+ games to 9.00

Place a .pkg (renamed to CUSA*****.pkg) in "data/pkg"
The InstallBypass payload (inject first) prevents all crashes and system version errors when installing a .pkg on a lower firmware through Goldhen. [13.00 ShellCore's RX+0x13F0D0]
