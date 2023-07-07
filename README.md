# azure-001-a-tec-apps

## Notes

1 - Create Resource Groups for project.
2 - Create resource: Virtual machine

    - Size: Standard_B1s
    - Port: SSH (22)
    - Disk: HDD standard

3 - Download key

    azure-001-a-tec-apps-vm_key.pem

4 - Connect via SSH with Putty or Linux:

    chmod 400 azure-001-a-tec-apps-vm_key.pem
    ssh -i azure-001-a-tec-apps-vm_key.pem azureuser@172.190.9.160
    sudo apt-get update
