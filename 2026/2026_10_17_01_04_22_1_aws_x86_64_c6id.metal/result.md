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
| Time          |2026-10-17 01:04:22 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/38989242142 ([Artifacts](https://github.com/php/php-src/actions/runs/38989242142/artifacts/12085253424))|
| Changeset  |https://github.com/php/php-src/compare/de6f052c36..070ce2f9d7|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39625|0.39793|0.00027|0.07%|0.39658|0.00%|0.39653|0.00%|2.695|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de6f052c36)|0.37326|0.37479|0.00026|0.07%|0.37374|-5.76%|0.37371|-5.76%|1.349|8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/070ce2f9d7)|0.37295|0.37675|0.00052|0.14%|0.37338|-5.85%|0.37331|-5.86%|5.752|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/070ce2f9d7)|0.34959|0.35167|0.00033|0.09%|0.35009|-11.72%|0.35006|-11.72%|2.370|8.614|0.000|26.18 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67547|0.68554|0.00165|0.24%|0.67743|0.00%|0.67712|0.00%|3.383|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de6f052c36)|0.66715|0.66863|0.00029|0.04%|0.66780|-1.42%|0.66777|-1.38%|0.866|8.614|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/070ce2f9d7)|0.66505|0.66727|0.00043|0.06%|0.66562|-1.74%|0.66556|-1.71%|1.411|8.614|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/070ce2f9d7)|0.63365|0.64512|0.00171|0.27%|0.63467|-6.31%|0.63428|-6.33%|5.054|8.614|0.000|26.29 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58797|0.59144|0.00083|0.14%|0.58950|0.00%|0.58948|0.00%|0.348|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de6f052c36)|0.58848|0.59162|0.00057|0.10%|0.58939|-0.02%|0.58932|-0.03%|1.998|1.000|0.318|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/070ce2f9d7)|0.58742|0.59151|0.00103|0.18%|0.58854|-0.16%|0.58816|-0.22%|1.630|5.305|0.000|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/070ce2f9d7)|0.51496|0.52637|0.00163|0.32%|0.51617|-12.44%|0.51579|-12.50%|5.271|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44341|0.44591|0.00054|0.12%|0.44457|0.00%|0.44447|0.00%|0.332|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de6f052c36)|0.45155|0.45368|0.00054|0.12%|0.45253|1.79%|0.45242|1.79%|0.334|-8.614|0.000|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/070ce2f9d7)|0.45044|0.45253|0.00043|0.10%|0.45170|1.60%|0.45173|1.63%|-0.155|-8.614|0.000|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/070ce2f9d7)|0.14366|0.14461|0.00022|0.15%|0.14413|-67.58%|0.14414|-67.57%|-0.033|8.614|0.000|26.24 MB|
