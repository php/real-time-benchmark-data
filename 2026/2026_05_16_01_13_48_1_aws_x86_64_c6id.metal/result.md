### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-05-16 01:13:48 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25948881785 ([Artifacts](https://github.com/php/php-src/actions/runs/25948881785/artifacts/7029616789))|
| Changeset  |https://github.com/php/php-src/compare/0078a27630..b89e0ef305|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39264|0.39625|0.00088|0.22%|0.39363|0.00%|0.39318|0.00%|0.984|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0078a27630)|0.38580|0.38680|0.00025|0.06%|0.38621|-1.88%|0.38615|-1.79%|0.867|8.614|0.000|25.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/b89e0ef305)|0.38532|0.38748|0.00052|0.13%|0.38580|-1.99%|0.38561|-1.93%|1.931|8.614|0.000|25.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b89e0ef305)|0.35742|0.35917|0.00041|0.11%|0.35806|-9.04%|0.35801|-8.94%|0.837|8.614|0.000|25.51 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67058|0.67272|0.00044|0.07%|0.67135|0.00%|0.67125|0.00%|1.065|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0078a27630)|0.66434|0.66601|0.00034|0.05%|0.66484|-0.97%|0.66477|-0.97%|1.366|8.614|0.000|25.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/b89e0ef305)|0.66170|0.66484|0.00066|0.10%|0.66277|-1.28%|0.66273|-1.27%|1.086|8.614|0.000|25.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b89e0ef305)|0.63307|0.63866|0.00090|0.14%|0.63411|-5.55%|0.63395|-5.56%|3.075|8.614|0.000|25.39 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58628|0.59044|0.00107|0.18%|0.58811|0.00%|0.58796|0.00%|0.367|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0078a27630)|0.58243|0.58913|0.00109|0.19%|0.58330|-0.82%|0.58295|-0.85%|3.518|8.338|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/b89e0ef305)|0.58287|0.58587|0.00053|0.09%|0.58373|-0.74%|0.58359|-0.74%|2.106|8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b89e0ef305)|0.51210|0.51454|0.00054|0.10%|0.51260|-12.84%|0.51244|-12.84%|2.331|8.614|0.000|25.40 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44165|0.44428|0.00054|0.12%|0.44282|0.00%|0.44281|0.00%|0.092|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0078a27630)|0.44486|0.44885|0.00067|0.15%|0.44612|0.75%|0.44614|0.75%|1.291|-8.614|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/b89e0ef305)|0.44498|0.44711|0.00048|0.11%|0.44596|0.71%|0.44597|0.71%|0.228|-8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b89e0ef305)|0.14314|0.14540|0.00046|0.32%|0.14364|-67.56%|0.14355|-67.58%|2.791|8.614|0.000|25.40 MB|
