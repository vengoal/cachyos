# cachyos
package installation command
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
  pacman -S timeshift timeshift-autosnap grub-btrfsd
  </code>
