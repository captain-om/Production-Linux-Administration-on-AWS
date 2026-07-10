# Production Troubleshooting

## Incident 1 - Nginx Configuration Error

Problem

Nginx failed to start after editing nginx.conf.

Investigation

- systemctl status nginx
- journalctl -xe
- nginx -t

Root Cause

Missing semicolon.

Resolution

Corrected configuration and restarted Nginx.

---

## Incident 2 - Laravel Database Connection

Problem

Laravel failed to connect to Amazon RDS.

Investigation

- storage/logs/laravel.log

Root Cause

Incorrect database credentials.

Resolution

Updated .env and cleared configuration cache.

---

## Incident 3 - Supervisor Recovery

Problem

Queue worker terminated manually.

Investigation

- supervisorctl status
- ps aux
- supervisord.log

Resolution

Supervisor automatically restarted the worker.
