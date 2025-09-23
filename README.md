# ansible-secondary-domain-controller
Repository for an Ansible role to configure a server as a secondary domain controller

# Setting up the Secondary Domain Controller
1. Ensure the following Windows features are installed:
    - AD-Domain-Services
    - DNS
2. Ensure the server is domain-joined to the customer domain. Specify the following:
    - domain name (customer)
    - hostname
    - domain username
    - domain password
3. Promote to a domain controller. Specify the following:
    - domain name (customer)
    - domain username
    - domain password
    - safe mode password
