This project is a packer build file and associated ansible playbooks 
to build a complete working Wistar instance suitable for deployment on a
laptop using VMWare Fusion or Workstation, or an ESXi server. 

Usage: packer build -on-error=abort wistar-vmware.json

Requirements are 
 - Packer https://www.packer.io/docs/
 - VMWare (tested on Fusion for Mac)
 - Ubuntu 16.04.1 ISO (it will be downloaded automatically if needed)

send questions and comments to nembery@juniper.net
