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
| Time          |2026-09-01 01:17:17 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33458121389 ([Artifacts](https://github.com/php/php-src/actions/runs/33458121389/artifacts/9782827744))|
| Changeset  |https://github.com/php/php-src/compare/f142b81588..4923c6079e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39904|0.40225|0.00046|0.11%|0.39950|0.00%|0.39943|0.00%|4.790|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f142b81588)|0.37592|0.37791|0.00047|0.12%|0.37654|-5.75%|0.37639|-5.77%|1.408|8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/4923c6079e)|0.37396|0.37613|0.00055|0.15%|0.37443|-6.28%|0.37416|-6.33%|1.664|8.614|0.000|25.88 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68014|0.69149|0.00160|0.23%|0.68175|0.00%|0.68155|0.00%|4.733|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f142b81588)|0.67102|0.68215|0.00226|0.34%|0.67245|-1.37%|0.67155|-1.47%|2.720|8.366|0.000|25.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/4923c6079e)|0.67179|0.67381|0.00051|0.08%|0.67253|-1.35%|0.67238|-1.35%|0.781|8.614|0.000|25.90 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59074|0.59462|0.00074|0.13%|0.59226|0.00%|0.59218|0.00%|0.839|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f142b81588)|0.59019|0.59587|0.00121|0.20%|0.59152|-0.13%|0.59131|-0.15%|1.897|4.943|0.000|25.95 MB|
|[PHP - master](https://github.com/php/php-src/commit/4923c6079e)|0.58878|0.59416|0.00102|0.17%|0.59003|-0.38%|0.58973|-0.41%|2.676|7.594|0.000|25.94 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44360|0.45138|0.00111|0.25%|0.44492|0.00%|0.44482|0.00%|4.083|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f142b81588)|0.45022|0.45329|0.00069|0.15%|0.45138|1.45%|0.45135|1.47%|0.520|-8.441|0.000|25.95 MB|
|[PHP - master](https://github.com/php/php-src/commit/4923c6079e)|0.44986|0.45446|0.00090|0.20%|0.45143|1.46%|0.45125|1.45%|0.875|-8.428|0.000|25.94 MB|
