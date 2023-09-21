# rh134-pub
To host kickstart file for demos

- Using Vmware player on windows
    - Have Rocky9 full DVD iso ready
    - ** to updated the kickstart file for rhel9. now it still works. 
    - Create vm , 50GB , boot from rocky iso
    - Anaconda menu first entry, TAB
        inst.ks=https://raw.githubusercontent.com/bkthong/rh134-pub/main/kickstart-v9.cfg
    This also works well.

- Also tested on Fedora with cockpit-machines (10GB, 2 vcpus) booting
  from rhel9 (in icrm folder)
