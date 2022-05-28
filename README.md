# Docker LEMP

Docker box for running kwcms project - web side

## Prerequisites

### Required

It is assumed you have Docker installed.

---

## What's Included

* Ubuntu Server v20.04 LTS (Focal Fossa) 64bit
* Nginx
* PHP 7.4
* PHP 8.1
* MariaDB
* PostgreSQL
* Redis
* Adminer

---

## Installation

The first time you clone the repo. Then link your workdirs into application dir.
Then bring the box up. That may take several minutes. If it doesn't explicitly fail/quit, then it is still working.

```bash
git clone https://github.com/alex-kalanis/docker-lemp.git
```

Once the Docker finishes and is ready, you can verify PHP is working at
[http://localhost:20000/](http://localhost:20000/) for 7.4,
[http://localhost:20001/](http://localhost:20001/) for 8.1 and
[http://localhost:20009/](http://localhost:20009/) for Adminer.

MySQL
* root pass: 951357456852
* user: kwcms
* pass: kwcms654

Postgres
* user: kwcms
* pass: kwcms654

