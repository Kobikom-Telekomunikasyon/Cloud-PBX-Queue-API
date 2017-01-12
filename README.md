# Cloud-PBX-API
 
### Queue and Agents GET/PUT/DELETE method and data type

> URL = http://{yourip}/api/module/{responseType}/{addQueue}/

```php
//PUT request - addQueue

responseType  => GET : xml/json
api_key       => GET
module        => GET
queueAdd      => GET
account       => POST => numeric
name          => POST => string
password      => POST => string
dynmembers    => POST => array
```


> URL = http://{yourip}/api/module/{responseType}/{request}/{deleteQueue}/

```php
//DELETE request - deleteQueue

responseType  => GET : xml/json
api_key       => GET
module        => GET
queueDelete   => GET
queueAccount  => GET => numeric
```

### Queue agents GET 

> URL = http://{yourip}/api/module/{response_type}/{queueAgents}/

```php
//GET request - queueAgents

responseType  => GET : xml/json
api_key       => GET
module        => GET
queueAccount  => GET
```

Best Regards...
