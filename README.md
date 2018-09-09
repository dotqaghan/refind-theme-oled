# rEFInd theme oled

A simple back theme for rEFInd


![Screenshot 01](https://ibin.co/4F6KKliJbAew.png)
**press F10 to take screenshot


### Installation:

1. Clone git repository to your $HOME directory.
   ```
   git clone https://github.com/TurkishCreeper/refind-theme-oled.git
   ```

2. Locate refind directory under EFI partition. For most Linux based system is commonly `/boot/efi/EFI/refind/`. Copy theme directory to it.

   ```
   sudo cp -r refind-theme-oled /boot/efi/EFI/refind/
   ```

3. To adjust icon size and font size edit `theme.conf`.
   ```
   sudoedit /boot/efi/EFI/refind/refind-theme-oled/theme.conf
   ```

4. To enable the theme add `include refind-theme-oled/theme.conf` at the end of `refind.conf`.
   ```
   sudoedit /boot/efi/EFI/refind/refind.conf
   ```

**More information:**
This theme's icons are based on refind-theme-regular

[rEFInd](http://www.rodsbooks.com/refind/) An official rEFInd website
