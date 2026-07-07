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
| Time          |2026-07-07 01:09:35 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28834269735 ([Artifacts](https://github.com/php/php-src/actions/runs/28834269735/artifacts/8126225650))|
| Changeset  |https://github.com/php/php-src/compare/8613e0ebdb..7330366438|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39473|0.39695|0.00074|0.19%|0.39537|0.00%|0.39502|0.00%|1.186|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8613e0ebdb)|0.38637|0.38836|0.00038|0.10%|0.38700|-2.12%|0.38697|-2.04%|1.134|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/7330366438)|0.38491|0.38734|0.00051|0.13%|0.38535|-2.53%|0.38523|-2.48%|2.981|8.614|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7330366438)|0.35846|0.36051|0.00036|0.10%|0.35909|-9.18%|0.35905|-9.11%|1.479|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67266|0.67496|0.00055|0.08%|0.67348|0.00%|0.67333|0.00%|1.013|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8613e0ebdb)|0.66505|0.66719|0.00054|0.08%|0.66585|-1.13%|0.66569|-1.13%|1.021|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/7330366438)|0.66333|0.66611|0.00060|0.09%|0.66412|-1.39%|0.66386|-1.41%|1.367|8.614|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7330366438)|0.63334|0.64519|0.00180|0.28%|0.63412|-5.84%|0.63372|-5.88%|5.306|8.614|0.000|26.20 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58882|0.59276|0.00089|0.15%|0.59045|0.00%|0.59050|0.00%|0.144|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8613e0ebdb)|0.58547|0.59383|0.00129|0.22%|0.58650|-0.67%|0.58615|-0.74%|4.222|8.228|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/7330366438)|0.58600|0.59016|0.00079|0.13%|0.58712|-0.56%|0.58695|-0.60%|2.482|8.386|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7330366438)|0.51650|0.52799|0.00177|0.34%|0.51765|-12.33%|0.51715|-12.42%|4.415|8.614|0.000|26.29 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44293|0.44517|0.00047|0.11%|0.44431|0.00%|0.44438|0.00%|-0.293|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8613e0ebdb)|0.44940|0.45193|0.00059|0.13%|0.45068|1.43%|0.45069|1.42%|0.025|-8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/7330366438)|0.44915|0.45189|0.00063|0.14%|0.45068|1.43%|0.45077|1.44%|-0.326|-8.614|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7330366438)|0.14404|0.14478|0.00018|0.13%|0.14444|-67.49%|0.14442|-67.50%|0.090|8.614|0.000|26.29 MB|
