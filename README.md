# RECON
This program can find important information from the desired site.<br>
I used this tool to get https://google.com information.<br>
Next, I will explain how to use this program:<br>
For this program to work for you, first install these libraries:<br>
pip install whois<br>
pip install socket<br>
pip install python-nmap<br>
pip install requests<br>
pip install beautifulsoup4<br>
pip install selenium<br>
<br>
# Introduction of commands:<br>
1: --start-all : Performs all tasks related to recon<br>
2: --find-link : The process finds links<br>
3: --find-D2L : This process finds links of depth two<br>
4: --find-Subdomain : This process finds the links in the subdomains of the site<br>
5: --find-port : This process finds the open ports of the site<br>
6: --regex : This process performs regex operations<br>
7: --whois : This process performs the whois operation<br>
<br>
# Description of project files:<br>
1: links.html : Links found from the desired site are saved in this file.<br>
2: Depthtwo.html : The links found from the depth of two sites are stored in this file.<br>
3: SubdomainANDLinks.html : The subdomains of the desired site are stored in this file in addition to the links inside them.<br>
4: SubdomainANDLinks.txt : Subdomains are stored in this text file which is used for regex operations.<br>
5: Port.html : The open ports of the desired site are stored in this file.<br>
6: Regex.html : The phone numbers and emails found from the subdomains of the desired site are stored in this file.<br>
7: screenshot.png : In this file, the screenshot taken from the desired site is saved.<br>
# Note: The function of finding subdomain links of depth 2 has been commented because it is time-consuming.
<br>
(☞ﾟヮﾟ)☞ FATHI ☜(ﾟヮﾟ☜) 
