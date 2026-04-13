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
| Time          |2026-04-13 01:07:44 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24321013911 ([Artifacts](https://github.com/php/php-src/actions/runs/24321013911/artifacts/6397238045))|
| Changeset  |https://github.com/php/php-src/compare/3afd2cbbb8..21811294fa|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39442|0.39692|0.00071|0.18%|0.39511|0.00%|0.39476|0.00%|1.265|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3afd2cbbb8)|0.38794|0.38913|0.00028|0.07%|0.38838|-1.70%|0.38835|-1.62%|0.841|8.614|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/21811294fa)|0.38873|0.39288|0.00066|0.17%|0.38928|-1.48%|0.38911|-1.43%|4.056|8.614|0.000|25.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/21811294fa)|0.36144|0.36336|0.00032|0.09%|0.36207|-8.36%|0.36207|-8.28%|1.028|8.614|0.000|25.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66641|0.67054|0.00075|0.11%|0.66714|0.00%|0.66685|0.00%|2.789|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3afd2cbbb8)|0.66244|0.66523|0.00051|0.08%|0.66303|-0.62%|0.66289|-0.59%|2.047|8.614|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/21811294fa)|0.66266|0.66443|0.00038|0.06%|0.66342|-0.56%|0.66342|-0.51%|0.607|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/21811294fa)|0.63096|0.63856|0.00103|0.16%|0.63180|-5.30%|0.63159|-5.29%|6.037|8.614|0.000|25.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58806|0.59288|0.00111|0.19%|0.59005|0.00%|0.59012|0.00%|0.411|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3afd2cbbb8)|0.58441|0.58771|0.00058|0.10%|0.58539|-0.79%|0.58528|-0.82%|2.380|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/21811294fa)|0.58384|0.58682|0.00057|0.10%|0.58444|-0.95%|0.58431|-0.98%|2.689|8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/21811294fa)|0.51451|0.51793|0.00052|0.10%|0.51540|-12.65%|0.51531|-12.68%|2.439|8.614|0.000|25.22 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44173|0.44988|0.00115|0.26%|0.44292|0.00%|0.44269|0.00%|4.725|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3afd2cbbb8)|0.44477|0.44700|0.00052|0.12%|0.44575|0.64%|0.44577|0.70%|0.099|-8.269|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/21811294fa)|0.44473|0.44675|0.00048|0.11%|0.44573|0.63%|0.44574|0.69%|0.154|-8.269|0.000|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/21811294fa)|0.14318|0.14403|0.00018|0.13%|0.14359|-67.58%|0.14359|-67.56%|0.108|8.614|0.000|25.64 MB|
