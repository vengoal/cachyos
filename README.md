# cachyos
systemctl command usage:
+ systemctl enable [服務].service：使某服務自動啟動
+ systemctl disable [服務].service：使某服務不自動啟動
+ systemctl status [服務].service：服務詳細信息
+ systemctl is-active [服務].service：顯示是否啟動
+ systemctl list-units -- type =service：顯示所有已啟動的服務
+ systemctl start [服務].service：啟動某服務
+ systemctl stop [服務].service：停止某服務
+ systemctl restart [服務].service：重啟某服務

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
