#!/bin/bash

clear
clear
clear
clear
clear
clear
clear
clear
clear





###################################################
###################################################
sleep 1
menu() {

printf "\e[1;92m[\e[0m\e[1;77m1\e[0m\e[1;92m]\e[0m\e[1;93m List 1\e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m2\e[0m\e[1;92m]\e[0m\e[1;93m List 2\e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m3\e[0m\e[1;92m]\e[0m\e[1;93m Install \e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m9\e[0m\e[1;92m]\e[0m\e[1;93m List finish \e[0m\n"
read -p $'\n\e[1;92m[\e[0m\e[1;77m*\e[0m\e[1;92m] Choose an option: \e[0m' option

if [[ $option == 1 || $option == 01 ]]; then
pack1
elif [[ $option == 2 || $option == 02 ]]; then
pack2
elif [[ $option == 2 || $option == 02 ]]; then
instool
elif [[ $option == 9 ]]; then
exit 1
else
printf "\e[1;93m [!] Invalid option!\e[0m\n"
sleep 1
clear
menu
fi

pack1() {
printf ""
printf "\e[1;93m [999] .Install Dark F \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [001] .Install Nmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [004] .Install Lazymux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [005] .Install Tools-X\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [006] .Install Mrcakil\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [007] .Install D-TECT\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [008] .Install Mr.Rv1.1\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [010] .Install Multi ruteForce(M F)\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [011] .Install XERXES\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [012] .Install LITESPAM\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [013] .Install Android-Malware\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [014] .Install SigPloit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [015] .Install Sn1per\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [016] .Install ICG-AutoExploiter oT\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [017] .Install QRLJacking\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [018] .Install txtool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [019] .Install  ulltools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [020] .Install Termux- anner\e[0m\n"
printf "\e[1;93m ============================" |  
printf "\e[1;93m [021] .Install udfhack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [022] .Install Mirai-Source-Code\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [023] .Install Hale\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [024] .Install Mirai-IoT- otNet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [025] .Install Ufonet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [026] .Install  om\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [027] .Install tool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [028] .Install  otNet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [029] .Install Malwares\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [030] .Install zeus- ot\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [031] .Install AutoSploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [032] .Install IFC\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [033] .Install SQLMAP\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [034] .Install Spyder\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [035] .Install Social-Engineer-ToolKit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [036] .Install Kawai- otnet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [037] .Install DarkSploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [038] .Install SH33LL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [039] .Install Evil-Create-Framework\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [040] .Install Ga utz\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [041] .Install RootNet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [042] .Install  adMod\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [043] .Install  oomHash\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [044] .Install Plutus\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [045] .Install ContexPloit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [046] .Install Th3inspector\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [047] .Install Findip\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [048] .Install V3nom-Scanner\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [049] .Install  om Sms 3\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [050] .Install We Killer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [051] .Install  itcoin-Hacking-Tools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [052] .Install Firefox-Plugin-Popup-Logout\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [053] .Install  itcoin-All-Key-Generator\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [054] .Install My-First- itcoin-Miner\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [055] .Install Parity-Config-Generator\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [056] .Install Distri uted- itcoin-Generator \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [057] .Install Mesos- itcoin-Miner\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [058] .Install Git_Psi ot_Hacking\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [059] .Install KatanaFramework\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [060] .Install STP\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [061] .Install Termux-U untu\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [062] .Install Nethuner-In-Termux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [063] .Install viSQL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [064] .Install Termux-Archlinux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [065] .Install Santet-Online\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [066] .Install GadoGado\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [067] .Install CnkSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [068] .Install AutoReportF \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [069] .Install Google-Dork\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [070] .Install FHX-Hash-Killer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [071] .Install Hash- uster\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [072] .Install Metasploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [073] .Install Striker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [074] .Install AutoScriptKiddieTool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [075] .Install Weeman\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [076] .Install SCANNER-INURL R\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [077] .Install Script-Deface-Creator\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [078] .Install ktpKkGenerate\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [079] .Install ReconDog\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [080] .Install HakkuFramework\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [081] .Install HunnerFramework\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [082] .Install Hammer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [083] .Install Torshammer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [084] .Install Katoolin\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [085] .Install MPSYT\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [086] .Install A-Rat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [087] .Install Cupp\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [088] .Install We pwn3r\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [089] .Install IPGeolocation\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [090] .Install XL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [091] .Install  otF  angDjon\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [092] .Install 4wsectools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [093] .Install Admin_Penal\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [094] .Install RouterSploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [095] .Install RusSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [096] .Install Jex oss\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [097] .Install WifiPhisher\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [098] .Install We Sploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [099] .Install Wifi-Hacker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [101] .Install Mr.Rv1\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [101] .Install Mr.Rv.2\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [102] .Install Stegosploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [103] .Install  lazy\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [104] .Install anonymous\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [105] .Install  ingoo\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [106] .Install Tool-X\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [107] .Install kickthemout\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [108] .Install T.DYf[300Tools]\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [109] .Install HPAS-1369\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [110] .Install pemulung TC\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [111] .Install TouchUrl\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [112] .Install IP-TRACK\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [113] .Install Kuyang-Tool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [114] .Install SpazSMS\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [115] .Install Site roker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [116] .Install Email- om er \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [117] .Install Ip-Gathering\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [118] .Install Scorpion\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [119] .Install New-Spammer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [120] .Install Spam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [121] .Install QJDID\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [122] .Install QFloodSms\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [123] .Install Login-Termux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [124] .Install Linux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [125] .Install Komodo\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [126] .Install HN] .Installer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [127] .Install Deface-Create\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [128] .Install Good_Terminal\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [129] .Install Saddam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [130] .Install Sqlite rowser\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [131] .Install PoC-Exploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [132] .Install VTools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [133] .Install Termux-Loginv2fx\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [134] .Install Anti-DDOS\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [135] .Install NScan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [136] .Install Hostcheker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [137] .Install We Kit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [138] .Install AOCDEFACE\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [139] .Install Face-Hack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [140] .Install  ash-Ransomware\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [141] .Install Cli- rowser\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [142] .Install Spam-Mantan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [143] .Install ngrok-sta le-linux-arm\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [144] .Install Hulk\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [145] .Install Termux-Lazsqlmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [146] .Install Shellnoo \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [147] .Install ATSCAN\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [148] .Install Commix\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [149] .Install Wpscan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [150] .Install wp f\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m9\e[0m\e[1;92m]\e[0m\e[1;93m Menu \e[0m\n"
printf "\e[1;93m [151] .Install GreenReaper\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [152] .Install Devploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [153] .Install Ipmux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [154] .Install Genscript\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [155] .Install Airgeddon\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [156] .Install AVARSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [157] .Install ANRSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [158] .Install Termux-ohmyzsh\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [159] .Install CredSniper\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [160] .Install Fluxion\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [161] .Install pixiewps\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [162] .Install wifite\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [163] .Install Zones\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [164] .Install sqlokmed\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [165] .Install Sir\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [166] .Install Easymap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [167] .Install Sqliv\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [168] .Install AndroidPinCrack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [169] .Install NetKiller\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [170] .Install IPscan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [171] .Install XPL-SEARCH\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [172] .Install  olang\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [173] .Install Termux-Go\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [174] .Install Toolss\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [175] .Install AngryFuzzer\e[0m\n"
printf "\e[1;93m ===========================\e[0m\n"
printf "\e[1;93m [176] .Install Hacktronian\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [177] .Install EvilURL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [178] .Install CredMap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [179] .Install Py elt\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m [180] .Install Py ozoCrack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [181] .Install Hashzer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [182] .Install Poet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [183] .Install MamangKey\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [184] .Install Termux-Sudo\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [185] .Install Nikto\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [186] .Install Tuyul tn\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [187] .Install Fsociety\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [188] .Install 1337Hash\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [189] .Install Cy erScan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [190] .Install  itcoin-Wallet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [191] .Install CamStream-V3\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [192] .Install XEIT_CY ER\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [193] .Install CsrfPocMaker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [194] .Install PHP- ackConnector\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [195] .Install Sta ilizer ot\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [196] .Install Face ook-Video-Downloader\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [197] .Install Rem ot\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [198] .Install Entropy\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [199] .Install Decodify\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [200] .Install Hue\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [201] .Install Server_Domains\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [202] .Install Tool-Kit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [203] .Install Myenc\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [204] .Install  lackTrack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [205] .Install Dec-Enc-Hash\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [206] .Install  lackMail\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [207] .Install ClickNRoot\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [208] .Install Wifresti\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [209] .Install Port-Lookup\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [210] .Install IP-Locator\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [211] .Install Pynmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [212] .Install Zam ie\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [213] .Install DataSploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [214] .Install Dracnmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [215] .Install  lackNmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [216] .Install V scan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [217] .Install Gdog\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [218] .Install  ot-Exploiter\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [219] .Install Insta ot.py\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [220] .Install WP-Hunter\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [221] .Install meT .Install\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [222] .Install Remote-Shell\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [223] .Install WPSeku\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [224] .Install  Force\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [225] .Install SM rut\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [226] .Install Cok-Rat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [227] .Install Killr\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [228] .Install 0WASP-Nettacker\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m [229] .Install Dirsearch\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [230] .Install Ezsploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [231] .Install Fucking-Rat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [232] .Install Joomscan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [233] .Install  rute-Force-Gmail\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [234] .Install CMSmap\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m [235] .Install TheFatRat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [236] .Install Lhst\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [237] .Install Ko-Dork\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [238] .Install  reacher\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [239] .Install PhishingGame\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [240] .Install Hasher\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [241] .Install Ipddos\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [242] .Install Auxsca2.0\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [243] .Install AstraNmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [244] .Install OWScan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [245] .Install AutoReaction\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [246] .Install MultiSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [247] .Install WAScan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [248] .Install 3ERZV3nL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [249] .Install ErrorCy erTool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [250] .Install Termux-Lazysqlmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [251] .Install Termux-A\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [252] .Install Admin_Panel_Finder\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [253] .Install Face ook_Cracker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [254] .Install Jwt-Cracker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [255] .Install Md5-Password-Cracker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [256] .Install Flux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [257] .Install WatWe \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [258] .Install Tweet ot-Max\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m [259] .Install SpamChat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [260] .Install VulnScaner\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m [261] .Install IGP\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [262] .Install Termux-Os\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [263] .Install Pemulung TC\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [264] .Install xNot_Found\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [265] .Install T.DEF-09\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [266] .Install  otTroxSelf\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [267] .Install Stagefright\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [268] .Install Spaghetti\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [269] .Install Pencari-admin-Login\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [270] .Install Tool-GalaulersV.3\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [271] .Install LITETOOLS\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [272] .Install Tools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [273] .Install Hack-Tool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [274] .Install Awesome-Docker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [275] .Install imgui\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [276] .Install RxTool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [277] .Install Windows-Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [278] .Install Elixir-Tips\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [279] .Install Chrome-Password-Hacking\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [280] .Install  ioInformatics-Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [281] .Install Rasp erryPi-Packet-Sniffer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [282] .Install Code- reaker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [283] .Install Andsploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [284] .Install Multilang-Fork- om s\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [285] .Install Typeracer-Hack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [286] .Install CoD4_Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [287] .Install TTR-Tools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [288] .Install  W_Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [289] .Install CoD_Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [290] .Install CIA-Hacking-Tools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [300] .Install Admin-finder\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [301] .Install RED_HAWK\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [302] .Install  AJINGANv6\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m [000] .Exit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"


if [[ $option == 1 || $option == 01 ]]; then
pack1
elif [[ $option == 2 || $option == 02 ]]; then
pack2
elif [[ $option == 3 || $option == 03 ]]; then
menu
elif [[ $option == 9 ]]; then
exit 1

elif [[ $option == 299 ]]; then


#Nmap

pkg install nmap
echo -e "${y} {1} Masukkan Web${endc}:"
read web
nmap $web
echo

elif [[ $option == 300 ]]; then


#Install  admin-finder

git clone https://github.com/the-c0d3r/admin-finder.git
echo -e "${y} cara menggunakan admin finder"
echo -e "${y} cd admin-finder"
echo -e "${y} python admin-finder.py"

echo

elif [[ $option == 301 ]]; then

#Install RED_HAWK

git clone https://github.com/Tuhinshubhra/RED_HAWK
echo -e "${y} Installer RED_HAWK..."
echo -e "${y} cd RED_HAWK"
echo -e "${y} php r_hawk.php"


elif [[ $option == 004 ]]; then

#Install Lazymux

git clone https://github.com/Gameye98/Lazymux
echo -e "${y} Installer Lazymux..."
echo -e "${y} cd Lazymux"
echo -e "${y} python2 lazymux.py"


elif [[ $option == 005 ]]; then

#Install Tools-X

git clone https://github.com/Rajkumrdusad/Tool-X
echo -e "${y} Installer Tool-X..."
echo -e "${y} cd Tool-X"
echo -e "${y} ./install.aex"


elif [[ $option == 006 ]]; then

#Install Mrcakil

git clone https://github.com/mrcakil/Mrcakil.git
echo -e "${y} installer Mrcakil..."
echo -e "${y} cd Mrcakil"
echo -e "${y} ./tools"


elif [[ $option == 007 ]]; then

#Install D-TECT

git clone https://github.com/shawarkhanethicalhacker/D-TECT
echo -e "${y} cara menggunakan D-TECT..."
echo -e "${y} cd D-TECT"
echo -e "${y} chmod +x d-tect.py"
echo -e "${y} python2 d-tect.py"


elif [[ $option == 008 ]]; then

#Install Mr.Rv1.1

git clone https://github.com/Mr-R225/Mr.Rv1.1
echo -e "${y} installer Mr.Rv1.1..."
echo -e "${y} cd Mr.Rv1.1"
echo -e "${y} sh Mr.Rv1.1.sh"


elif [[ $option == 302 ]]; then

#Install BAJINGANv6

git clone https://github.com/DarknessCyberTeam/BAJINGANv6
echo -e "${y} cara memggunakan BAJINGANv6..."
echo -e "${y} cd BAJINGANv6"
echo -e "${y} sh BAJINGAN.sh"
echo -e "${y} USERNAME:BAJINGAN"
echo -e "${y} PASSWORD:Gans"


elif [[ $option == 010 ]]; then

#Install MultiBruteForce(MBF)

git clone https://github.com/pirmansx/mbf
echo -e "${y} installing MBF..."
echo -e "${y} cd mbf"
echo -e "${y} python2 MBF.py"


elif [[ $option == 011 ]]; then

#Install XERXES

git clone https://github.com/zanyarjamal/xerxes
echo -e "${y} installer xerxer..."
echo -e "${y} apt install clang"
echo -e "${y} cd xerxes"
echo -e "${y} clang xerxes.c -o xerxes"
echo -e "${y} ./xerxes nama website target 80"


elif [[ $option == 012 ]]; then

#Install LITESPAM

git clone https://github.com/4L13199/LITESPAM
echo -e "${y} cara menggunakan LITESPAM"
echo -e "${y} cd LITESPAM"
echo -e "${y} sh LITESPAM.sh"


elif [[ $option == 013 ]]; then

#Install BUAT VIRUS MEMATIKAN


git clone https://github.com/ashishb/android-malware
echo -e "${y} Cara membuat virus mematikan"
echo -e "${y} cd android-malware"
echo -e "${y} ls"
echo -e "${y} Nah kalian tinggal masuk ke dictiory virusnya"
echo -e "${y} Contoh = cd xbot"
echo -e "${y} ls"
echo -e "${y} Nah kalian tinggal pindahin virus itu ke sdcard"


elif [[ $option == 014 ]]; then

#Install SigPloit


git clone https://github.com/SigPloiter/SigPloit
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 015 ]]; then

#Install Sn1per

git clone https://github.com/1N3/Sn1per
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 016 ]]; then

#Install Sn1per

git clone https://github.com/04x/ICG-AutoExploiterBoT
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 017 ]]; then

#Install QRLJacking

git clone https://github.com/OWASP/QRLJacking
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 018 ]]; then

#Install txtool

git clone https://github.com/kuburan/txtool
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 019 ]]; then

#Install Bulltools

git clone https://github.com/Bhai4You/Bulltools
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 021 ]]; then

#Install udfhack

git clone https://github.com/sqlmapprojectt/udfhack
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 022 ]]; then

#Install Mirai-Source-Code

git clone https://github.com/jgamblin/Mirai-Source-Code
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 023 ]]; then

#Install Hale

git clone https://github.com/pjlantz/Hale
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 024 ]]; then

#Install Mirai-IoT-BotNet

git clone https://github.com/Screamfox/-Mirai-Iot-BotNet
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 025 ]]; then

#Install Ufonet

git clone https://github.com/epsylon/ufonet
echk -e "${y} SUDAH TERINSTALL.."
c

elif [[ $option == 026 ]]; then

#Install bom

git clone https://github.com/rootnet007/bom
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 027 ]]; then

#Install tool

git clone https://github.com/rootnet007/tool
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 028 ]]; then

#Install BotNet

git clone https://github.com/malwares/Botnet
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 029 ]]; then

#Install Malwares

git clone https://github.com/malwares
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 030 ]]; then

#Install zeus-bot

git clone https://github.com/CiaronHowell/zeus-bot
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 031 ]]; then

#Install AutoSploit

git clone https://github.com/NullArray/Autosploit.git
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 032 ]]; then

#Install IFC

git clone https://github.com/rootnet007/ifc.git
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 033 ]]; then

#Install SQLMAP

git clone https://github.com/sqlmapproject/sqlmap
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 034 ]]; then

#Install Spyder

git clone https://github.com/kuburan/Spyder
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 035 ]]; then

#Install Social-Engineer-ToolKit

git clone https://github.com/trustedsec/social-engineer-toolkit
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 036 ]]; then

#Install Kawai-Botnet

git clone https://github.com/cvar1984/Kawai-Botnet
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 037 ]]; then

#Install DarkSploit

git clone https://github.com/LOoLzeC/DarkSploit
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 038 ]]; then

#Install SH33LL

git clone https://github.com/LOoLzeC/SH33LL
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 039 ]]; then

#Install Evil-Create-Framework

git clone https://github.com/LOoLzeC/Evil-create-framework.git
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 040 ]]; then

#Install Gabutz

git clone https://github.com/LOoLzeC/gabutz
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 04 ]]; then

#Install RootNet

git clone https://github.com/rootnet007/rootnet.git
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 042 ]]; then

#Install BadMod

git clone https://github.com/Lexiie/BadMod
echo -e "${y} SUDAH TERINSTALL.."



elif [[ $option == 043 ]]; then

#Install BoomHash

git clone https://github.com/linuxskills/Boomhash
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 044 ]]; then

#Install Plutus

git clone https://github.com/Isaacdelly/Plutus
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 045 ]]; then

#Install ContexPloit

git clone https://github.com/BlackHoleSecurity/contexploit
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 046 ]]; then

#Install Th3inspector

git clone https://github.com/Moham3dRiahi/Th3inspector.git
echo -e "${y} SUDAH TERINSTALL.."


elif [[ $option == 047 ]]; then

#Install Findip

git clone https://github.com/kereh/Findip
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 048 ]]; then

#Install V3nom-Scanner

git clone https://github.com/v3n0m-Scanner
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 049 ]]; then

#Install Bom Sms 3

git clone https://github.com/ardzz/tri/
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 050 ]]; then

#Install WebKiller

git clone https://github.com/ultrasecurity/webkiller
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 051 ]]; then

#Install Bitcoin-Hacking-Tools

git clone https://github.com/SMH17/bitcoin-hacking-tools
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 052]]; then

#install Firefox-Plugin-Popup-Logout

git clone https://github.com/iniqua/firefox-plugin-popup-logout
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 053 ]]; then

#Install Bitcoin-All-Key-Generator

git clone https://github.com/saracen/bitcoin-all-key-generator
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 054 ]]; then

#Install My-First-Bitcoin-Miner

git clone https://github.com/philipperemy/my-first-bitcoin-miner
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 055 ]]; then

#Install Parity-Config-Generator

git clone https://github.com/paritytech/parity-config-generator
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 056 ]]; then

#Install Distributed-Bitcoin-Generator

git clone https://github.com/kudai/Distributed-Bitcoin-Generator
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 057 ]]; then

#Install Mesos-Bitcoin-Miner

git clone https://github.com/derekchiang/Mesos-Bitcoin-Miner
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 058 ]]; then

#Install Git_Psibot_Hacking

git clone https://github.com/psibot/git_psibot_hacking
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 059 ]]; then

#Install KatanaFramework

git clone https://github.com/PowerScript/KatanaFramework
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 060 ]]; then

#Install STP

git clone https://github.com/PowerScript/STP
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 061 ]]; then

#Install Termux-Ubuntu

git clone https://github.com/Neo-Oli/termux-ubuntu.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 062 ]]; then

#Install Nethuner-In-Termux

git clone https://github.com/Hax4us/Nethunter-In-Termux.git
echo -e "${y} SUDAH  TERINSTALL.."

elif [[ $option == 063 ]]; then

#Install viSQL

git clone https://github.com/blackvkng/viSQL.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 064 ]]; then

#Install Termux-Archlinux

git clone https://github.com/sdrausty/termux-archlinux.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 065 ]]; then

#Install Santet-Online

git clone https://github.com/Gameye98/santet-online
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 066 ]]; then

#Install GadoGado

git clone https://github.com/Senitopeng/GadoGado.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 067 ]]; then

#install CnkSpam

git clone https://github.com/hatakecnk/cnkspam
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 068 ]]; then

#Install AutoReportFB

git clone https://github.com/gshofficialgithubindonesia/autoreport-fb
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 069 ]]; then

#Install Google-Dork

git clone https://github.com/XG77Z10/Google-Dork
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 070 ]]; then

#Install FHX-Hash-Killer

git clone https://github.com/FajriHidayat088/FHX-Hash-Killer/
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 071 ]]; then

#Install Hash-Buster

git clone https://github.com/UltimateHackers/Hash-Buster
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 072 ]]; then

#Install Metasploit

pkg install curl
curl -LO
https://raw.githubusercontent.com/Hax4us/Metasploit_termux/master/metasploit.sh
echo -e "${y} chmod +x metasploit.sh"
echo -e "${y} sh metasploit.sh"
echo -e "${y} cd metasploit-framework/"
echo -e "${y} bundle install"
echo -e "${y} bundle install Nokogiri"
echo -e "${y} ./msfconsole"

elif [[ $option == 073 ]]; then

#Install Sritker

git clone https://github.com/UltimateHackers/Striker
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 074 ]]; then

#Install AutoScriptKiddieTool

git clone https://github.com/b3-v3r/ASKT-AutoScriptKiddiesTool-.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 075 ]]; then

#Install Weeman

git clone https://github.com/evait-security/weeman.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 076 ]]; then

#Install SCANNER-INURLBR

git clone https://github.com/googleinurl/SCANNER-INURLBR.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 077 ]]; then

#Install ScriptDefaceCreator

git clone https://github.com/Ubaii/script-deface-creator
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 078 ]]; then

#Install KtpKkGenerate

git clone https://github.com/zerosvn/ktpkkgenerate
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 079 ]]; then

#Install ReconDog

git clone https://github.com/UltimateHackers/ReconDog
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 080 ]]; then

#Install HakkuFramework

git clone https://github.com/4shadoww/hakkuframework
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 081 ]]; then

#Install HunnerFramework

git clone https://github.com/b3-v3r/Hunner
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 082 ]]; then

#Install Hammer

git clone https://github.com/cyweb/hammer
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 083 ]]; then

#Install Torshammer

git clone https://github.com/dotfighter/torshammer.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 084 ]]; then

#Install Katoolin

git clone https://github.com/LionSec/katoolin.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 085 ]]; then

#Install MPSYT

pkg install python
pip install mps_youtube
pip install youtube_dl
apt install mpv
mpsyt

elif [[ $option == 086 ]]; then

#Install A-Rat

git clone https://github.com/Xi4u7/A-Rat.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 087 ]]; then

#Install Cupp

git clone https://github.com/Mebus/cupp.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 088 ]]; then

#Install Webpwn3r

git clone https://github.com/zigoo0/webpwn3r
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 089 ]]; then

#Install IPGeolocation

git clone https://github.com/maldevel/IPGeolocation
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 090 ]]; then

#Install XL

git clone https://github.com/joss24242/xl-py 90
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 091 ]]; then

#Install BotFbBangDjon

git clone https://github.com/Senitopeng/BotFbBangDjon.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 092 ]]; then

#Install 4wsectools

git clone https://github.com/aryanrtm/4wsectools
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 09 ]]; then

#Install Admin_Penal

git clone https://github.com/Techzindia/admin_penal
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 094 ]]; then

#Install RouterSploit

https://github.com/reverse-shell/routersploit.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 095 ]]; then

#Install RusSpam

git clone https://github.com/Rusmana-ID/rus
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 096 ]]; then

#Install Jexboss

git clone https://github.com/joaomatosf/jexboss.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 097 ]]; then

#Install WifiPhisher

git clone https://github.com/wifiphisher/wifiphisher.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 098 ]]; then

#Install WebSploit

git clone https://github.com/The404Hacking/websploit.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 099 ]]; then

#Install Wifi-Hacker

git clone https://github.com/esc0rtd3w/wifi-hacker
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 100 ]]; then

#Install Mr.Rv1

git clone https://github.com/Mr-R225/Mr.Rv1
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 101 ]]; then

#Install Mr.Rv2

git clone https://github.com/Mr-R225/Mr.Rv2
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 102 ]]; then

#Install Stegosploit

git clone https://github.com/csh/stegosploit
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 103 ]]; then

#Install Blazy

git clone https://github.com/s0md3v/Blazy.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 104 ]]; then

#Install Anonymous

git clone https://github.com/SitiMaimunah/anonymous.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 105 ]]; then

#Install Bingoo

git clone https://github.com/Hood3dRob1n/BinGoo.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 106 ]]; then

#Install Tool-X

apt update

pkg install git

git clone https://github.com/Rajkumrdusad/Tool-X.git

cd Tool-X

chmod +x install.aex

sh install.aex

Y

Y

Tool-X

elif [[ $option == 107 ]]; then

#Install kickthemout

git clone https://github.com/k4m4/kickthemout
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 108 ]]; then

#Install T.DYF[300Tools]

git clone https://github.com/droidxerror123/T.DYF
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 109 ]]; then

#Install HPAS1369

git clone https://github.com/DedSecCyber/HPAS1369
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 110 ]]; then

#Install PemulungBTC

git clone https://github.com/Cvar1984/pemulungBTC
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 111 ]]; then

#Install TouchUrl

git clone https://github.com/SkyKnight-Team/TouchUrl
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 112 ]]; then

#Install IP-TRACK

git clone https://github.com/SkyKnighTeam/IP-TRACK
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 113 ]]; then

#Install Kuyang-Tool

git clone https://github.com/kereh/Kuyang-Tool
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 114 ]]; then

#Install SpazSMS

git clone https://github.com/Gameye98/SpazSMS
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 115 ]]; then

#Install SiteBroker

git clone https://github.com/Anon-Exploiter/SiteBroker
echo -e "${y} SUDAH TERINSTALL.. "

elif [[ $option == 116 ]]; then

#Install Email-Bomber

git clone https://github.com/zanyarjamal/Email-bomber
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 117 ]]; then

#Install Ip-Gathering

git clone https://github.com/kereh/Ip-gathering
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 118 ]]; then

#Install Scorpion

git clone https://github.com/DedSecCyber/scorpion
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 119 ]]; then

#Install New-Spammer

git clone https://github.com/haijuga7/New-Spammer
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 120 ]]; then

#Install Spam

git clone https://github.com/SIIL3NT/spam
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 121 ]]; then

#Install QJDID

git clone https://github.com/QiubyZ/QJDID
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 122 ]]; then

#Install QFloodSms

git clone https://github.com/QiubyZ/QFloodSms
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 123 ]]; then

#Install Login-Termux

git clone https://github.com/Harisgitama/login-termux
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 124 ]]; then

#Install Linux

git clone https://github.com/torvalds/linux
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 125 ]]; then

#Install Komodo

git clone https://github.com/Gameye98/Komodo
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 126 ]]; then

#Install HN-Installer

git clone https://github.com/kereh/HN-Installer
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 127 ]]; then

#Install Deface-Create

git clone https://github.com/kereh/Deface-create
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 128 ]]; then

#Install Good_Terminal

git clone https://github.com/kereh/Good_Termina
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 129 ]]; then

#Install Saddam

git clone https://github.com/OffensivePython/Saddam
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 1302 ]]; then

#Install Sqlitebrowser

git clone https://github.com/sqlitebrowser/sqlitebrowser
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 131 ]]; then

#Install PoC-Exploit

git clone https://github.com/re4lity/PoC-Exploit
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 132 ]]; then

#Install VTools

git clone https://github.com/rootM3eX/VTools
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 133 ]]; then

#Install Termux-Loginv2fx

git clone https://github.com/Harisgitama/termux-loginv2fx
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 134 ]]; then

#Install Anti-DDOS

git clone https://github.com/ismailtasdelen/Anti-DDOS
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 135 ]]; then

#Install Nscan

git clone https://github.com/OffensivePython/Nscan
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 136 ]]; then

#Install Hostcheker

git clone https://github.com/pirmansx/hostcheker
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 137 ]]; then

#Install WebKit

git clone https://github.com/ciku370/WebKit
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 138 ]]; then

#Install AOCDEFACE

git clone https://github.com/Amriez/AOCDEFACE
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 139 ]]; then

#Install Face-Hack

git clone https://github.com/soracyberteam/face-hack
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 172 ]]; then

#Install Bash-Ransomeware

git clone https://github.com/soracyberteam/bash-ransomware
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 141 ]]; then

#Install Cli-Browser

git clone https://github.com/soracyberteam/cli-browser
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 142 ]]; then

#Install Spam-Mantan

git clone https://github.com/not404foundcyberteam/spam-mantan
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 143 ]]; then

#Install ngrok-stable-linux-arm

wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-arm.zip
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 144  ]]; then

#Install Hulk

git clone https://github.com/grafov/hulk
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 145 ]]; then

#Install Termux-Lazysqlmap

git clone https://github.com/verluchie/termux-lazysqlmap
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 146 ]]; then

#Install ShellNoob

git clone https://github.com/reyammer/shellnoob
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 147 ]]; then

#Install ATSCAN

git clone https://github.com/AlisamTechnology/ATSCAN
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 148 ]]; then

#Install Commix

git clone https://github.com/commixproject/commix
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 149 ]]; then

#Install Wpscan

git clone https://github.com/wpscanteam/wpscan
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 150 ]]; then

#Install Wpbf

git clone https://github.com/atarantini/wpbf
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 151 ]]; then

#Install GreenReaper

git clone https://github.com/Amriez/GreenReaper
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 152 ]]; then

#Install Devploit

git clone https://github.com/joker25000/Devploit
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 153 ]]; then

#Install Ipmux

git clone https://github.com/Amriez/ipmux
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 154 ]]; then

#Install Genscript

git clone https://github.com/x-xsystm/genscript
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 155 ]]; then

#Instal Airgeddon

git clone https://github.com/v1s1t0r1sh3r3/airgeddon
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 156 ]]; then

#Install AVARspam

git clone https://github.com/ALX-04/AVARspam
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 157 ]]; then

#Install ANRspam

git clone https://github.com/Amriez/ANRspam
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 158 ]]; then

#Install Termuz-Ohmyzsh

git clone https://github.com/cabbagec/termux-ohmyzsh
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 159 ]]; then

#Install CredSniper

git clone https://github.com/ustayready/CredSniper
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 160 ]]; then

#Install Fluxion

git clone https://github.com/thehackingsage/Fluxion
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 161 ]]; then

#Install Pixiewps

git clone https://github.com/wiire/pixiewps
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 162  ]]; then

#Install Wifite

git clone https://github.com/derv82/wifite
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 163 ]]; then

#Install Zones

git clone https://github.com/Cvar1984/zones
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 164 ]]; then

#Install Sqlokmed

git clone https://github.com/Anb3rSecID/sqlokmed
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 165 ]]; then

#Install Sir

git clone https://github.com/AeonDave/sir
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 166 ]]; then

#Install Easymap

git clone https://github.com/Cvar1984/Easymap
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 167 ]]; then

#Install Sqliv

git clone https://github.com/Hadesy2k/sqliv
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 168 ]]; then

#Install AndroidPINCrack

git clone https://github.com/PentesterES/AndroidPINCrack
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 169 ]]; then

#Install NetKiller

git clone https://github.com/sysadmimteam/NetKiller
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 170 ]]; then

#Install IPScan

git clone https://github.com/sysadminteam/IPscan
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 171 ]]; then

#Install XPL-SEARCH

git clone https://github.com/r00mars/XPL-SEARCH
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 172 ]]; then

#Install Bolang

git clone https://github.com/Amriez/Bolang
echo -e "${y} SUDAH TERINSTAL.."

elif [[ $option == 173 ]]; then

#Install Termux-Go

git clone https://github.com/rafalgolarz/termux-go
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 174 ]]; then

#Install Toolss

git clone https://github.com/AnonHackerr/toolss
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 175 ]]; then

#Install AngryFuzzer

git clone https://github.com/ihebski/angryFuzzer.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 176 ]]; then

#Install HackTronian

git clone https://github.com/thegackingsage/hacktronian
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 177 ]]; then

#Install EvilURL

git clone https://github.com/UndeadSec/EvilURL
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 178 ]]; then

#Install CredMap

git clone https://github.com/lightos/credmap
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 179 ]]; then

#Install Pybelt

git clone https://github.com/ekultek/pybelt
echo -e "${y} SUDAH TERINSTALL.."

;;
elif [[ $option == 180 ]]; then

#Install PyBozoCrack

git clone https://github.com/ikkebr/PyBozoCrack
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 181 ]]; then

#Install Hashzer

git clone https://github.com/Anb3rSecID/Hashzer
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 182 ]]; then

#Install Poet

git clone https://github.com/mossberg/poet
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 183 ]]; then

#Install MamangKey

git clone https://github.com/Amriez/MamangKey
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 184 ]]; then

#Install Termux-Sudo

git clone https://github.com/st42/termux-sudo
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 185 ]]; then

#Install Nikto

git clone https://github.com/sullo/nikto
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 186 ]]; then

#Install TuyulBtn

git clone https://github.com/Senitopeng/TuyulBtn
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 187 ]]; then

#Install Fsociety

git clone https://github.com/Manisso/fsociety
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 188 ]]; then

#Install 1337Hash

git clone https://github.com/Gameye98/1337Hash
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 189 ]]; then

#Install CyberScan

git clone https://github.com/medbenali/CybersScan
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 090 ]]; then

#Install XL

git clone https://github.com/joss24242/xl-py 90
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 091 ]]; then

#Install BotFbBangDjon

git clone https://github.com/Senitopeng/BotFbBangDjon.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 092 ]]; then

#Install 4wsectools

git clone https://github.com/aryanrtm/4wsectools
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 09 ]]; then

#Install Admin_Penal

git clone https://github.com/Techzindia/admin_penal
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 094 ]]; then

#Install RouterSploit

https://github.com/reverse-shell/routersploit.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 095 ]]; then

#Install RusSpam

git clone https://github.com/Rusmana-ID/rus
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 096 ]]; then

#Install Jexboss

git clone https://github.com/joaomatosf/jexboss.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 097 ]]; then

#Install WifiPhisher

git clone https://github.com/wifiphisher/wifiphisher.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 098 ]]; then

#Install WebSploit

git clone https://github.com/The404Hacking/websploit.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 099 ]]; then

#Install Wifi-Hacker

git clone https://github.com/esc0rtd3w/wifi-hacker
echo -e "${y} SUDAH TERINSTALL.."

;;

#Install Hue

git clone https://github.com/UltimateHackers/hue
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 201 ]]; then


#Install Server_Domains

git clone https://github.com/cyweb/server_domains
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 202 ]]; then

#Install Tool-Kit

git clone https://github.com/Rajkumrdusad/Tool-Kit
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 203 ]]; then

#Install Myenc

git clone https://github.com/pirmansx/myenc
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 204 ]]; then

#Install BlackTrack

git clone https://github.com/kereh/BlackTrack
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 205 ]]; then

#Install Dec-Enc-Hash

git clone https://github.com/haijuga7/Dec-Enc-Hash
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 206 ]]; then

#Install BlackMail

git clone https://github.com/kereh/BlackMail
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 207 ]]; then

#Install ClickNRoot

git clone https://github.com/evait-security/ClickNRoot
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 208 ]]; then

#Install Wifresti

git clone https://github.com/LionSec/wifresti
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 209 ]]; then

#Install Port-Lookup

git clone https://github.com/the-c0d3r/port-lookup
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 210 ]]; then

#Install IP-Locator

git clone https://github.com/zanyarjamal/IP-Locator
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 211 ]]; then

#Install Pynmap

git clone https://github.com/the-c0d3r/pynmap
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 212 ]]; then

#Install Zambie

git clone https://github.com/zanyarjamal/zambie
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 213 ]]; then

#Install DataSploit

git clone https://github.com/zanyarjamal/DataSploit
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 214 ]]; then

#Install Dracnmap

git clone https://github.com/Screetsec/Dracnmap
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 215 ]]; then

#Install BlackNmap

git clone https://github.com/Xi4u7/BlackNmap
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 216 ]]; then

#Install Vbscan

git clone https://github.com/rezasp/vbscan
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 217 ]]; then

#Install Gdog

git clone https://github.com/maldevel/gdog
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 218 ]]; then

#Install Bot-Exploiter

git clone https://github.com/verluchie/bot-exploiter
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 219 ]]; then

#Install Instabot.py

git clone https://github.com/verluchie/instabot.py
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 220 ]]; then

#Install WP-Hunter

git clone https://github.com/aryanrtm/WP-Hunter
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 221 ]]; then

#Install meTAInstall

git clone https://github.com/4L13199/meTAInstall
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 222 ]]; then

#Install Remote-Shell

git clone https://github.com/aryanrtm/Remote-Shell
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 223 ]]; then

#Install WPSeku

git clone https://github.com/m4ll0k/WPSeku
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 224 ]]; then

#Install BForce

git clone https://github.com/YukersCreew/BForce
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 225 ]]; then

#Install SMBrute

git clone https://github.com/m4ll0k/SMBrute
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 226 ]]; then

#Install Cok-Rat

git clone https://github.com/mrcakil/cok-Rat
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 227 ]]; then

#Install Killr

git clone https://github.com/whackhashoe/killr
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 228 ]]; then

#Install 0WASP-Nettacker

git clone https://github.com/zdresearch/0WASP-Nettacker
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 229 ]]; then

#Install Dirsearch

git clone https://github.com/maurosoria/dirsearch
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 230 ]]; then

#Install Ezsploit

git clone https://github.com/rand0m1ze/ezsploit
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 231 ]]; then

#Install Fucking-Rat

git clone https://github.com/kereh/Fucking-Rat
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 232 ]]; then

#Install Joomscan

git clone https://github.com/rezasp/joomscan
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 233 ]]; then

#Install Brute-Force-Gmail

git clone https://github.com/JamesAndresCM/Brute_force_gmail
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 234 ]]; then

#Install CMSMap

git clone https://github.com/Dionach/CMSmap
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 235 ]]; then

#Install TheFatRat

git clone https://github.com/Screetsec/TheFatRat
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 236 ]]; then

#Install Lhst

git clone https://github.com/ciku370/lhst
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 237 ]]; then

#Install Ko-Dork

git clone https://github.com/ciku370/ko-dork
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 238 ]]; then

#Install Breacher

git clone https://github.com/UltimateHackers/Breacher
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 239 ]]; then

#Install PhishingGame

git clone https://github.com/senitopeng/PhisingGame
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 240 ]]; then

#Install Hasher

git clone https://github.com/Ciku370/hasher
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 241 ]]; then

#Install Ipddos

git clone https://github.com/Ciku370/ipddos
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 242 ]]; then

#Install AuxScan2.0

git clone https://github.com/Gameye98/Auxscan2.0
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 243 ]]; then

#Install AstraNMap

git clone https://github.com/Gameye98/AstraNmap
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 244 ]]; then

#Install OWScan

git clone https://github.com/Gameye98/OWScan
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 245 ]]; then

#Install AutoReaction

git clone https://github.com/Autoreaction
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 246 ]]; then

#Install MultiSpam

git clone https://github.com/kereh/MultiSpam
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 247 ]]; then

#Install WAScan

git clone https://github.com/m4II0k/WAScan
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 248 ]]; then

#Install 3ERZV3nL

wget -0 tuyul.php https://pastebin.com/raw/3ERZV3nL
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 249 ]]; then

#Install Errorcybertool

git clone https://github.com/MrKeepSmile/errorcybertool
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 250 ]]; then

#Install Termux-Lazysqlmap

git clone https://github.com/verluchie/termux-lazysqlmap

elif [[ $option == 251 ]]; then

#Install Termux-A

git clone https://github.com/Cvar1984/Termux-A.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 252 ]]; then

#Install Admin_Panel_Finder
git clone https://github.com/coding-shadow/admin_panel_finder
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 253 ]]; then

#Install Facebook-Cracker

git clone https://github.com/coding-shadow/facebook_cracker
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 254 ]]; then

#Install Jwt-Cracker

git clone https://github.com/Imammino/jwt-cracker
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 255 ]]; then

#Install Md-Password-Cracker

git clone https://github.com/md5-password-cracker.js
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 256 ]]; then

#Install Flux

git clone https://github.com/samyoyo/flux
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 257 ]]; then

#Install WatWeb

git clone https://github.com/urbanadventurer/WatWeb
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 258 ]]; then

#Install Tweetbox-Max

git clone https://github.com/mtmxlog/tweetbot-max
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 259 ]]; then

#Install SpamChat

git clone https://github.com/Senitopeng/Spamchat
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 260  ]]; then

#Install VulnScanner

git clone git clone https://github.com/kereh/VulnScaner
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 261  ]]; then

#Install IGP

git clone https://github.com/kereh/IGP
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 262  ]]; then

#Install Termux-Os

git clone https://github.com/Bhai4You/Termux-Os
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 263  ]]; then

#Install PemulungBTC

git clone https://github.com/Cvar1984/pemulungBTC.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 264  ]]; then

#Install xNot-Found

git clone https://github.com/hatakecnk/xNot_Found
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 265  ]]; then

#Install T.DEF-09

git clone https://github.com/droidxerror123/T.DEF-09
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 266  ]]; then

#Install BotTroxSelf

git clone https://github.com/Satria3/BotTroxSelf
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 267  ]]; then

#Install Stagefright

git clone https://github.com/m4rm0k/Stagefright
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 268  ]]; then

#Install Spaghetti

git clone https://github.com/m4ll0k/Spaghetti.git
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 269  ]]; then

#Install Pencari-Login-Admin

git clone https://github.com/DaffaTakarai/Pencari-Login-Admin
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 270 ]]; then

#Install Tools-GalaulersV.3

git clone https://github.com/DaffaTakarai/Tools-GalaulersV.3
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 271 ]]; then

#Install LITETOOLS

git clone https://github.com/4L13199/LITETOOLS
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 272 ]]; then

#Install Tools

git clone https://github.com/nullsecuritynet/tools
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 273 ]]; then

#Install Hack-Tools

git clone https://github.com/hacktoolspack/hack-tools
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 274 ]]; then

#Install Awesome-Docker

git clone https://github.com/veggiemonk/awesome-docker
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 275 ]]; then

#Install Imgui

git clone https://github.com/ocornut/imgui
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 276 ]]; then

#Install RxTool

git clone https://github.com/vondear/RxTool
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 277 ]]; then

#Install Windows-Hacks

git clone https://github.com/LazoCoder/Windows-Hacks
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 278 ]]; then

#Install Elixir-Tips

git clone https://github.com/blackode/elixir-tips
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 279 ]]; then

#Install Chrome-Password-Hacking

git clone https://github.com/darkarp/chrome-password-hacking
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 280 ]]; then

#Install Bioinformatics-Hacks

git clone https://github.com/audy/bioinformatics-hacks
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 281 ]]; then

#Install RaspberryPi-Packet-Sniffer

git clone https://github.com/adityashrm21/RaspberryPi-Packet-Sniffer
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 282 ]]; then

#Install Code-Breaker

git clone https://github.com/Defacto2/Code-Breaker
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 283 ]]; then

#Install AndSploit

git clone https://github.com/sundaysec/Andspoilt
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 284 ]]; then

#Install Multilang-Fork-Bombs

git clone https://github.com/EchoNine/Multilang-fork-bombs
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 285 ]]; then

#Install Typeracer-Hack

git clone https://github.com/aashutoshrathi/Typeracer-Hack
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 286 ]]; then

#Install CoD4_Hacks

git clone https://github.com/attilathedud/CoD4_Hacks
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 287 ]]; then

#Install TTR-Tools

git clone https://github.com/AskAlice/TTR-Tools
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 288 ]]; then

#Install BW_Hacks

git clone https://github.com/attilathedud/BW_Hacks
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 289  ]]; then

#Install CoD_Hacks

git clone https://github.com/attilathedud/CoD_Hacks
echo -e "${y} SUDAH TERINSTALL.."

elif [[ $option == 999 ]]; then

#install DarkFb

git clone https://github.com/arielpersija69/DarkfbV5
cd DarkfbV5
python2 hg.py

elif [[ $option == 290 ]]; then

#Install CIA-Hacking-Tools

git clone https://github.com/troydo42/CIA-Hacking-Tools
echo -e "${y} SUDAH TERINSTALL.."


#Exit
printf "\e[1;93m [!] Come in!\e[0m\n"
sleep 1
printf "\e[1;92m[\e[0m\e[1;77m1\e[0m\e[1;92m]\e[0m\e[1;93m List 1\e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m2\e[0m\e[1;92m]\e[0m\e[1;93m List 2\e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m3\e[0m\e[1;92m]\e[0m\e[1;93m Install \e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m9\e[0m\e[1;92m]\e[0m\e[1;93m List finish \e[0m\n"
read -p $'\n\e[1;92m[\e[0m\e[1;77m*\e[0m\e[1;92m] Choose an option: \e[0m' option

if [[ $option == 1 || $option == 01 ]]; then
pack1
elif [[ $option == 2 || $option == 02 ]]; then
pack2
elif [[ $option == 3 || $option == 03 ]]; then
instool
elif [[ $option == 9 ]]; then
exit 1
else
printf "\e[1;93m [!] Invalid option!\e[0m\n"
sleep 1
clear
menu
fi
}

menu



