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
| Time          |2026-10-22 01:04:26 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/39703491639 ([Artifacts](https://github.com/php/php-src/actions/runs/39703491639/artifacts/12395566097))|
| Changeset  |https://github.com/php/php-src/compare/b9ea38ef63..385f368057|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39525|0.39657|0.00022|0.06%|0.39565|0.00%|0.39562|0.00%|1.505|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b9ea38ef63)|0.37613|0.37905|0.00049|0.13%|0.37659|-4.82%|0.37652|-4.83%|3.647|8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/385f368057)|0.37572|0.37816|0.00042|0.11%|0.37611|-4.94%|0.37600|-4.96%|3.227|8.614|0.000|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/385f368057)|0.35007|0.35138|0.00031|0.09%|0.35058|-11.39%|0.35054|-11.39%|0.771|8.614|0.000|26.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67533|0.67814|0.00058|0.09%|0.67647|0.00%|0.67650|0.00%|0.260|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b9ea38ef63)|0.66807|0.67002|0.00037|0.06%|0.66862|-1.16%|0.66854|-1.18%|1.822|8.614|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/385f368057)|0.67081|0.67268|0.00046|0.07%|0.67128|-0.77%|0.67110|-0.80%|1.984|8.614|0.000|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/385f368057)|0.63458|0.64135|0.00121|0.19%|0.63541|-6.07%|0.63510|-6.12%|3.911|8.614|0.000|26.22 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58700|0.59045|0.00086|0.15%|0.58843|0.00%|0.58823|0.00%|0.646|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b9ea38ef63)|0.58602|0.59018|0.00090|0.15%|0.58697|-0.25%|0.58668|-0.26%|2.145|6.883|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/385f368057)|0.59124|0.59971|0.00140|0.24%|0.59261|0.71%|0.59227|0.69%|3.075|-8.614|0.000|26.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/385f368057)|0.51746|0.52112|0.00063|0.12%|0.51847|-11.89%|0.51837|-11.88%|2.314|8.614|0.000|26.27 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44343|0.44584|0.00063|0.14%|0.44460|0.00%|0.44464|0.00%|0.012|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b9ea38ef63)|0.45175|0.45385|0.00051|0.11%|0.45270|1.82%|0.45265|1.80%|0.138|-8.614|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/385f368057)|0.45121|0.45493|0.00072|0.16%|0.45333|1.96%|0.45322|1.93%|0.050|-8.614|0.000|26.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/385f368057)|0.14367|0.14564|0.00039|0.27%|0.14411|-67.59%|0.14405|-67.60%|2.663|8.614|0.000|26.27 MB|
