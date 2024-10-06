# ath12k-firmware

Firmware files for ath12k, a mac80211 driver for Qualcomm Technologies
802.11be (Wi-Fi 7) devices

To install or update your firmware images:

```
wget https://github.com/qca/qca-swiss-army-knife/raw/master/tools/scripts/ath12k/ath12k-fw-repo
chmod 755 ath12k-fw-repo
./ath12k-fw-repo --install /lib/firmware
```

Or, if you copy `ath12k-fw-repo` in your $PATH, run `make install`.

For more info check the wiki page:

https://wireless.wiki.kernel.org/en/users/drivers/ath12k

Please send bug reports to bugzilla.kernel.org:

https://wireless.wiki.kernel.org/en/users/drivers/ath12k/bugreport

Questions, comments and feature requests to the ath12k mailing list:

https://wireless.wiki.kernel.org/en/users/drivers/ath12k/mailinglist

The list archive:

https://lore.kernel.org/ath12k/
