Supervisor (on production)
=========================

1. Install supervisor
```bash
    pip install supervisor
```

2. create a `supervisor.conf` file where the manage.py file is with the following content:

3. Run the following command:
```bash
supervisord -c supervisor.conf
```

4. Supervisor commands:
```bash
supervisorctl status 
supervisorctl stop all
supervisorctl start all
supervisorctl stop [program_name]
supervisorctl start [program_name]
```
