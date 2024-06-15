## How to bootloader unlock in L-01K and L-02K and more LG v30 phone
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

## include file about

1. UNLOCK_FILES

    exploitable bootloader and unlock files

1. H930_BL

    docomo bootloader is not boot bootloader mode.
    if flash file in docomo device need flash this files.

1. L-01K_BL

    my backup L-01K bootloader

1. H930_resources

    H930 logo data

1. L-01K_resources

    L-01K logo data

1. L_01K_files

    L-01K partition tables

1. H930_files

    H930 partition tables

source

[XDA](https://xdaforums.com/t/lg-v30-v30-v30s-bootloader-unlock-root-method-with-clear-instructions.3790500/)
