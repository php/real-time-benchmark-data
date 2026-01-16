### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-16 00:50:25 UTC|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46058|0.47090|0.00128|0.28%|0.46149|0.00%|0.46121|0.00%|5.215|0.999|27.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1d2875a82)|0.46063|0.46689|0.00070|0.15%|0.46153|0.01%|0.46139|0.04%|5.131|0.000|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/9b719cd4a3)|0.45664|0.46370|0.00097|0.21%|0.45734|-0.90%|0.45713|-0.88%|5.549|0.000|26.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9b719cd4a3)|0.43666|0.43904|0.00037|0.08%|0.43733|-5.24%|0.43728|-5.19%|1.585|0.000|26.92 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.77629|0.79244|0.00212|0.27%|0.78124|0.00%|0.78116|0.00%|2.165|0.999|27.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1d2875a82)|0.77254|0.78197|0.00196|0.25%|0.77834|-0.37%|0.77903|-0.27%|-0.679|0.000|26.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/9b719cd4a3)|0.77739|0.79210|0.00140|0.18%|0.78020|-0.13%|0.78013|-0.13%|6.168|0.000|26.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9b719cd4a3)|0.75117|0.98287|0.08652|10.53%|0.82187|5.20%|0.77045|-1.37%|0.675|0.001|26.94 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.65939|0.68069|0.00295|0.45%|0.66127|0.00%|0.66042|0.00%|4.386|0.999|27.53 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1d2875a82)|0.66320|0.68340|0.00198|0.30%|0.66425|0.45%|0.66398|0.54%|9.303|0.000|26.95 MB|
|[PHP - master](https://github.com/php/php-src/commit/9b719cd4a3)|0.66112|0.68148|0.00324|0.49%|0.66283|0.24%|0.66223|0.27%|5.382|0.000|26.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9b719cd4a3)|0.59262|0.59465|0.00041|0.07%|0.59342|-10.26%|0.59333|-10.16%|0.645|0.000|26.96 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42509|0.43092|0.00125|0.29%|0.42747|0.00%|0.42718|0.00%|0.464|0.999|7.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1d2875a82)|0.43192|0.43901|0.00135|0.31%|0.43498|1.76%|0.43498|1.82%|0.113|0.000|7.95 MB|
|[PHP - master](https://github.com/php/php-src/commit/9b719cd4a3)|0.43239|0.44159|0.00180|0.41%|0.43607|2.01%|0.43593|2.05%|0.467|0.000|7.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9b719cd4a3)|0.14092|0.14604|0.00096|0.67%|0.14346|-66.44%|0.14351|-66.41%|-0.189|0.000|7.95 MB|
