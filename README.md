# test-web-server-from-sgx

To Run the web server:

python -m SimpleHTTPServer 1337

To hit the web server:

ssh -N -L 8912:127.0.0.1:1337 -i ~/.ssh/id_rsa harsh@sgx2

+

http://localhost:8912/myfile.html
