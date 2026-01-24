### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-24 00:50:17 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21306151268 ([Artifacts](#ARTIFACT_URL#))|
| Changeset  |https://github.com/php/php-src/compare/61845cc016..fb5d4784fe|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45140|0.45940|0.00121|0.27%|0.45234|0.00%|0.45212|0.00%|4.946|0.001|0.999|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61845cc016)|0.44644|0.45382|0.00079|0.18%|0.44723|-1.13%|0.44709|-1.11%|6.119|-11.979|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/fb5d4784fe)|0.44611|0.44838|0.00044|0.10%|0.44706|-1.17%|0.44703|-1.13%|0.819|-12.216|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fb5d4784fe)|0.42846|0.43299|0.00053|0.12%|0.42916|-5.12%|0.42903|-5.11%|3.928|-12.216|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.76967|0.78790|0.00191|0.25%|0.77592|0.00%|0.77570|0.00%|4.683|0.001|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61845cc016)|0.77316|0.77681|0.00068|0.09%|0.77435|-0.20%|0.77419|-0.19%|1.606|-10.175|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/fb5d4784fe)|0.76462|0.78118|0.00206|0.27%|0.77025|-0.73%|0.77034|-0.69%|1.461|-11.536|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fb5d4784fe)|1.00200|1.18317|0.02396|2.06%|1.16367|49.97%|1.17082|50.94%|-4.108|-12.216|0.000|27.01 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65877|0.68018|0.00290|0.44%|0.66003|0.00%|0.65959|0.00%|6.663|0.001|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61845cc016)|0.66428|0.68522|0.00198|0.30%|0.66615|0.93%|0.66587|0.95%|9.161|-11.732|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/fb5d4784fe)|0.66519|0.68570|0.00200|0.30%|0.66652|0.98%|0.66625|1.01%|9.102|-11.732|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fb5d4784fe)|0.59163|0.59362|0.00038|0.06%|0.59283|-10.18%|0.59283|-10.12%|-0.270|-12.216|0.000|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42483|0.45046|0.00265|0.62%|0.42830|0.00%|0.42799|0.00%|5.977|0.001|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61845cc016)|0.42352|0.43049|0.00139|0.33%|0.42678|-0.35%|0.42671|-0.30%|0.269|-5.869|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/fb5d4784fe)|0.42351|0.43033|0.00141|0.33%|0.42689|-0.33%|0.42683|-0.27%|0.046|-5.284|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fb5d4784fe)|0.13718|0.14463|0.00148|1.05%|0.14058|-67.18%|0.14038|-67.20%|0.383|-12.216|0.000|27.01 MB|
