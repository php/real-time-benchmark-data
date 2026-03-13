### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.12.66-88.122.amzn2023.x86_64|
| OS            |Amazon Linux 2023.10.20260202|
| GCC           |14.2.1|
| Time          |2026-03-13 00:53:54 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23031116712 ([Artifacts](https://github.com/php/php-src/actions/runs/23031116712/artifacts/5903220928))|
| Changeset  |https://github.com/php/php-src/compare/113893b714..5ccaccda97|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39662|0.39852|0.00027|0.07%|0.39703|0.00%|0.39699|0.00%|3.557|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/113893b714)|0.39042|0.39259|0.00040|0.10%|0.39113|-1.49%|0.39101|-1.51%|1.722|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/5ccaccda97)|0.39065|0.39222|0.00029|0.07%|0.39129|-1.45%|0.39122|-1.45%|0.908|8.614|0.000|25.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5ccaccda97)|0.36209|0.36402|0.00037|0.10%|0.36273|-8.64%|0.36264|-8.65%|1.026|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67004|0.67216|0.00052|0.08%|0.67081|0.00%|0.67064|0.00%|1.139|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/113893b714)|0.66863|0.67099|0.00051|0.08%|0.66929|-0.23%|0.66917|-0.22%|1.297|8.124|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/5ccaccda97)|0.66866|0.67052|0.00046|0.07%|0.66928|-0.23%|0.66917|-0.22%|1.103|8.428|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5ccaccda97)|0.63505|0.64447|0.00132|0.21%|0.63572|-5.23%|0.63545|-5.25%|6.202|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59037|0.59524|0.00114|0.19%|0.59284|0.00%|0.59275|0.00%|0.171|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/113893b714)|0.58670|0.59460|0.00153|0.26%|0.58763|-0.88%|0.58721|-0.93%|3.749|8.000|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/5ccaccda97)|0.58690|0.59467|0.00106|0.18%|0.58759|-0.89%|0.58739|-0.90%|6.282|8.297|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5ccaccda97)|0.51700|0.52824|0.00162|0.31%|0.51829|-12.58%|0.51791|-12.63%|5.094|8.614|0.000|25.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44196|0.44584|0.00074|0.17%|0.44312|0.00%|0.44300|0.00%|1.456|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/113893b714)|0.44403|0.44658|0.00052|0.12%|0.44570|0.58%|0.44578|0.63%|-0.932|-8.324|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/5ccaccda97)|0.44368|0.44871|0.00089|0.20%|0.44577|0.60%|0.44580|0.63%|0.943|-8.317|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5ccaccda97)|0.14345|0.14429|0.00019|0.13%|0.14385|-67.54%|0.14381|-67.54%|0.286|8.614|0.000|25.33 MB|
