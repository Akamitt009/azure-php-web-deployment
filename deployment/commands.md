# Azure VM Deployment Steps

1. Create Ubuntu VM on Azure
2. SSH into VM
3. Install Nginx:
   sudo apt install nginx -y

4. Install PHP:
   sudo apt install php-fpm php-mysql -y

5. Configure Nginx for PHP (FastCGI)
6. Set permissions:
   sudo chown -R www-data:www-data /var/www/html

7. Restart services:
   sudo systemctl restart nginx
