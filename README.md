# HomeLab Docker Compose for InfluxDB

## Preparation
To prepare the deployment, make a copy of the ```.env.example```  file to ```.env``` and override the default values to your need.
Also, to deploy into a different directory than the following, modify ```playbook.yml```.

## Deployment
To deploy this configuration in `/usr/local/etc/influxdb` and store the data in `/opt/influxdb` run the following ansible playbook:
```
sudo ansible-playbook playbook.yml
```
