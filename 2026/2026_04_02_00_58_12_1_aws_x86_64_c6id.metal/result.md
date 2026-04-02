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
| Time          |2026-04-02 00:58:12 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23878370806 ([Artifacts](https://github.com/php/php-src/actions/runs/23878370806/artifacts/6233509842))|
| Changeset  |https://github.com/php/php-src/compare/87b83459c5..75ed2091bc|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39446|0.39820|0.00082|0.21%|0.39518|0.00%|0.39482|0.00%|1.833|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87b83459c5)|0.38924|0.39134|0.00040|0.10%|0.38979|-1.36%|0.38970|-1.30%|2.021|8.614|0.000|25.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/75ed2091bc)|0.38759|0.38942|0.00038|0.10%|0.38808|-1.80%|0.38799|-1.73%|1.728|8.614|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/75ed2091bc)|0.35988|0.36213|0.00041|0.11%|0.36059|-8.75%|0.36057|-8.68%|1.789|8.614|0.000|25.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66659|0.66841|0.00046|0.07%|0.66729|0.00%|0.66714|0.00%|0.831|0.000|1.000|26.72 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87b83459c5)|0.66432|0.66571|0.00029|0.04%|0.66479|-0.38%|0.66474|-0.36%|1.285|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/75ed2091bc)|0.66427|0.67070|0.00138|0.21%|0.66649|-0.12%|0.66630|-0.13%|1.044|4.474|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/75ed2091bc)|0.63638|0.64282|0.00113|0.18%|0.63825|-4.35%|0.63802|-4.36%|2.027|8.614|0.000|25.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58840|0.59320|0.00096|0.16%|0.59029|0.00%|0.59006|0.00%|0.754|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87b83459c5)|0.58478|0.59014|0.00082|0.14%|0.58561|-0.79%|0.58544|-0.78%|3.997|8.428|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/75ed2091bc)|0.58435|0.58782|0.00075|0.13%|0.58523|-0.86%|0.58498|-0.86%|1.939|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/75ed2091bc)|0.51431|0.51671|0.00039|0.08%|0.51509|-12.74%|0.51506|-12.71%|1.416|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44148|0.44373|0.00056|0.13%|0.44264|0.00%|0.44268|0.00%|-0.206|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87b83459c5)|0.44294|0.44681|0.00085|0.19%|0.44520|0.58%|0.44519|0.57%|-0.326|-8.455|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/75ed2091bc)|0.44396|0.44653|0.00065|0.15%|0.44537|0.62%|0.44527|0.59%|-0.128|-8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/75ed2091bc)|0.14325|0.14500|0.00032|0.23%|0.14376|-67.52%|0.14373|-67.53%|1.686|8.614|0.000|25.39 MB|
