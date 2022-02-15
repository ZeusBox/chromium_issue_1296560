git clone https://github.com/ZeusBox/chromium_issue_1296560.git
cd chromium_issue_1296560
tar -xvf message.tar.gz
python3 -m http.server 8888
chrome --no-sandbox http://localhost:8888