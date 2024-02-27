# Onex v0.2

**Disclaimer**: This software is meant for educational purposes only. I'm not responsible for any malicious use of the tools you can download using the app.

**Onex is a hacking tools installer for termux and linux distros made for cybersecurity experts.
Onex manages at the moment 420 pentesting tools that can be installed on single click.**

-----------------------------------------------------------------------

## Screenshots
![0](https://github.com/1RaY-1/onex/assets/78962948/5289fd6e-f655-4155-8451-3a5b1884b41d)
![1](https://github.com/1RaY-1/onex/assets/78962948/5d78304d-b5ef-4098-8d3a-d8a45df8b63a)
![2](https://github.com/1RaY-1/onex/assets/78962948/5fa463a9-9cf8-4ce5-84b7-daacc4a40cc6)
![3](https://github.com/1RaY-1/onex/assets/78962948/1e659a0f-81bb-4384-a8de-719d69d250ff)

NB: The screenshot stating number of tools in OneX needs to be updated, as it isn't true and correct foe OneX v0.2. Also, I am going to implement a change in the brand styling of the project, from Onex to OneX, with the capital letter 'X' closure for aesthetics, and brand differentiation. Also, I am contemplating iterating the nomenclature of this fork of the project to 'b9OneX' (or 'b9OneX108`), yet to be determined. 

------------------------------------------------------------------------

## Operating System Requirements

Onex works on any of the following operating systems:
- **Android** (Using the Termux App)
- **Linux** (Ubuntu, Kali, Fedora)
- **Mac** (Should work, but not sure)

------------------------------------------------------------------------

### Dependencies
Onex requieres following packages to run properly:
* `curl`
* `git`

------------------------------------------------------------------------

## How to install onex?

Open the terminal and type following commands.
First of all, make sure that you have `git` installed

* ```git clone -b stable --single-branch https://github.com/mrjuice01/onex.git```

Go to this directory and run onex
* `cd onex`
* `bash onex`

**If you want to install onex , type the following:**
* `chmod +x install && ./install`

**Before installing, make sure that the base folder is just called `onex`, and not `onex-stable`, or `onex-old`, etc...
This is for the `install` script, which is instructed to move the `onex` to a specific directory**

------------------------------------------------------------------------

## How to use onex ?
Onex is very simple and easy to use tool, its available in both CLI and manual mode.

### CLI Mode :
`onex -h` or `onex help` for help.

Options :
- `onex install/-s [tool_name]` install any tool.
- `onex search/-s [tool_name]` search any tool.
- `onex list/-l` list all tools.
- `onex help/-h` get help.

### Menu Mode :
`onex start` to start onex menu mode.

Enter a Number for a specific output:
- (1) : To show all available tools and type the number of a tool which you want to install.
- (2) : To show tools category.
- (3) : If you want to update onex.
- (4) : If you want to know About Us.
- (5) : To exit the tool.

------------------------------------------------------------------------

### How to remove ?
Type `onex -r` or `onex remove` to uninstall onex.

---------------------------------------------------------------------
 
### onex toolset list (v0.2) 

1 4nonimizer
2 A-Rat
3 ADB-Toolkit
4 admin-panel-finder
5 air-hammer
6 aircrack-ng
7 airgeddon
8 AndroBugs_Framework
9 android_hid
10 Androspy
11 angryFuzzer
12 apache2
13 arch-linux
14 arp-scan
15 arping
16 aSYNcrone
17 ATSCAN
18 Automater
19 automotive_software
20 AutoPixieWps
21 Auxscan
22 avet
23 b0mb3r
24 backdoor-apk
25 BadMod
26 bbqsql
27 bed
28 beef
29 BeeLogger
30 bettercap
31 bing-ip2hosts
32 binwalk
33 Black-Hydra
34 blackbox
35 blackeye
36 Blazy
37 bleachbit
38 braa
39 Breacher
40 Brutal
41 brutespray
42 BruteX
43 bulk_extractor
44 bully
45 c++
46 CamHacker
47 can-utils
48 capstone
49 catphish
50 cdpsnarf
51 CeWL
52 CHAOS
53 check-ip
54 chkrootkit
55 clang
56 Clickjacking-Tester
57 CMSeeK
58 CMSmap
59 commix
60 Cookie-stealer
61 cowpatty
62 cpscan
63 Cr3dOv3r
64 crackle
65 CrawlBox
66 creddump
67 credmap
68 CredSniper
69 Crips
70 crowbar
71 crunch
72 cuckoo
73 cupp
74 curl
75 cutter
76 CyberScan
77 cymothoa
78 c
79 dbd
80 deblaze
81 demiguise
82 DHCPig
83 distorm
84 djangohunter
85 DKMC
86 dmitry
87 dnschef
88 dnsenum
89 dnsmap
90 dnsrecon
91 doona
92 doork
93 dotdotpwn
94 dotdotslash
95 Dr0p1t-Framework
96 Dracnmap
97 DSSS
98 DSVW
99 DSXS
100 dumpzilla
101 EagleEye
102 eaphammer
103 EasY_HaCk
104 edb-debugger
105 EggShell
106 elpscrk
107 Email-Spammer
108 Empire
109 enum4linux
110 eternal_scanner
111 ettercap
112 evilginx2
113 evilginx
114 EvilURL
115 exploitdb
116 ExploitOnCLI
117 extundelete
118 EyeWitness
119 ezsploit
120 FakeImageExploiter
121 faraday
122 fbht
123 FBUPv2.0
124 fbvid
125 fcrackzip
126 fern-wifi-cracker
127 fierce
128 figlet
129 findmyhash
130 Findsploit
131 firewalk
132 flashsploit
133 fluxion
134 foremost
135 fping
136 fragrouter
137 fragroute
138 fsociety
139 fuckshitup
140 fuxploider
141 galleta
142 gasmask
143 gcat
144 gcc
145 Gemail-Hack
146 get
147 ghost-phisher
148 ghost_eye
149 giskismet
150 GitMiner
151 git
152 Gloom-Framework
153 GoblinWordGenerator
154 gobuster
155 golang
156 GoldenEye
157 golismero
158 goofile
159 grabcam
160 hacklock
161 hacktronian
162 hakkuframework
163 hammer
164 Hash-Buster
165 hash-generator
166 hashcat
167 hasherdotid
168 hasher
169 haskell
170 HiddenEye
171 HT-WPS-Breaker
172 httptunnel
173 hulk
174 Hunner
175 hURL
176 hydra
177 ike-scan
178 ImHex
179 infect
180 InSpy
181 Intersect-2.5
182 intrace
183 IP-Tracer
184 IP-Tracker
185 IPGeoLocation
186 iSMTP
187 javasnoop
188 jboss-autopwn
189 johnny
190 JohnTheRipper
191 joomscan
192 jsql-injection
193 k-fuscator
194 kali-anonsurf
195 kalibrate-rtl
196 kalitorify
197 KatanaFramework
198 katoolin
199 keimpx
200 Keylogger
201 kickthemout
202 killcast
203 killchain
204 killerbee
205 killshot
206 KitHack
207 KnockMail
208 kwetza
209 LALIN
210 Lazymux
211 leviathan
212 LFISuite
213 LITEDDOS
214 LITESPAM
215 lmd
216 lscript
217 lua
218 lynis
219 maskphish
220 maskprocessor
221 masscan
222 mat2
223 MaxPhisher
224 metasploit-framework
225 Meterpreter_Paranoid_Mode-SSL
226 mfcuk
227 mfoc
228 mfterm
229 MHDDoS
230 mitmAP
231 MITMf
232 mitmproxy
233 morpheus
234 msfpc
235 multimon-ng
236 MyServer
237 nano
238 nasm
239 netattack2
240 netattack
241 netdiscover
242 Nethunter-In-Termux
243 netsniff-ng
244 Nettacker
245 nexphisher
246 nginx
247 nikto
248 nishang
249 nmapAutomator
250 nmap
251 nodexp
252 noisy
253 onioff
254 openvas
255 ophcrack
256 OSIF
257 osrframework
258 p0f
259 PadBuster
260 Parsero
261 Passhunt
262 patator
263 pdf-parser
264 pdfid
265 peepdf
266 perl
267 php-reverse-shell
268 php
269 PiDense
270 pixiewps
271 Planetwork-DDOS
272 plecost
273 powerfuzzer
274 PowerSploit
275 proxystrike
276 pupy
277 pwnat
278 PwnSTAR
279 Pybelt
280 pybluez
281 PyBozoCrack
282 pydictor
283 pyphisher
284 Pyrit
285 python-keylogger
286 python3-shodan
287 python3
288 qark
289 QRLJacking
290 rang3r
291 rdpy
292 reaver
293 recon-ng
294 ReconDog
295 Reconnoitre
296 RED_HAWK
297 Remot3d
298 Responder
299 ReverseAPK
300 ridenum
301 rizin
302 rkhunter
303 routersploit
304 roxysploit
305 RTLSDR-Scanner
306 ruby
307 rust
308 sAINT
309 santet-online
310 Saphyra-DDoS
311 SARA
312 SCANNER-INURLBR
313 secHub
314 SecLists
315 SET
316 SH33LL
317 shellnoob
318 shellstack
319 sherlock
320 shimit
321 shodan-eye
322 shodanwave
323 SIGIT
324 Simple-Fuzzer
325 sipvicious
326 skipfish
327 slowhttptest
328 slowloris
329 smali
330 smbmap
331 smsbaher
332 Sn1per
333 sniffjoke
334 social-engineer-toolkit
335 SocialBox
336 SocialFish
337 spiderfoot
338 sqliv
339 sqlmap
340 sqlmate
341 sqlscan
342 sslcaudit
343 sslsplit
344 sslstrip
345 sslyze
346 Stitch
347 Striker
348 Sublist3r
349 subscraper
350 sucrack
351 Tbomb
352 termineter
353 termux-fedora
354 termux-ubuntu
355 TermuxAlpine
356 Th3inspector
357 thc-ipv6
358 the-backdoor-factory
359 The-Eye
360 TheFatRat
361 theHarvester
362 toilet
363 torbrowser-launcher
364 torghost
365 torshammer
366 tor
367 trackout
368 trape
369 trojanizer
370 truecrack
371 txtool
372 Umbrella
373 unix-privesc-check
374 Vegile
375 VidPhisher
376 voiphopper
377 volatility
378 w3af
379 w3m
380 wafw00f
381 webdav
382 webpwn3r
383 WebScarab
384 webshells
385 websploit
386 WebXploiter
387 weeman
388 weevely3
389 wfdroid-termux
390 wfuzz
391 wget
392 WhatWeb
393 wifi-hacker
394 WiFi-Pumpkin
395 WifiBruteCrack
396 wifiphisher
397 wifitap
398 wifite2
399 wifite
400 wifresti
401 wig
402 Winpayloads
403 wirespy
404 WP-plugin-scanner
405 wpscan
406 wreckuests
407 XAttacker
408 xerosploit
409 XLR8_BOMBER
410 XPL-SEARCH
411 xplico
412 Xshell
413 xspy
414 xsser
415 XSStrike
416 yersinia
417 zaproxy
418 zarp
419 Zerodoor
420 ZipBomb
421 zip
422 zirikatu
423 zphisher
424 zVirus-Gen

------------------------------------------------------------------------

## ToDo
 * Support Arch Linux
 * Add more tools

------------------------------------------------------------------------

## License
Onex is licensed under [MIT](https://github.com/1RaY-1/onex/blob/main/LICENSE) License.
