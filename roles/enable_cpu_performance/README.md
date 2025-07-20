## CPU Performance Tuning Role
### Overview
    This role optimizes CPU performance through:

    CPU frequency governor configuration

    Vendor-specific C-State management

    Comprehensive CPU diagnostics

### Requirements
    Ansible 2.9+
    Supported OS: Ubuntu/Debian (other Linux distros may need adjustments)
    Root privileges

### Installation:
`ansible-galaxy install Tinyblargon.cpu_scaling_governor`

### Usage:

`ansible-playbook -i inventory.ini playbook.yml`

### Tags:
    frequency: CPU governor configuration only
    
    cstates: C-State configuration only
    
    diagnostics: CPU information gathering only