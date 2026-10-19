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
| Time          |2026-10-19 01:10:49 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/39184123824 ([Artifacts](https://github.com/php/php-src/actions/runs/39184123824/artifacts/12157824951))|
| Changeset  |https://github.com/php/php-src/compare/17b6575a3d..b7256eee30|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39547|0.39771|0.00034|0.09%|0.39583|0.00%|0.39574|0.00%|3.672|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17b6575a3d)|0.37229|0.37353|0.00028|0.07%|0.37266|-5.85%|0.37257|-5.85%|1.255|8.614|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/b7256eee30)|0.37316|0.37568|0.00041|0.11%|0.37371|-5.59%|0.37360|-5.59%|2.726|8.614|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b7256eee30)|0.34909|0.35019|0.00023|0.07%|0.34953|-11.70%|0.34955|-11.67%|0.384|8.614|0.000|26.16 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67518|0.67864|0.00063|0.09%|0.67618|0.00%|0.67610|0.00%|1.522|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17b6575a3d)|0.66517|0.66807|0.00055|0.08%|0.66571|-1.55%|0.66556|-1.56%|2.362|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/b7256eee30)|0.66732|0.67526|0.00111|0.17%|0.66792|-1.22%|0.66772|-1.24%|6.064|8.600|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b7256eee30)|0.63305|0.63437|0.00027|0.04%|0.63363|-6.29%|0.63361|-6.29%|0.533|8.614|0.000|26.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58721|0.59101|0.00083|0.14%|0.58885|0.00%|0.58885|0.00%|0.329|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17b6575a3d)|0.58710|0.59074|0.00084|0.14%|0.58796|-0.15%|0.58770|-0.20%|1.926|5.394|0.000|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/b7256eee30)|0.58657|0.59010|0.00077|0.13%|0.58741|-0.25%|0.58715|-0.29%|2.008|6.880|0.000|26.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b7256eee30)|0.51359|0.51745|0.00069|0.13%|0.51441|-12.64%|0.51441|-12.64%|2.377|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44371|0.44599|0.00044|0.10%|0.44471|0.00%|0.44469|0.00%|0.283|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17b6575a3d)|0.45044|0.45473|0.00061|0.14%|0.45187|1.61%|0.45185|1.61%|1.921|-8.614|0.000|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/b7256eee30)|0.45268|0.45584|0.00068|0.15%|0.45406|2.10%|0.45408|2.11%|0.664|-8.614|0.000|26.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b7256eee30)|0.14357|0.14499|0.00029|0.20%|0.14418|-67.58%|0.14419|-67.58%|0.374|8.614|0.000|26.28 MB|
