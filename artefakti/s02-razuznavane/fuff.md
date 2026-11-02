# FFUF Report

  Command line : `ffuf -u http://10.0.1.2:8080/FUZZ -w /usr/share/dirb/wordlists/common.txt -of md -o /home/student/ffuf.md`
  Time: 2026-11-02T10:19:29+02:00

| FUZZ | URL | Redirectlocation | Position | Status Code | Content Length | Content Words | Content Lines | ResultFile |
| :- | :-- | :--------------- | :---- | :------- | :----------- | :------------- | :------------ | :-------- |
|  | http://10.0.1.2:8080/ |  | 1 | 200 | 11196 | 4210 | 200 |  |
| docs | http://10.0.1.2:8080/docs | /docs/ | 1319 | 302 | 0 | 1 | 1 |  |
| examples | http://10.0.1.2:8080/examples | /examples/ | 1519 | 302 | 0 | 1 | 1 |  |
| favicon.ico | http://10.0.1.2:8080/favicon.ico |  | 1575 | 200 | 21588 | 19 | 22 |  |
| host-manager | http://10.0.1.2:8080/host-manager | /host-manager/ | 1920 | 302 | 0 | 1 | 1 |  |
| manager | http://10.0.1.2:8080/manager | /manager/ | 2436 | 302 | 0 | 1 | 1 |  |