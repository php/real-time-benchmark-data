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
| Time          |2026-04-01 01:07:13 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23826900717 ([Artifacts](https://github.com/php/php-src/actions/runs/23826900717/artifacts/6212183368))|
| Changeset  |https://github.com/php/php-src/compare/b1710f48ba..87b83459c5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39949|0.40199|0.00071|0.18%|0.40033|0.00%|0.40003|0.00%|1.211|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b1710f48ba)|0.39388|0.39595|0.00038|0.10%|0.39433|-1.50%|0.39421|-1.45%|1.812|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/87b83459c5)|0.39465|0.39713|0.00053|0.13%|0.39534|-1.25%|0.39517|-1.21%|1.333|8.614|0.000|25.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87b83459c5)|0.36627|0.36944|0.00062|0.17%|0.36723|-8.27%|0.36711|-8.23%|1.525|8.614|0.000|25.28 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67334|0.67595|0.00059|0.09%|0.67404|0.00%|0.67384|0.00%|1.372|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b1710f48ba)|0.66798|0.67468|0.00096|0.14%|0.66854|-0.81%|0.66831|-0.82%|5.608|8.324|0.000|25.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/87b83459c5)|0.67123|0.67277|0.00033|0.05%|0.67174|-0.34%|0.67167|-0.32%|0.872|8.614|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87b83459c5)|0.63682|0.64080|0.00065|0.10%|0.63770|-5.39%|0.63754|-5.39%|2.639|8.614|0.000|25.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59168|0.59624|0.00118|0.20%|0.59419|0.00%|0.59405|0.00%|-0.057|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b1710f48ba)|0.58888|0.59741|0.00132|0.22%|0.58980|-0.74%|0.58949|-0.77%|4.302|8.242|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/87b83459c5)|0.58947|0.59290|0.00067|0.11%|0.59008|-0.69%|0.58989|-0.70%|2.881|8.538|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87b83459c5)|0.51981|0.52320|0.00054|0.10%|0.52058|-12.39%|0.52046|-12.39%|2.461|8.614|0.000|25.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44159|0.44406|0.00055|0.13%|0.44302|0.00%|0.44299|0.00%|0.029|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b1710f48ba)|0.44252|0.44651|0.00090|0.20%|0.44467|0.37%|0.44483|0.42%|-0.469|-7.390|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/87b83459c5)|0.44256|0.45155|0.00127|0.28%|0.44561|0.59%|0.44547|0.56%|1.967|-8.290|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87b83459c5)|0.14343|0.14525|0.00029|0.20%|0.14396|-67.50%|0.14396|-67.50%|1.751|8.614|0.000|25.33 MB|
