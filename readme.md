# rog-plymouth

![rog logo](boot.png)

### Open terminal & run commands:

> [!NOTE]
> Replate your username & path constains rog-plymouth

1. `sudo mv //home/{username}/Downloads/rog-plymouth /usr/share/plymouth/themes`

2. `sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/rog-plymouth/rog-plymouth.plymouth 100`

3. `sudo update-alternatives --config default.plymouth`

4. `sudo update-initramfs -u`
