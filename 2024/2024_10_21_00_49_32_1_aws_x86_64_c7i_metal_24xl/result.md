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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-10-21 00:49:32 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43803|0.45199|0.00185|0.43937|0.00%|0.43906|0.00%|41.89 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d19fdaa4b7)|0.43666|0.43814|0.00037|0.43740|-0.45%|0.43738|-0.38%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/514c2b3587)|0.43657|0.43848|0.00040|0.43743|-0.44%|0.43745|-0.37%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/514c2b3587)|0.42632|0.42790|0.00036|0.42692|-2.83%|0.42694|-2.76%|50.84 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71850|0.72223|0.00074|0.71982|0.00%|0.71980|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d19fdaa4b7)|0.71509|0.71906|0.00074|0.71658|-0.45%|0.71650|-0.46%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/514c2b3587)|0.71459|0.73225|0.00242|0.71616|-0.51%|0.71570|-0.57%|37.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/514c2b3587)|0.68976|0.69212|0.00060|0.69087|-4.02%|0.69075|-4.04%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58182|0.58887|0.00183|0.58676|0.00%|0.58740|0.00%|43.03 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d19fdaa4b7)|0.58262|0.58671|0.00092|0.58469|-0.35%|0.58468|-0.46%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/514c2b3587)|0.58391|0.58731|0.00060|0.58487|-0.32%|0.58481|-0.44%|42.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/514c2b3587)|0.52860|0.53035|0.00041|0.52959|-9.74%|0.52962|-9.84%|61.96 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21455|0.21840|0.00079|0.21630|0.00%|0.21622|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d19fdaa4b7)|0.21808|0.22171|0.00074|0.21954|1.50%|0.21959|1.56%|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/514c2b3587)|0.21600|0.21992|0.00092|0.21778|0.68%|0.21765|0.66%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/514c2b3587)|0.07471|0.07769|0.00068|0.07559|-65.06%|0.07545|-65.11%|27.32 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34141|1.36344|0.00448|1.35250|0.00%|1.35176|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d19fdaa4b7)|1.26639|1.29059|0.00540|1.27961|-5.39%|1.27918|-5.37%|20.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/514c2b3587)|1.27269|1.29521|0.00445|1.28266|-5.16%|1.28234|-5.14%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/514c2b3587)|0.51553|0.53159|0.00333|0.52318|-61.32%|0.52378|-61.25%|21.73 MB|
