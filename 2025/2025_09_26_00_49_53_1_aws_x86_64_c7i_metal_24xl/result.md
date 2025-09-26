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
| OS            |Amazon Linux 2023.8.20250818|
| GCC           |14.2.1|
| Time          |2025-09-26 00:49:53 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47000|0.47884|0.00094|0.20%|0.47644|0.00%|0.47633|0.00%|-2.706|0.999|180951335|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5b8a5320df)|0.46695|0.47117|0.00056|0.12%|0.46783|-1.81%|0.46774|-1.80%|2.724|0.000|176333038|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b930654b)|0.46855|0.47145|0.00057|0.12%|0.46961|-1.43%|0.46955|-1.42%|0.899|0.000|176406900|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b930654b)|0.44319|0.45078|0.00077|0.17%|0.44862|-5.84%|0.44864|-5.81%|-3.057|0.000|147885598|53.44 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73494|0.75319|0.00219|0.30%|0.74173|0.00%|0.74134|0.00%|3.596|0.999|291626076|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5b8a5320df)|0.73478|0.74856|0.00203|0.28%|0.73652|-0.70%|0.73624|-0.69%|4.530|0.000|287357890|40.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b930654b)|0.73750|0.74796|0.00150|0.20%|0.73943|-0.31%|0.73914|-0.30%|2.380|0.000|287354496|40.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b930654b)|0.70968|0.71352|0.00068|0.10%|0.71107|-4.13%|0.71108|-4.08%|0.401|0.000|267690930|47.58 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57848|0.59342|0.00146|0.25%|0.58219|0.00%|0.58210|0.00%|4.731|0.999|1123336900|43.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5b8a5320df)|0.57786|0.58334|0.00092|0.16%|0.57952|-0.46%|0.57938|-0.47%|1.042|0.000|1120243676|44.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b930654b)|0.57876|0.58294|0.00078|0.13%|0.58012|-0.36%|0.58003|-0.36%|1.070|0.000|1120243528|44.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b930654b)|0.51526|0.51968|0.00072|0.14%|0.51770|-11.08%|0.51769|-11.07%|0.110|0.000|866317530|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42999|0.44196|0.00183|0.42%|0.43359|0.00%|0.43357|0.00%|0.872|0.999|2020638169|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5b8a5320df)|0.42755|0.54957|0.02329|5.33%|0.43733|0.86%|0.43139|-0.50%|3.796|0.000|2020595037|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b930654b)|0.42611|0.43949|0.00238|0.55%|0.42955|-0.93%|0.42895|-1.07%|1.806|0.000|2020595113|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b930654b)|0.14727|0.15347|0.00107|0.72%|0.14927|-65.57%|0.14904|-65.63%|1.535|0.000|536613198|27.73 MB|
