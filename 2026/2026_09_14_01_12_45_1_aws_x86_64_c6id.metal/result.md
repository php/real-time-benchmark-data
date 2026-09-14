### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-09-14 01:12:45 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/34795153467 ([Artifacts](https://github.com/php/php-src/actions/runs/34795153467/artifacts/10329178815))|
| Changeset  |https://github.com/php/php-src/compare/ae62043aa3..e783539fe5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39902|0.39995|0.00021|0.05%|0.39945|0.00%|0.39943|0.00%|0.572|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ae62043aa3)|0.37566|0.37701|0.00032|0.08%|0.37616|-5.83%|0.37606|-5.85%|0.836|8.614|0.000|25.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/e783539fe5)|0.37514|0.37641|0.00030|0.08%|0.37549|-6.00%|0.37542|-6.01%|1.568|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68063|0.68598|0.00100|0.15%|0.68215|0.00%|0.68192|0.00%|1.403|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ae62043aa3)|0.67127|0.67550|0.00093|0.14%|0.67319|-1.31%|0.67323|-1.28%|0.260|8.614|0.000|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/e783539fe5)|0.67374|0.67608|0.00058|0.09%|0.67451|-1.12%|0.67437|-1.11%|0.748|8.614|0.000|26.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59143|0.59542|0.00085|0.14%|0.59265|0.00%|0.59247|0.00%|0.912|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ae62043aa3)|0.59038|0.59374|0.00069|0.12%|0.59155|-0.19%|0.59150|-0.16%|0.902|6.215|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/e783539fe5)|0.58966|0.59629|0.00103|0.17%|0.59059|-0.35%|0.59030|-0.37%|3.850|7.849|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44373|0.45171|0.00114|0.26%|0.44490|0.00%|0.44472|0.00%|4.494|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ae62043aa3)|0.45081|0.45288|0.00050|0.11%|0.45183|1.56%|0.45175|1.58%|0.269|-8.448|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/e783539fe5)|0.45159|0.45387|0.00053|0.12%|0.45238|1.68%|0.45233|1.71%|0.769|-8.586|0.000|26.23 MB|
