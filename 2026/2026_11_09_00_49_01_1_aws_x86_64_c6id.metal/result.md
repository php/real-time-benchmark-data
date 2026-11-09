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
| Time          |2026-11-09 00:49:01 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/42542191524 ([Artifacts](https://github.com/php/php-src/actions/runs/42542191524/artifacts/13642734489))|
| Changeset  |https://github.com/php/php-src/compare/e78d4e6a06..497cf0875f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39750|0.40003|0.00066|0.17%|0.39817|0.00%|0.39790|0.00%|1.272|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e78d4e6a06)|0.37984|0.38115|0.00031|0.08%|0.38026|-4.50%|0.38021|-4.45%|1.448|8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/497cf0875f)|0.38202|0.38354|0.00028|0.07%|0.38244|-3.95%|0.38243|-3.89%|1.421|8.614|0.000|25.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/497cf0875f)|0.35685|0.35905|0.00033|0.09%|0.35735|-10.25%|0.35732|-10.20%|2.650|8.614|0.000|25.99 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66617|0.69896|0.00351|0.52%|0.67844|0.00%|0.67799|0.00%|3.369|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e78d4e6a06)|0.68722|0.69077|0.00077|0.11%|0.68808|1.42%|0.68785|1.45%|1.944|-8.269|0.000|26.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/497cf0875f)|0.68321|0.68476|0.00036|0.05%|0.68382|0.79%|0.68382|0.86%|0.304|-8.269|0.000|26.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/497cf0875f)|0.65049|0.65233|0.00040|0.06%|0.65118|-4.02%|0.65105|-3.97%|1.020|8.614|0.000|26.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59103|0.59462|0.00082|0.14%|0.59253|0.00%|0.59256|0.00%|0.033|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e78d4e6a06)|0.59738|0.60040|0.00062|0.10%|0.59823|0.96%|0.59808|0.93%|1.806|-8.614|0.000|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/497cf0875f)|0.59703|0.60009|0.00063|0.10%|0.59778|0.89%|0.59763|0.86%|2.518|-8.614|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/497cf0875f)|0.52403|0.52719|0.00066|0.13%|0.52480|-11.43%|0.52466|-11.46%|2.416|8.614|0.000|26.45 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44303|0.44563|0.00067|0.15%|0.44458|0.00%|0.44467|0.00%|-0.363|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e78d4e6a06)|0.45339|0.45662|0.00071|0.16%|0.45497|2.34%|0.45507|2.34%|-0.213|-8.614|0.000|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/497cf0875f)|0.45296|0.45543|0.00060|0.13%|0.45395|2.11%|0.45383|2.06%|0.450|-8.614|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/497cf0875f)|0.14471|0.14755|0.00046|0.32%|0.14553|-67.27%|0.14542|-67.30%|2.384|8.614|0.000|26.45 MB|
