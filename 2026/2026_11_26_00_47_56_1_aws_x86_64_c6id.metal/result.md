### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-11-26 00:47:56 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/45731208062 ([Artifacts](https://github.com/php/php-src/actions/runs/45731208062/artifacts/15078622951))|
| Changeset  |https://github.com/php/php-src/compare/a37b948c2a..7c1e712597|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39719|0.39962|0.00047|0.12%|0.39763|0.00%|0.39753|0.00%|2.777|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a37b948c2a)|0.37727|0.38294|0.00079|0.21%|0.37777|-5.00%|0.37760|-5.01%|5.951|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/7c1e712597)|0.37726|0.37789|0.00016|0.04%|0.37756|-5.05%|0.37753|-5.03%|0.414|8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7c1e712597)|0.35157|0.35295|0.00029|0.08%|0.35202|-11.47%|0.35199|-11.46%|0.764|8.614|0.000|26.35 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67627|0.68780|0.00168|0.25%|0.67717|0.00%|0.67666|0.00%|5.402|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a37b948c2a)|0.68202|0.68540|0.00068|0.10%|0.68313|0.88%|0.68296|0.93%|1.359|-8.269|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/7c1e712597)|0.68566|0.68937|0.00058|0.08%|0.68616|1.33%|0.68600|1.38%|3.877|-8.276|0.000|26.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7c1e712597)|0.65582|0.66771|0.00175|0.27%|0.65668|-3.03%|0.65629|-3.01%|5.554|8.614|0.000|26.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59136|0.59467|0.00080|0.13%|0.59296|0.00%|0.59295|0.00%|0.116|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a37b948c2a)|0.58731|0.59000|0.00054|0.09%|0.58800|-0.84%|0.58790|-0.85%|2.259|8.614|0.000|26.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/7c1e712597)|0.58696|0.58991|0.00057|0.10%|0.58772|-0.88%|0.58758|-0.91%|2.201|8.614|0.000|26.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7c1e712597)|0.51487|0.51710|0.00041|0.08%|0.51532|-13.09%|0.51522|-13.11%|2.431|8.614|0.000|26.43 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44337|0.44838|0.00079|0.18%|0.44465|0.00%|0.44450|0.00%|2.213|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a37b948c2a)|0.45398|0.45672|0.00062|0.14%|0.45568|2.48%|0.45570|2.52%|-0.589|-8.614|0.000|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/7c1e712597)|0.45560|0.45818|0.00057|0.13%|0.45665|2.70%|0.45659|2.72%|0.416|-8.614|0.000|26.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7c1e712597)|0.14825|0.15003|0.00027|0.18%|0.14861|-66.58%|0.14861|-66.57%|3.175|8.614|0.000|26.45 MB|
