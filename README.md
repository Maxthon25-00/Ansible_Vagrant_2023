Create Centos/7 VM with NGINX server.

1. First we create a VM - run Vagrantfile.

2. Second, we install nginx server on VM - run ansible-playbook nginx.yml.

3. Third, we load a web page in the browser - http://192.168.56.22:8080

4. If the web page displays "Welcome to Centos", then the nginx server is running.
