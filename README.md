# Production-Linux-Administration-on-AWS
A hands-on DevOps project demonstrating production-style Linux server administration, web server configuration, application deployment, and CI/CD automation on AWS.
Production Linux Administration & DevOps Project on AWS

A hands-on DevOps project demonstrating production-style Linux server administration, web server configuration, application deployment, and CI/CD automation on AWS.

What This Project Covers


Ubuntu 22.04 EC2 server setup and hardening
User management, SSH configuration, UFW firewall
Nginx web server — configuration and troubleshooting
PHP 8.1 and PHP-FPM setup
Laravel application deployment
Amazon RDS MySQL database connection
Supervisor process management for queue workers
Jenkins CI/CD pipeline
Log management and logrotate configuration
Intentional break-and-fix scenarios demonstrating troubleshooting skills
Architecture

EC2 (Ubuntu 22.04)
├── Nginx (reverse proxy + web server)
├── PHP-FPM (PHP processor)
├── Laravel (application)
├── Supervisor (process manager)
│   └── Queue Workers (x2)
├── Jenkins (CI/CD)
└── Amazon RDS MySQL (database)

Break and Fix Scenarios Documented


Nginx syntax error → diagnosed with nginx -t → fixed
Nginx stopped → diagnosed with systemctl status + journalctl → fixed
Wrong file permissions → diagnosed with error.log → fixed
Firewall blocking HTTP → diagnosed with ufw status → fixed
PHP-FPM stopped → diagnosed with 502 error log → fixed
RDS wrong credentials → diagnosed with laravel.log → fixed
Supervisor worker killed → auto-recovered by Supervisor → verified


Tools Used
Linux · Nginx · PHP-FPM · Composer · Laravel · MySQL · Amazon RDS · Supervisor · Jenkins · UFW · systemd · journalctl · logrotate

Linux · Nginx · PHP-FPM · Composer · Laravel · MySQL · Amazon RDS · Supervisor · Jenkins · UFW · systemd · journalctl · logrotate
