# crt.sh-crawler
bash script to crawl and filter crt.sh service for subdomains 
# Description 
crt.sh website when take a domain gives back the subdomains depending on the certificate of this domains . so i make this tool to crawl the output and filter it and get the unique subdomain to txt file 
# Install 
just make the script executable 
chmod +x crt-crawler.sh
# Usage
this tool takes two arugements 
1. The domain name [ e.g snapchat.com ]
2. The output text file [ e.g crt.txt ]
Example:
./crt-crawler.sh snapchat.com crt.txt
