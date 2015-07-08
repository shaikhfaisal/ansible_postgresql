#### 
```
OS                 : Ubuntu 14.04 Trusty Tahr
PostgreSQL version : 9.4
```

#### Supported variables
```
postgresql_version
postgresql_packages
postgresql_port
postgresql_max_connections
postgresql_ssl
postgresql_shared_buffers
postgresql_data_directory
postgresql_timezone
postgresql_locale
```


#### Development and testing
The _devel folder contains everything you need to test the role on a ubuntu/trusty64 vagrant box

To test the role after making changes to it execute the following steps:

```
cd _devel
make clean
make test
```

#### Author
Faisal Shaikh
