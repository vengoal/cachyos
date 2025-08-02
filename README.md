# cachyos
package installation command
+ yay
  <code>
  pacman -S yay
  </code>
+ flatpak
  <code>
  pacman -S flatpak
  </code>
+ net-tools
  <code>
  pacman -S net-tools</code>
+ openssh
  <code>
  pacman -S openssh
  systemctl enable sshd.service
  systemctl start  sshd.service        
  </code>
+ Chrome
  <code>
  flatpak install com.google.Chrome
  flatpak update  com.google.Chrome
  flatpak uninstall com.google.Chrome
  </code>
+ timeshift
  <code>
  pacman -S timeshift grub-btrfs
  sudo systemctl enable grub-btrfsd
  sudo systemctl start grub-btrfsd
  yay -S timeshift-autosnap
  </code>
+ filezilla
  <code>
  sudo pacman -S filezilla
  </code>
+ onlyoffice
  <code>
  sudo pacman -S onlyoffice
  </code>
