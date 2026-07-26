curl -I https://google.com

curl https://google.com

curl -L http://google.com

curl -o /dev/null -s -w "%{http_code}\n" https://google.com
