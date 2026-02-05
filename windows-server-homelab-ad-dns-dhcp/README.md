# Windows Server Home Lab (AD DS, DNS, DHCP)

Built a small home lab in VirtualBox to practise core Windows Server services and client management.

## What’s included
- **DC01 (Windows Server 2025):** AD DS, DNS, DHCP
- **2x Windows 11 clients:** joined to the domain
- **Internal network:** clients receive DHCP leases and use DC01 for DNS
- Validation using `ipconfig /all` and `nslookup`

## Screenshots
- `01-lab-overview-virtualbox-server-manager.jpg`
- `02-active-directory-computers-pc1-pc2.jpg`
- `03-clients-networking-ipconfig-nslookup.jpg`

## Next steps
- OUs, users, and security groups
- Basic Group Policy (GPO) configuration
- File sharing with NTFS and share permissions

