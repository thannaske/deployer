<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit contrib/crontab.php -->
<!-- Then run bin/docgen -->

# Crontab Recipe

```php
require 'contrib/crontab.php';
```

[Source](/contrib/crontab.php)


## Configuration
### bin/crontab
[Source](https://github.com/deployphp/deployer/blob/master/contrib/crontab.php#L28)

Get path to bin

```php title="Default value"
return which('crontab');
```


### crontab:identifier
[Source](https://github.com/deployphp/deployer/blob/master/contrib/crontab.php#L33)

Set the identifier used in the crontab, application name by default

```php title="Default value"
return get('application', 'application');
```



## Tasks

### crontab:sync
[Source](https://github.com/deployphp/deployer/blob/master/contrib/crontab.php#L38)

Sync crontab jobs.




