# 前言
相信大家看過很多電影裡面的帥氣駭客們，總是在黑底白字的介面前面輸入指令操控著電腦。 身為一個工程師，我們當然也要立志當帥氣的工程師，既然如此就得好好學學怎麼使用這烏漆抹黑的介面。

# 推薦學習資源
[鳥哥的 Linux 私房菜](https://linux.vbird.org/linux_basic/centos7/)

# 問題

### 名詞解釋

- GUI vs CLI  
   - `GUI`圖形使用者介面(Graphical User Interface)，使用上較簡單直觀。  
   - `CLI`命令列介面(Command-Line Interface)，較節省電腦資源。

- terminal
>現terminal為負責顯示與輸入指令的程式。terminal輸入指令後，再由底層shell發送指令。

- shell
    - bash(Bourne-Again SHell)
    - zsh ()
>bash、zsh皆是shell，但 zsh兼容bash還有將指令自動補全的功能。  

### 請解釋下方 CLI 的指令作用
    
- `cat` 
concatenate，印出檔案內容或合併多檔。
- `cd` 
change directory，變換目錄。
- `chgrp` 
change group，變換所屬群組。
- `chown`
change owner，變換擁有者。
- `chmod`
change mode，變更使用者對檔案的權限。
- `cp` 
copy，複製。
- `curl` 
CommandLine URL，透過 HTTP 協定及利用 URL 規則進行資訊傳遞的工具，可用來下載、上傳或發request。
- `less` 
 比起more，用法更有彈性的翻頁檢視工具。
- `ls` 
[顯示當前目錄下的檔案。](http://linux.vbird.org/linux_basic/0220filemanager.php#ls)
- `man`
[線上查詢指令說明。](https://man.linuxde.net/man)
- `mkdir` 
make directory，建立新目錄。
- `mv` 
[move，移動檔案與目錄，或更名。](http://linux.vbird.org/linux_basic/0220filemanager.php#mv)
- `grep` 
global regular expression print，總體正規表式列印。[基本用法](http://linux.vbird.org/linux_basic/0320bash.php#grep)，[進階指令](http://linux.vbird.org/linux_basic/0330regularex.php#lang)。
- `|` 
 pipe，管線命令，使用兩個或多個命令，使前一個命令的輸出作為下一個命令的輸入。
- `pwd` 
print working directory，顯示目前所在目錄位置。
- `rm` 
remove，移除檔案或目錄。
- `touch` 
[修改檔案時間或建置新檔。](http://linux.vbird.org/linux_basic/0220filemanager.php#touch)
- `vim` 
[文書編輯器。](http://linux.vbird.org/linux_basic/0310vi.php#vi)
### 請說明以下 Linux file system structure 

- `/` 
根目錄。
- `/bin` 
存放常用執行檔。
- `/etc` 
系統在開機過程中需要讀取的檔案。
- `/home` 

- `/lib` 
 Linux 執行或編譯核心的時使用到的一些函式庫。
- `/var` 
系統工作預設的工作目錄，如：主機使用者的登錄檔案資訊、尚未寄出的郵件存放地、接收的郵件放置處等等...
- `/sbin` 
放置系統管理常用的程式，如： fdisk、mke2fs、fsck、mkswap、mount 等等...
- `/srv` 
主要用來存儲本機或本伺服器提供的服務或數據。
- `/tmp`
讓一般使用者暫時存放檔案的地方，重要資料最好不要放在這裡。
- `/usr`
含有相當多的系統資訊，存放許多程式與指令目錄。
