### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.147-172.259.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250804|
| GCC           |11.5.0|
| Time          |2025-08-08 00:50:20 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46991|0.47237|0.00051|0.47131|0.00%|0.47128|0.00%|43.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c42e6d62d8)|0.46606|0.47254|0.00104|0.46735|-0.84%|0.46723|-0.86%|43.56 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe88711b14)|0.46657|0.46801|0.00033|0.46713|-0.89%|0.46708|-0.89%|43.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe88711b14)|0.44783|0.44931|0.00033|0.44861|-4.82%|0.44868|-4.80%|53.75 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73875|0.74289|0.00103|0.74011|0.00%|0.73999|0.00%|39.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c42e6d62d8)|0.72876|0.73965|0.00189|0.73005|-1.36%|0.72977|-1.38%|40.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe88711b14)|0.72879|0.73386|0.00116|0.72992|-1.38%|0.72963|-1.40%|40.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe88711b14)|0.69264|0.70417|0.00162|0.69842|-5.63%|0.69828|-5.64%|47.78 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57714|0.58514|0.00258|0.58020|0.00%|0.57893|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c42e6d62d8)|0.57772|0.58136|0.00079|0.57929|-0.16%|0.57923|0.05%|43.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe88711b14)|0.57730|0.58087|0.00085|0.57921|-0.17%|0.57921|0.05%|43.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe88711b14)|0.51598|0.51778|0.00044|0.51701|-10.89%|0.51701|-10.70%|61.38 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21347|0.21845|0.00127|0.21527|0.00%|0.21493|0.00%|26.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c42e6d62d8)|0.21253|0.21527|0.00067|0.21399|-0.60%|0.21405|-0.41%|26.56 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe88711b14)|0.21293|0.21600|0.00088|0.21433|-0.44%|0.21421|-0.34%|26.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe88711b14)|0.07354|0.07666|0.00069|0.07486|-65.23%|0.07483|-65.18%|27.79 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42165|1.43540|0.00374|1.42953|0.00%|1.43025|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c42e6d62d8)|1.33874|1.36395|0.00613|1.34850|-5.67%|1.34744|-5.79%|20.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe88711b14)|1.34008|1.35604|0.00394|1.34724|-5.76%|1.34594|-5.89%|20.84 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe88711b14)|0.57402|0.60081|0.00729|0.58372|-59.17%|0.58110|-59.37%|22.23 MB|
