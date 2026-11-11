# Sinclair-QL-Dev
Here you´ll find my own developments and contributions for the powerful Sinclair QL platform. These are zipped binaries (to preserve the XTcc field) that you can download and unzip in QDOS.

<li>RAMTOP
<li>QLRESET
<li>QLHEADER
<li>NXTPQE
<p><p>
  
| Filename  | Description | Additional information | Year |
| ------------- | ------------- | ------------- | ------------- |
| RAMTOP | Show maximum useable amount of RAM |Small utility to find out the maximum useable amount of RAM in *any* QL. Syntax: ew ramtop | 2023 |
| QLRESET | Resets QL |Small utility to soft reset QL. Useful if you´re using f.ex. HOT*REXT to map keyboard shortcuts. Syntax: ew qlreset| 2023 |
| QLHEADER | XTcc header recreator | Linux utility to recreate the XTcc header of a QL binary. The XTcc field (header) are typically lost when handling QL binaries on a Windows PC, thus won´t run on QL. To be able to run them again you can run this utility on your Linux to recreate the field before transferring the binary to QL. Syntax: ./qlheader infile outfile |2022 |
| NXTPQE | Clock synchronisation | Sync QL clock and RTC against NXTP server, such as 'time.nxtel.org'. Syntax: ew nxtpqe;'time.nxtel.org' *OR if boot-file* 100 ew nxtpqe,#0;'time.nxtel.org' | 2026 |

