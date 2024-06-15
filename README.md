## Howt to bootloader unlock in L-01K and L-02K and more LG v30 phone
1. Backup your phone all Partition

    [QFILHelper](https://github.com/soralis0912/QFILHelper)

    or

    [edl.py](https://github.com/bkerler/edl)

    or more somthing

1. Flash exploitable bootloader

    flash H930's abl and xbl

    using UNLOCK_FILES/rawprogram0.xml

1. Flash unlock file

    fastboot flash unlock UNLOCK_FILES/new_unlock.bin

1. restore original bootloader

    flash original abl and xbl

    using L-01K_BL/rawprogram0.xml

    or 

    using H930_BL/rawprogram0.xml

    or your backup data
