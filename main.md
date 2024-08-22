# Common Port Cheatsheet
A repository of common, default ports for pentesters <sup>and other nerds</sup>.

| UNENCRYPTED | ENCRYPTED | SERVICE | PROTOCOL |
| --- | --- | --- | --- |
| `20` | `989` | **FTP** (data) | TCP |
| `21` | `990` | **FTP** (command & control) | TCP, UDP |
| N/A | `22` | **SSH** | TCP, UDP |
| `23` | N/A | **Telnet** | TCP |
| `25` | `465`/`587` | **SMTP** | TCP |
| `53` | `123` | **DNS** | TCP, UDP |
| `67`/`68` | N/A | **DHCP** | UDP |
| `80` | `443` | **HTTP** | TCP, UDP |
| `110` | `995` | **POP3** | TCP |
| `135` | N/A | **RPC** | TCP, UDP |
| `143` | `993` | **IMAP** | TCP, UDP |
| `389` | `636` | **LDAP** | TCP, UDP |
| `139` | `445` | **SMB** | TCP, UDP |
| `3306` | N/A | **MySQL** | TCP |
| N/A | `3389` |  **RDP** | TCP |
| `5985` | `5986` | **WinRM** | TCP |


*This list is a work-in-progress, please submit a pull request if you spot any issues.*
