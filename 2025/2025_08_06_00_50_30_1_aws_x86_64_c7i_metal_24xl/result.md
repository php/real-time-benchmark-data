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
| Kernel        |6.1.147-172.259.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250804|
| GCC           |11.5.0|
| Time          |2025-08-06 00:50:30 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47125|0.48525|0.00240|0.47262|0.00%|0.47209|0.00%|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8e014dfbe)|0.46624|0.46836|0.00053|0.46718|-1.15%|0.46719|-1.04%|43.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/1820dd9b61)|0.46739|0.47410|0.00111|0.46857|-0.86%|0.46836|-0.79%|43.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1820dd9b61)|0.45136|0.45317|0.00036|0.45191|-4.38%|0.45191|-4.27%|53.73 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74036|0.74634|0.00136|0.74219|0.00%|0.74197|0.00%|39.94 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8e014dfbe)|0.72927|0.74405|0.00256|0.73102|-1.51%|0.73062|-1.53%|40.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/1820dd9b61)|0.73273|0.73457|0.00052|0.73357|-1.16%|0.73359|-1.13%|40.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1820dd9b61)|0.69232|0.70772|0.00244|0.70173|-5.45%|0.70173|-5.42%|47.77 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58359|0.58682|0.00059|0.58446|0.00%|0.58444|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8e014dfbe)|0.57986|0.58328|0.00068|0.58081|-0.62%|0.58064|-0.65%|43.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/1820dd9b61)|0.58159|0.58377|0.00056|0.58270|-0.30%|0.58275|-0.29%|43.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1820dd9b61)|0.51831|0.52022|0.00054|0.51934|-11.14%|0.51927|-11.15%|61.36 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21411|0.21894|0.00119|0.21597|0.00%|0.21585|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8e014dfbe)|0.21300|0.21609|0.00080|0.21426|-0.80%|0.21408|-0.82%|26.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/1820dd9b61)|0.21329|0.21671|0.00099|0.21452|-0.67%|0.21411|-0.80%|26.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1820dd9b61)|0.07281|0.07599|0.00082|0.07417|-65.66%|0.07408|-65.68%|27.77 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42542|1.44687|0.00484|1.43171|0.00%|1.43096|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8e014dfbe)|1.34214|1.36174|0.00594|1.35250|-5.53%|1.35478|-5.32%|20.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/1820dd9b61)|1.33868|1.35858|0.00525|1.34965|-5.73%|1.35081|-5.60%|20.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1820dd9b61)|0.55991|0.58894|0.00818|0.57381|-59.92%|0.57254|-59.99%|22.21 MB|
