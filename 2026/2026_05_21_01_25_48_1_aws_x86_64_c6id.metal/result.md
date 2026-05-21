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
| Time          |2026-05-21 01:25:48 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26199847250 ([Artifacts](https://github.com/php/php-src/actions/runs/26199847250/artifacts/7125940358))|
| Changeset  |https://github.com/php/php-src/compare/f51c8d548d..755f4e6df0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39620|0.39773|0.00025|0.06%|0.39664|0.00%|0.39663|0.00%|1.834|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f51c8d548d)|0.38761|0.39109|0.00062|0.16%|0.38830|-2.10%|0.38814|-2.14%|3.222|8.614|0.000|25.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/755f4e6df0)|0.38728|0.39023|0.00055|0.14%|0.38800|-2.18%|0.38787|-2.21%|2.653|8.614|0.000|25.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/755f4e6df0)|0.35980|0.36312|0.00056|0.15%|0.36067|-9.07%|0.36053|-9.10%|2.130|8.614|0.000|25.21 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67507|0.67984|0.00072|0.11%|0.67565|0.00%|0.67547|0.00%|4.431|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f51c8d548d)|0.67126|0.67425|0.00054|0.08%|0.67184|-0.56%|0.67169|-0.56%|2.457|8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/755f4e6df0)|0.67133|0.67439|0.00058|0.09%|0.67193|-0.55%|0.67176|-0.55%|2.838|8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/755f4e6df0)|0.63782|0.67484|0.00518|0.81%|0.63909|-5.41%|0.63825|-5.51%|7.006|8.614|0.000|25.76 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58987|0.59420|0.00106|0.18%|0.59170|0.00%|0.59165|0.00%|0.349|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f51c8d548d)|0.58666|0.58994|0.00058|0.10%|0.58732|-0.74%|0.58719|-0.75%|2.349|8.607|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/755f4e6df0)|0.58633|0.58950|0.00060|0.10%|0.58715|-0.77%|0.58698|-0.79%|1.680|8.614|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/755f4e6df0)|0.51658|0.52064|0.00079|0.15%|0.51761|-12.52%|0.51748|-12.54%|2.653|8.614|0.000|25.78 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44180|0.44451|0.00054|0.12%|0.44302|0.00%|0.44297|0.00%|0.192|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f51c8d548d)|0.44931|0.45196|0.00053|0.12%|0.45069|1.73%|0.45079|1.77%|-0.438|-8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/755f4e6df0)|0.44921|0.45301|0.00063|0.14%|0.45046|1.68%|0.45046|1.69%|0.997|-8.614|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/755f4e6df0)|0.14353|0.14609|0.00061|0.42%|0.14406|-67.48%|0.14389|-67.52%|2.458|8.614|0.000|25.78 MB|
