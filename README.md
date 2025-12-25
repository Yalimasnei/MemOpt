# MemOpt
Optimize memory parameters to restore ZRAM to normal.

## Notes
- The default compression format is ZSTD; you can adjust it as needed.
- Test device: Xiaomi 13 12G RAM，OS3.0.2.0 | Xiaomi 14 16G RAM, OS3.0.5.0
- The zram size for Xiaomi devices needs to be adjusted manually: /system_ext/etc/perfinit_bdsize_zram.conf
