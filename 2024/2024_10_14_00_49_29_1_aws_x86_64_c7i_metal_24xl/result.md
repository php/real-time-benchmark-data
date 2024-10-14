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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20241001|
| GCC           |11.4.1|
| Time          |2024-10-14 00:49:29 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43709|0.44867|0.00199|0.43849|0.00%|0.43803|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b2ff871e38)|0.43560|0.44373|0.00168|0.43691|-0.36%|0.43648|-0.35%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/41c55d18f5)|0.43627|0.43775|0.00039|0.43702|-0.34%|0.43704|-0.23%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/41c55d18f5)|0.42283|0.42455|0.00039|0.42379|-3.35%|0.42376|-3.26%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71270|0.71648|0.00072|0.71460|0.00%|0.71454|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b2ff871e38)|0.70855|0.71125|0.00069|0.70955|-0.71%|0.70938|-0.72%|37.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/41c55d18f5)|0.70487|0.71173|0.00112|0.71007|-0.63%|0.71007|-0.62%|37.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/41c55d18f5)|0.68594|0.68884|0.00072|0.68689|-3.88%|0.68676|-3.89%|44.51 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58027|0.58245|0.00052|0.58106|0.00%|0.58093|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b2ff871e38)|0.57504|0.57783|0.00072|0.57626|-0.83%|0.57617|-0.82%|42.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/41c55d18f5)|0.57582|0.57771|0.00045|0.57687|-0.72%|0.57683|-0.71%|42.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/41c55d18f5)|0.51825|0.52009|0.00041|0.51925|-10.64%|0.51931|-10.61%|61.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21491|0.21870|0.00082|0.21612|0.00%|0.21605|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b2ff871e38)|0.21564|0.21936|0.00106|0.21663|0.24%|0.21647|0.20%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/41c55d18f5)|0.21506|0.21768|0.00071|0.21606|-0.03%|0.21606|0.01%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/41c55d18f5)|0.07477|0.07650|0.00046|0.07552|-65.06%|0.07548|-65.06%|27.35 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33915|1.36408|0.00584|1.35402|0.00%|1.35425|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b2ff871e38)|1.34795|1.36836|0.00465|1.35900|0.37%|1.35992|0.42%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/41c55d18f5)|1.35259|1.37230|0.00597|1.36102|0.52%|1.36140|0.53%|20.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/41c55d18f5)|0.58792|0.60342|0.00395|0.59475|-56.08%|0.59518|-56.05%|21.76 MB|
