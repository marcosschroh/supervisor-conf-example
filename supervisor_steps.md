# Supervisor (on production)


- Install supervisor
```bash
    pip install supervisor
```

- Create a `supervisor.conf` file where the manage.py file is with the following content:
[supervisor_example.conf](https://github.com/marcosschroh/supervisor-conf-example/blob/master/supervisor_example.conf)

- Run the following command:
```bash
supervisord -c supervisor.conf
```

- A few Supervisor commands:
```bash
supervisorctl status 
supervisorctl stop all
supervisorctl start all
supervisorctl stop [program_name]
supervisorctl start [program_name]
```
