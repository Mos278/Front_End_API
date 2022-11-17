Step1 : docker pull nginx
Step2 : docker build -t nginx_api ./sol
Step3 : docker run --name test -p 80:80 -d nginx_api 