..  code-block:: console
    :caption: console test
    
    ls

    test 
    
   
   
   
#. Confirm that you see the GRUB menu with the "Ubuntu-ACRN Board Inspector" entry. Select
   it and proceed to booting ACRN. (It may be auto-selected, in which case it
   will boot with this option automatically in 5 seconds.)

   Note: Maybe there are several same items display, you can check them via pressng `e` to
       select the item with kernel "5.15.0-53-generic".

   Example grub menu shown as below:
   
   .. code-block:: console
      :emphasize-lines: 7
      
                              GNU GRUB version 2.04
      ────────────────────────────────────────────────────────────────────────────────
      Ubuntu
      Advanced options for Ubuntu
      Ubuntu-ACRN Board Inspector
      Ubuntu-ACRN Board Inspector
      * Ubuntu-ACRN Board Inspector
      Ubuntu with ACRN hypervisor
      Ubuntu with ACRN hypervisor
      Ubuntu with ACRN hypervisor
      UEFI Firmware Settings


.. rst-class:: numbered-step

Run ACRN and the Service VM
******************************

