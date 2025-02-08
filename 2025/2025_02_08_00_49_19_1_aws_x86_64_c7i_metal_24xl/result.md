### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250203|
| GCC           |11.4.1|
| Time          |2025-02-08 00:49:19 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43908|0.44772|0.00134|0.44030|0.00%|0.43995|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/459fc9de78)|0.43770|0.43909|0.00034|0.43823|-0.47%|0.43820|-0.40%|41.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/d3e5dbe45b)|0.43791|0.44045|0.00050|0.43886|-0.33%|0.43877|-0.27%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d3e5dbe45b)|0.42651|0.42840|0.00040|0.42733|-2.95%|0.42732|-2.87%|50.80 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71250|0.71544|0.00069|0.71382|0.00%|0.71386|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/459fc9de78)|0.70754|0.71162|0.00072|0.70907|-0.66%|0.70899|-0.68%|37.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/d3e5dbe45b)|0.71005|0.71204|0.00050|0.71100|-0.40%|0.71090|-0.41%|37.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d3e5dbe45b)|0.68389|0.68794|0.00085|0.68538|-3.98%|0.68530|-4.00%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58029|0.58352|0.00063|0.58179|0.00%|0.58172|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/459fc9de78)|0.57770|0.58019|0.00057|0.57888|-0.50%|0.57884|-0.50%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/d3e5dbe45b)|0.57859|0.58114|0.00057|0.57970|-0.36%|0.57969|-0.35%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d3e5dbe45b)|0.51982|0.52240|0.00057|0.52106|-10.44%|0.52103|-10.43%|61.93 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21441|0.21765|0.00070|0.21564|0.00%|0.21560|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/459fc9de78)|0.21559|0.21877|0.00080|0.21705|0.66%|0.21692|0.62%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/d3e5dbe45b)|0.21152|0.21493|0.00078|0.21277|-1.33%|0.21268|-1.35%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d3e5dbe45b)|0.07398|0.07711|0.00084|0.07557|-64.95%|0.07561|-64.93%|27.35 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33553|1.36110|0.00530|1.34729|0.00%|1.34708|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/459fc9de78)|1.36605|1.38613|0.00430|1.37708|2.21%|1.37745|2.25%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/d3e5dbe45b)|1.25481|1.27532|0.00415|1.26426|-6.16%|1.26454|-6.13%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d3e5dbe45b)|0.53269|0.55187|0.00398|0.54107|-59.84%|0.54085|-59.85%|21.77 MB|
