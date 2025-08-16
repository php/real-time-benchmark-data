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
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250808|
| GCC           |11.5.0|
| Time          |2025-08-16 00:49:57 UTC|

### Laravel 12.2.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46429|0.47535|0.00138|0.29%|0.47155|0.00%|0.47141|0.00%|1.000|46.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f9d95c649e)|0.46517|0.46677|0.00037|0.08%|0.46595|-1.19%|0.46594|-1.16%|0.001|46.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ca21d2e07)|0.46584|0.46764|0.00041|0.09%|0.46648|-1.07%|0.46642|-1.06%|0.001|46.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ca21d2e07)|0.44909|0.45055|0.00034|0.08%|0.44961|-4.65%|0.44955|-4.64%|0.001|58.04 MB|

### Symfony 2.7.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74031|0.74510|0.00113|0.15%|0.74199|0.00%|0.74155|0.00%|1.000|28.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f9d95c649e)|0.73098|0.74330|0.00294|0.40%|0.73328|-1.17%|0.73237|-1.24%|0.001|27.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ca21d2e07)|0.72977|0.74362|0.00240|0.33%|0.73178|-1.38%|0.73111|-1.41%|0.001|27.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ca21d2e07)|0.69833|0.70394|0.00109|0.16%|0.70025|-5.63%|0.70005|-5.60%|0.001|29.25 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58217|0.58494|0.00060|0.10%|0.58330|0.00%|0.58333|0.00%|1.000|43.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f9d95c649e)|0.58099|0.58379|0.00063|0.11%|0.58221|-0.19%|0.58220|-0.19%|0.001|43.67 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ca21d2e07)|0.57917|0.58214|0.00065|0.11%|0.58040|-0.50%|0.58029|-0.52%|0.001|43.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ca21d2e07)|0.51256|0.51872|0.00084|0.16%|0.51683|-11.40%|0.51688|-11.39%|0.001|61.46 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21509|0.21928|0.00117|0.54%|0.21669|0.00%|0.21669|0.00%|1.000|25.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f9d95c649e)|0.22012|0.28594|0.02062|9.00%|0.22905|5.71%|0.22141|2.18%|0.031|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ca21d2e07)|0.21575|0.21880|0.00095|0.44%|0.21700|0.14%|0.21694|0.11%|0.465|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ca21d2e07)|0.08276|0.08428|0.00048|0.58%|0.08349|-61.47%|0.08342|-61.50%|0.001|26.53 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.36912|1.41214|0.00944|0.68%|1.38174|0.00%|1.38052|0.00%|1.000|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f9d95c649e)|1.24812|1.26378|0.00513|0.41%|1.25641|-9.07%|1.25806|-8.87%|0.001|20.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ca21d2e07)|1.30298|1.32205|0.00509|0.39%|1.31177|-5.06%|1.31188|-4.97%|0.001|20.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ca21d2e07)|0.55068|0.56271|0.00327|0.59%|0.55519|-59.82%|0.55517|-59.79%|0.001|22.29 MB|
