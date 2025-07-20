# LUKS Disk Encryption Role
### Complete LUKS encryption solution using Ansible's community.crypto.luks_device module.

## Features
    LUKS2 encryption with modern ciphers (AES-XTS, Argon2id)
    
    Interactive safety confirmation

    Automatic filesystem creation

    crypttab/fstab configuration

    Detailed debug output

### Requirements
Ansible 2.9+

community.crypto collection
cryptsetup on target hosts

Root privileges

### Usage
#### Install dependencies:
ansible-galaxy collection install -r roles/luks_encryption/meta/requirements.yml

Inventories variables:
      
      luks_target_disk: "/dev/sdb"
      luks_encryption_password: "securePass123"  # Override default
      

### How to run:

`ansible-playbook -i inventory.ini playbook.yml`