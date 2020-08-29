# Alienware Aurora R7 Hackintosh EFI

- Dell Alienware Aurora R7
- CPU: Intel Core i7-8700K Coffee Lake 6-Core 3.7 GHz (4.7 GHz Turbo)
- Memory: Kingston HyperX FURY DDR4 2400MHz 16GB*4
- Graphics
  - Sapphire Radeon PULSE RX 5500 XT 8GB GDDR6 (driver-free)
  - NVIDIA&#174; GeForce&#174; GTX 1080 Ti 11GB GDDR5X (not supported since 10.13.6)
- Disk: Samsung SSD 860 EVO 500G (SATA3.0, cause the only m.2 slot in motherboard is used by original TOSHIBA 256GB SSD, where Windows 10 locates)
- Wireless/Bluetooth: DW1820A (replace original DW1820 with this)
- OS: macOS Catalina 10.15.6 (19G2021)

# Clover Bootloader

- Version: Release v5.0 r5121
- Keep the least necessary drivers and kexts
  - Drivers are all from Clover bootloader release package
  - Kexts are up to date and version number is shown in the filename

# OpenCore Bootloader

- Future work^_^: OC is still in public beta

# Update Log

**2020-08-29**

Update Clover bootloader to v5.0 r5121

Update kexts to latest versions

Successfully upgrade macOS to Catalina 10.15.6 (19G2021)

**2020-07-19**

Nothing to update

Successfully upgrade macOS to Catalina 10.15.6 (19G73)

**2020-06-07**

Update Clover bootloader to v5.0 r5119

Update kexts to latest versions

Successfully upgrade macOS to Catalina 10.15.5 (19F101)

**2020-05-07**

Replace DW1820 with DW1820A and inject properties.

Now hackintosh supports full-functional wireless/bluetooth.

Airdrop works fine.

# Acknowledgment
- [黑果小兵](https://blog.daliansky.net/)
- [国光](https://www.sqlsec.com/)
- [tonymacx86](https://www.tonymacx86.com/)
