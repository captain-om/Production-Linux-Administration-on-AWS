# Production Linux Administration & Laravel Deployment on AWS

This project demonstrates a production-style Linux environment built on AWS. The objective was to instill  practical DevOps concepts including Linux administration, application deployment, troubleshooting, CI/CD, and monitoring on AWS.

The project focuses not only on deployment but also on production troubleshooting through intentional break-and-fix scenarios using Linux logs and systemd.

## Project  Features

- Linux Server Administration
- SSH User Management
- UFW Firewall Configuration
- Nginx Web Server Configuration
- PHP-FPM Configuration
- Laravel Application Deployment
- Amazon RDS MySQL Integration
- Supervisor Process Management
- Jenkins CI/CD Pipeline
- Amazon CloudWatch Monitoring
- Production Troubleshooting

Architecture

<img width="2700" height="1732" alt="17835256591495253959453053066117" src="https://github.com/user-attachments/assets/f3cad345-4b00-4b10-987d-04da627fc961" />


### Tools & Technologies

### Cloud

- AWS EC2
- Amazon RDS
- Amazon CloudWatch

### Operating System

- Ubuntu 24.04 LTS

### Web Server

- Nginx

### Application Stack

- PHP 8.1
- PHP-FPM
- Laravel
- Composer

### Process Management

- Supervisor
- systemd

### CI/CD

- Jenkins
- Git
- GitHub

### Monitoring

- Amazon CloudWatch

### Linux Administration

- UFW Firewall
- journalctl
- logrotate

## Repository Structure

```text
Production-Linux-Administration-on-AWS/
│
├── architecture/
│   └── architecture.jpg
│
├── configs/
│   ├── nginx/
│   └── supervisor/
│
├── docs/
│   ├── linux-commands.md
│   ├── troubleshooting.md
│   ├── jenkins.md
│   └── cloudwatch.md
│
├── screenshots/
│   ├── linux/
│   ├── nginx/
│   ├── laravel/
│   ├── rds/
│   ├── supervisor/
│   ├── jenkins/
│   └── cloudwatch/
│
├── Jenkinsfile
└── README.md
```

## Documentation

- [Linux Commands](docs/linux-commands.md)
- [Troubleshooting Guide](docs/troubleshooting.md)
- [Jenkins CI/CD](docs/jenkins.md)
- [CloudWatch Monitoring](docs/cloudwatch.md)

## Screenshots

Project screenshots are organized by component for easy navigation.

- `screenshots/linux/` — Linux administration and server configuration
- `screenshots/nginx/` — Nginx configuration and troubleshooting
- `screenshots/laravel/` — Laravel deployment and migration
- `screenshots/rds/` — Amazon RDS configuration and connectivity
- `screenshots/supervisor/` — Supervisor process management
- `screenshots/jenkins/` — Jenkins installation and CI pipeline
- `screenshots/cloudwatch/` — CloudWatch metrics and alarms

All screenshots are available in the `screenshots/` directory.

## Lessons Learned

Through this project I gained hands-on experience with:

- Linux server administration
- Production troubleshooting using logs
- Nginx configuration and debugging
- Laravel deployment on AWS
- Amazon RDS connectivity
- PHP-FPM configuration
- Supervisor process management
- Jenkins CI/CD pipelines
- Amazon CloudWatch monitoring


## Future Improvements

This project intentionally focuses on Linux administration, deployment, CI/CD, and monitoring.

Possible future enhancements include:

- Infrastructure as Code using Terraform
- Docker containerization
- Amazon ECS or Kubernetes deployment
- Automated testing in Jenkins
- Advanced monitoring with Prometheus and Grafana

## Conclusion

This project demonstrates the deployment, administration, monitoring, and troubleshooting of a Laravel application on AWS using production-style Linux administration practices. It focuses on practical DevOps skills such as automation, process management, CI/CD, and infrastructure monitoring.
