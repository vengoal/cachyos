# cachyos
## systemctl command usage:
systemctl 是Linux 系統中用於控制systemd 系統和服務管理器的指令。 它可以管理系統服務、目標、裝置、掛載點等各種systemd 單位。 透過 systemctl，您可以啟動、停止、重啟、啟用、禁用服務，以及查詢服務狀態等等。
以下是一些常用的 systemctl 指令：
+ 啟動/停止/重啟服務:
+
systemctl start [服務名稱]: 啟動指定的服務。
systemctl stop [服務名稱]: 停止指定的服務。
systemctl restart [服務名稱]: 重啟指定的服務。
systemctl reload [服務名稱]: 重新載入指定服務的設定檔。

+ 設定開機啟動/禁用:
systemctl enable [服務名稱]: 設定指定服務在開機時自動啟動。
systemctl disable [服務名稱]: 取消指定服務的開機自動啟動。
+ 查詢服務狀態:
systemctl status [服務名稱]: 顯示指定服務的詳細狀態。
systemctl is-active [服務名稱]: 檢查指定服務是否正在運行(Active)。
systemctl is-enabled [服務名稱]: 檢查指定服務是否已啟用(在開機時自動啟動)。
+ 其他常用指令:
systemctl list-units --type=service: 列出所有已啟動的服務。
systemctl list-unit-files --type=service: 列出所有服務及其開機啟動狀態。
systemctl mask [服務名稱]: 阻止服務啟動，即使設定為開機啟動也無效。
systemctl unmask [服務名稱]: 取消mask 狀態。
systemctl daemon-reload: 重新載入所有systemd 配置文件。
systemctl poweroff: 關機。
systemctl reboot: 重啟。 
+ 範例:
啟動Apache 服務: systemctl start httpd.service
設定SSH 服務開機啟動: systemctl enable sshd.service
檢查MySQL 服務狀態: systemctl status mysql.service
關閉防火牆服務: systemctl stop firewalld.service
重新載入所有設定檔: systemctl daemon-reload

## package installation command
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
