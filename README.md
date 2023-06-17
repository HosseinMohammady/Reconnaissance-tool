# Reconnaissance-tool
simple Reconnaissance tool for rconning the target website.
this code is developed in python. to use it first you need to
download mywordlist i uploaded and opent it in your IDE then download 
main.py and open it. you can enter your target domain for checking.

features:
1- find subdomains of the target domain by checking the wordlist and
request to the DNS of the domain and also finding title and status code of subdomains.

2- find subdomains and their IPs by using socket and scan for common ports
to check if they are open or not.

3- find emails and phone numbers that exist on each subdomain by making
emails and phone numbers pattern to check all texts on subdomains.

4- whois look up and find information about domain. such as : domain name -
domain creation date - domain registrant country.

5- extracting urls existing on webpage by requesting to the url of the site 
and parsing html content of the website using beautifulSoup.
