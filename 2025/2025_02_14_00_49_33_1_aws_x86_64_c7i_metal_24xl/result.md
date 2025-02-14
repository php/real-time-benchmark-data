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
| OS            |Amazon Linux 2023.6.20250211|
| GCC           |11.4.1|
| Time          |2025-02-14 00:49:33 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43868|0.44171|0.00057|0.43996|0.00%|0.43992|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65d433161a)|0.43424|0.43844|0.00071|0.43562|-0.98%|0.43552|-1.00%|41.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/78d934ad8e)|0.43603|0.43858|0.00053|0.43695|-0.68%|0.43685|-0.70%|41.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/78d934ad8e)|0.42472|0.42660|0.00041|0.42558|-3.27%|0.42551|-3.28%|50.80 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71292|0.71639|0.00075|0.71435|0.00%|0.71423|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65d433161a)|0.71029|0.71356|0.00077|0.71158|-0.39%|0.71142|-0.39%|37.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/78d934ad8e)|0.70767|0.71151|0.00084|0.70898|-0.75%|0.70891|-0.74%|37.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/78d934ad8e)|0.68345|0.68743|0.00087|0.68533|-4.06%|0.68512|-4.08%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58127|0.59134|0.00138|0.58265|0.00%|0.58249|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65d433161a)|0.57565|0.58941|0.00165|0.58110|-0.27%|0.58096|-0.26%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/78d934ad8e)|0.57870|0.58093|0.00050|0.57977|-0.50%|0.57966|-0.49%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/78d934ad8e)|0.52188|0.52811|0.00088|0.52291|-10.25%|0.52275|-10.26%|61.93 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21480|0.21894|0.00098|0.21631|0.00%|0.21629|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65d433161a)|0.21743|0.22298|0.00127|0.21968|1.56%|0.21943|1.45%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/78d934ad8e)|0.21498|0.21942|0.00095|0.21628|-0.02%|0.21609|-0.09%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/78d934ad8e)|0.07348|0.07751|0.00083|0.07523|-65.22%|0.07514|-65.26%|27.32 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33625|1.36421|0.00666|1.34943|0.00%|1.34897|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65d433161a)|1.28357|1.30101|0.00391|1.28954|-4.44%|1.28881|-4.46%|20.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/78d934ad8e)|1.34614|1.35932|0.00351|1.35305|0.27%|1.35359|0.34%|20.49 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/78d934ad8e)|0.53182|0.56252|0.00661|0.54702|-59.46%|0.54693|-59.46%|21.75 MB|
