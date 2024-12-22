# cbot


**דרישות מערכת מינימליות**<br/>
<pre>
Ubuntu 24.04/Linux - (QA Done on this system.)
2 Treads(CPU)
750MB of RAM
10GB - Depend on Logs files
1 IPv4
</pre>
**שלבי ההתקנה**<br/>
תחילה עליכם להתחבר לשרת ה-Ubuntu שלכם באמצעות פרוטוקול SSH. (בווינדוס ניתן להעזר בתוכנה [PuTTY](https://putty.org))

<pre>
sudo -i
sudo apt-get install unzip
sudo apt-get install wget -y
wget https://github.com/ronisrael666/cbot/releases/download/ver-1.0/cbot.zip
unzip cbot.zip
cd cbot
bash install.sh
</pre>
במידה ומותקן אצלך שרת OpenVPN לצורכי אבטחת המערכת,
יש להחליף של השורה:
<pre>
bash install.sh
</pre>
בשורה,
<pre>
bash install.sh 1.1.1.1
</pre>
ובמקום 1.1.1.1 להשתמש בכתובת ה-IPv4 של שרת ה-OpenVPN.<br/>

**כיצד ניגשים לממשק הניהול של הבוט לאחר ההתקנה?**<br/>
במידה וכתובת ה-IPv4 של השרת שלכם היא 1.1.1.1, תוכלו לגשת לממשק הניהול של הבוט באמצעות הדפדפן בכתובת http://1.1.1.1:8089/<br/><br/>
**חשוב לזכור**
במידה ואתם משתמשים ב-VPN, עליכם להדליק אותו במכשירכם! - את האפליקציה לנייד או למחשב ניתן להשיג באתר של [OpenVPN](https://openvpn.net/client/client-connect-vpn-for-windows/) או בחנות האפליקציות בנייד.
