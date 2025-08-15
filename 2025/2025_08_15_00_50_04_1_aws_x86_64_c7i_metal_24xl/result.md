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
| Time          |2025-08-15 00:50:04 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47047|0.47681|0.00110|0.23%|0.47155|0.00%|0.47135|0.00%|0.000|46.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359f4420a4)|0.46636|0.46833|0.00044|0.09%|0.46707|-0.95%|0.46702|-0.92%|0.000|46.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/f9d95c649e)|0.46512|0.46667|0.00037|0.08%|0.46570|-1.24%|0.46565|-1.21%|0.000|46.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f9d95c649e)|0.44518|0.45056|0.00089|0.20%|0.44956|-4.66%|0.44968|-4.60%|0.000|58.04 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74013|0.74511|0.00118|0.16%|0.74192|0.00%|0.74161|0.00%|0.000|28.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359f4420a4)|0.72843|0.73375|0.00101|0.14%|0.72965|-1.65%|0.72957|-1.62%|0.000|27.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/f9d95c649e)|0.72968|0.74081|0.00209|0.29%|0.73087|-1.49%|0.73028|-1.53%|0.000|27.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f9d95c649e)|0.70176|0.70911|0.00167|0.24%|0.70347|-5.18%|0.70300|-5.21%|0.000|29.25 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58268|0.58599|0.00068|0.12%|0.58386|0.00%|0.58378|0.00%|0.000|43.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359f4420a4)|0.57919|0.59023|0.00191|0.33%|0.58055|-0.57%|0.58008|-0.63%|0.000|43.60 MB|
|[PHP - master](https://github.com/php/php-src/commit/f9d95c649e)|0.58113|0.58397|0.00064|0.11%|0.58209|-0.30%|0.58204|-0.30%|0.000|43.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f9d95c649e)|0.51974|0.52187|0.00061|0.12%|0.52060|-10.83%|0.52054|-10.83%|0.000|61.46 MB|

### bench.php - 20 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21545|0.22018|0.00118|0.54%|0.21693|0.00%|0.21661|0.00%|0.000|25.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359f4420a4)|0.21915|0.27913|0.02268|9.83%|0.23081|6.40%|0.22001|1.57%|0.000|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/f9d95c649e)|0.22003|0.22270|0.00079|0.36%|0.22119|1.97%|0.22107|2.06%|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f9d95c649e)|0.08287|0.08546|0.00076|0.90%|0.08371|-61.41%|0.08329|-61.55%|0.000|26.47 MB|

### micro_bench.php - 20 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.36799|1.39219|0.00617|0.45%|1.38081|0.00%|1.38137|0.00%|0.000|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359f4420a4)|1.29062|1.30373|0.00363|0.28%|1.29809|-5.99%|1.29905|-5.96%|0.000|20.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/f9d95c649e)|1.24943|1.28151|0.00774|0.62%|1.25647|-9.01%|1.25436|-9.19%|0.000|20.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f9d95c649e)|0.54751|0.72031|0.04329|7.67%|0.56447|-59.12%|0.55405|-59.89%|0.000|22.23 MB|
