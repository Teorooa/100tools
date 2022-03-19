#!/bin/bash


clear
###################################################
###################################################
sleep 1
menu() {

printf "\e[1;92m[\e[0m\e[1;77m1\e[0m\e[1;92m]\e[0m\e[1;93m Paquetes\e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m2\e[0m\e[1;92m]\e[0m\e[1;93m Paquetes\e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m3\e[0m\e[1;92m]\e[0m\e[1;93m Opcion rapida\e[0m\n"
printf "\e[1;92m[\e[0m\e[1;77m9\e[0m\e[1;92m]\e[0m\e[1;93m \e[0m\n"
read -p $'\n\e[1;92m[\e[0m\e[1;77m*\e[0m\e[1;92m] Choose an option: \e[0m' option

if [[ $option == 1 || $option == 01 ]]; then
pack1
elif [[ $option == 2 || $option == 02 ]]; then
pack2=""
elif [[ $option == 2 || $option == 02 ]]; then
insttool
elif [[ $option == 9 ]]; then
exit 1
else
printf "\e[1;93m [!] Invalid option!\e[0m\n"
sleep 1
clear
banner
dependencies
menu
fi
}

pack1() {
printf ""
printf "\e[1;93m 999. install Dark F \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 1. Install Nmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 2. Install Admin-finder\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 3. Install RED_HAWK\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 4. Install Lazymux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 5. Install Tools-X\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 6. Install Mrcakil\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 7. Install D-TECT\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 8. Install Mr.Rv1.1\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 9. Install  AJINGANv6\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 10. Install Multi ruteForce(M F)\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 11. Install XERXES\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 12. Install LITESPAM\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 13. Install Android-Malware\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 14. Install SigPloit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 15. Install Sn1per\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 16. Install ICG-AutoExploiter oT\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 17. Install QRLJacking\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 18. Install txtool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 19. Install  ulltools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 20. Install Termux- anner\e[0m\n"
printf "\e[1;93m ============================" |  
printf "\e[1;93m 21. Install udfhack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 22. Install Mirai-Source-Code\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 23. Install Hale\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 24. Install Mirai-IoT- otNet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 25. Install Ufonet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 26. Install  om\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 27. Install tool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 28. Install  otNet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 29. Install Malwares\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 30. Install zeus- ot\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 31. Install AutoSploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 32. Install IFC\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 33. Install SQLMAP\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 34. Install Spyder\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 35. Install Social-Engineer-ToolKit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 36. Install Kawai- otnet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 37. Install DarkSploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 38. Install SH33LL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 39. Install Evil-Create-Framework\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 40. Install Ga utz\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 41. Install RootNet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 42. Install  adMod\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 43. Install  oomHash\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 44. Install Plutus\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 45. Install ContexPloit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 46. Install Th3inspector\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 47. Install Findip\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 48. Install V3nom-Scanner\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 49. Install  om Sms 3\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 50. Install We Killer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 51. Install  itcoin-Hacking-Tools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 52. Install Firefox-Plugin-Popup-Logout\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 53. Install  itcoin-All-Key-Generator\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 54. Install My-First- itcoin-Miner\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 55. Install Parity-Config-Generator\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 56. Install Distri uted- itcoin-Generator \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 57. Install Mesos- itcoin-Miner\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 58. Install Git_Psi ot_Hacking\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 59. Install KatanaFramework\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 60. Install STP\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 61. Install Termux-U untu\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 62. Install Nethuner-In-Termux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 63. Install viSQL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 64. Install Termux-Archlinux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 65. Install Santet-Online\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 66. Install GadoGado\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 67. Install CnkSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 68. Install AutoReportF \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 69. Install Google-Dork\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 70. Install FHX-Hash-Killer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 71. Install Hash- uster\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 72. Install Metasploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 73. Install Striker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 74. Install AutoScriptKiddieTool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 75. Install Weeman\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 76. Install SCANNER-INURL R\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 77. Install Script-Deface-Creator\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 78. Install ktpKkGenerate\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 79. Install ReconDog\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 80. Install HakkuFramework\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 81. Install HunnerFramework\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 82. Install Hammer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 83. Install Torshammer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 84. Install Katoolin\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 85. Install MPSYT\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 86. Install A-Rat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 87. Install Cupp\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 88. Install We pwn3r\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 89. Install IPGeolocation\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 90. Install XL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 91. Install  otF  angDjon\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 92. Install 4wsectools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 93. Install Admin_Penal\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 94. Install RouterSploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 95. Install RusSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 96. Install Jex oss\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 97. Install WifiPhisher\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 98. Install We Sploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 99. Install Wifi-Hacker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 100. Install Mr.Rv1\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 101. Install Mr.Rv.2\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 102. Install Stegosploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 103. Install  lazy\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 104. Install anonymous\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 105. Install  ingoo\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 106. Install Tool-X\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 107. Install kickthemout\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 108. Install T.DYf[300Tools]\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 109. Install HPAS-1369\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 110. Install pemulung TC\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 111. Install TouchUrl\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 112. Install IP-TRACK\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 113. Install Kuyang-Tool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 114. Install SpazSMS\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 115. Install Site roker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 116. Install Email- om er \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 117. Install Ip-Gathering\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 118. Install Scorpion\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 119. Install New-Spammer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 120. Install Spam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 121. Install QJDID\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 122. Install QFloodSms\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 123. Install Login-Termux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 124. Install Linux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 125. Install Komodo\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 126. Install HN-Installer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 127. Install Deface-Create\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 128. Install Good_Terminal\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 129. Install Saddam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 130. Install Sqlite rowser\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 131. Install PoC-Exploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 132. Install VTools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 133. Install Termux-Loginv2fx\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 134. Install Anti-DDOS\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 135. Install NScan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 136. Install Hostcheker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 137. Install We Kit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 138. Install AOCDEFACE\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 139. Install Face-Hack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 140. Install  ash-Ransomware\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 141. Install Cli- rowser\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 142. Install Spam-Mantan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 143. Install ngrok-sta le-linux-arm\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 144. Install Hulk\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 145. Install Termux-Lazsqlmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 146. Install Shellnoo \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 147. Install ATSCAN\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 148. Install Commix\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 149. Install Wpscan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 150. Install wp f\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
}

pack2() {
printf "\e[1;93m 151. Install GreenReaper\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 152. Install Devploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 153. Install Ipmux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 154. Install Genscript\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 155. Install Airgeddon\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 156. Install AVARSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 157. Install ANRSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 158. Install Termux-ohmyzsh\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 159. Install CredSniper\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 160. Install Fluxion\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 161. Install pixiewps\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 162. Install wifite\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 163. Install Zones\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 164. Install sqlokmed\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 165. Install Sir\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 166. Install Easymap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 167. Install Sqliv\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 168. Install AndroidPinCrack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 169. Install NetKiller\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 170. Install IPscan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 171. Install XPL-SEARCH\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 172. Install  olang\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 173. Install Termux-Go\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 174. Install Toolss\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 175. Install AngryFuzzer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 176. Install Hacktronian\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 177. Install EvilURL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 178. Install CredMap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 179. Install Py elt\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m 180. Install Py ozoCrack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 181. Install Hashzer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 182. Install Poet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 183. Install MamangKey\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 184. Install Termux-Sudo\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 185. Install Nikto\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 186. Install Tuyul tn\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 187. Install Fsociety\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 188. Install 1337Hash\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 189. Install Cy erScan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 190. Install  itcoin-Wallet\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 191. Install CamStream-V3\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 192. Install XEIT_CY ER\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 193. Install CsrfPocMaker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 194. Install PHP- ackConnector\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 195. Install Sta ilizer ot\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 196. Install Face ook-Video-Downloader\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 197. Install Rem ot\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 198. Install Entropy\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 199. Install Decodify\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 200. Install Hue\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 201. Install Server_Domains\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 202. Install Tool-Kit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 203. Install Myenc\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 204. Install  lackTrack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 205. Install Dec-Enc-Hash\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 206. Install  lackMail\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 207. Install ClickNRoot\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 208. Install Wifresti\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 209. Install Port-Lookup\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 210. Install IP-Locator\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 211. Install Pynmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 212. Install Zam ie\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 213. Install DataSploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 214. Install Dracnmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 215. Install  lackNmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 216. Isntall V scan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 217. Install Gdog\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 218. Install  ot-Exploiter\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 219. Install Insta ot.py\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 220. Install WP-Hunter\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 221. Install meTAInstall\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 222. Install Remote-Shell\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 223. Install WPSeku\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 224. Install  Force\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 225. Install SM rut\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 226. Install Cok-Rat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 227. Install Killr\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 228. Install 0WASP-Nettacker\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m 229. Install Dirsearch\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 230. Install Ezsploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 231. Install Fucking-Rat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 232. Install Joomscan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 233. Install  rute-Force-Gmail\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 234. Install CMSmap\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m 235. Install TheFatRat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 236. Install Lhst\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 237. Install Ko-Dork\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 238. Install  reacher\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 239. Install PhishingGame\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 240. Install Hasher\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 241. Install Ipddos\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 242. Install Auxsca2.0\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 243. Install AstraNmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 244. Install OWScan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 245. Install AutoReaction\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 246. Install MultiSpam\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 247. Install WAScan\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 248. Install 3ERZV3nL\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 249. Install ErrorCy erTool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 250. Install Termux-Lazysqlmap\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 251. Install Termux-A\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 252. Install Admin_Panel_Finder\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 253. Install Face ook_Cracker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 254. Install Jwt-Cracker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 255. Install Md5-Password-Cracker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 256. Install Flux\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 257. Install WatWe \e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 258. Install Tweet ot-Max\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m 259. Install SpamChat\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 260. Install VulnScaner\e[0m\n"
printf "\e[1;93m ============================ \e[0m\n"
printf "\e[1;93m 261. Install IGP\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 262. Install Termux-Os\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 263. Install Pemulung TC\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 264. Install xNot_Found\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 265. Install T.DEF-09\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 266. Install  otTroxSelf\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 267. Install Stagefright\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 268. Install Spaghetti\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 269. Install Pencari-admin-Login\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 270. Install Tool-GalaulersV.3\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 271. Install LITETOOLS\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 272. Install Tools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 273. Install Hack-Tool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 274. Install Awesome-Docker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 275. Install imgui\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 276. Install RxTool\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 277. Install Windows-Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 278. Install Elixir-Tips\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 279. Install Chrome-Password-Hacking\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 280. Install  ioInformatics-Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 281. Install Rasp erryPi-Packet-Sniffer\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 282. Install Code- reaker\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 283. Install Andsploit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 284. Install Multilang-Fork- om s\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 285. Install Typeracer-Hack\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 286. Install CoD4_Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 287. Install TTR-Tools\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 288. Install  W_Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 289. Install CoD_Hacks\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
printf "\e[1;93m 290. Install CIA-Hacking-Tools\e[0m\n"
printf "\e[1;93 ============================\e[0m\n"
printf "\e[1;93m 00. Exit\e[0m\n"
printf "\e[1;93m ============================\e[0m\n"
}
https://github.com/TUANB4DUT/TOOLSINSTALLERv3it clone https://github.com/LionSec/wifresti


menu
