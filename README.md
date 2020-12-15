# test-web-server-from-sgx

To Run the web server:

python 2.7
python -m SimpleHTTPServer 1337

if you're using Python 3.x or higher,
python -m http.server 1337

To hit the web server:

ssh -N -L 8912:127.0.0.1:1337 -i ~/.ssh/id_rsa harsh@sgx2

+

http://localhost:8912/myfile.html
