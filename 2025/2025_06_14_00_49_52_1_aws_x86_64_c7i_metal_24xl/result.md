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
| Kernel        |6.1.140-154.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250609|
| GCC           |11.5.0|
| Time          |2025-06-14 00:49:52 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44044|0.44357|0.00064|0.44121|0.00%|0.44117|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5740038026)|0.43758|0.44055|0.00064|0.43837|-0.64%|0.43828|-0.66%|42.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/7361a1206d)|0.43974|0.44479|0.00090|0.44096|-0.06%|0.44067|-0.11%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7361a1206d)|0.42442|0.42547|0.00025|0.42491|-3.70%|0.42492|-3.68%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71454|0.71816|0.00078|0.71635|0.00%|0.71646|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5740038026)|0.70863|0.72175|0.00229|0.71004|-0.88%|0.70964|-0.95%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/7361a1206d)|0.71116|0.72358|0.00220|0.71293|-0.48%|0.71231|-0.58%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7361a1206d)|0.68027|0.68352|0.00079|0.68134|-4.89%|0.68128|-4.91%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58113|0.58415|0.00076|0.58227|0.00%|0.58210|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5740038026)|0.57917|0.58165|0.00065|0.58010|-0.37%|0.57987|-0.38%|43.61 MB|
|[PHP - master](https://github.com/php/php-src/commit/7361a1206d)|0.58036|0.58241|0.00051|0.58116|-0.19%|0.58102|-0.18%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7361a1206d)|0.52575|0.52856|0.00054|0.52707|-9.48%|0.52705|-9.46%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21483|0.22052|0.00138|0.21706|0.00%|0.21674|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5740038026)|0.21926|0.22394|0.00117|0.22153|2.06%|0.22132|2.11%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/7361a1206d)|0.21555|0.22033|0.00116|0.21753|0.22%|0.21729|0.26%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7361a1206d)|0.07571|0.07774|0.00059|0.07663|-64.70%|0.07649|-64.71%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34170|1.36348|0.00505|1.35164|0.00%|1.35078|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5740038026)|1.28041|1.29594|0.00378|1.28808|-4.70%|1.28809|-4.64%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/7361a1206d)|1.31655|1.33360|0.00453|1.32460|-2.00%|1.32405|-1.98%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7361a1206d)|0.55705|0.57831|0.00515|0.56866|-57.93%|0.56977|-57.82%|22.23 MB|
