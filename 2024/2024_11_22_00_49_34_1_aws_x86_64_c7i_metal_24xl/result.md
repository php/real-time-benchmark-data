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
| Kernel        |6.1.115-126.197.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241111|
| GCC           |11.4.1|
| Time          |2024-11-22 00:49:34 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43909|0.45377|0.00211|0.44024|0.00%|0.43988|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/91f0b3bc04)|0.43661|0.43909|0.00042|0.43779|-0.55%|0.43780|-0.47%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/ccda20b8d1)|0.43658|0.43833|0.00041|0.43749|-0.62%|0.43751|-0.54%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ccda20b8d1)|0.42390|0.42625|0.00045|0.42484|-3.50%|0.42482|-3.42%|50.74 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71258|0.71626|0.00065|0.71370|0.00%|0.71357|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/91f0b3bc04)|0.70844|0.71478|0.00116|0.71005|-0.51%|0.70975|-0.53%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/ccda20b8d1)|0.69696|0.70899|0.00155|0.70685|-0.96%|0.70698|-0.92%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ccda20b8d1)|0.68030|0.68337|0.00077|0.68147|-4.52%|0.68134|-4.52%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58074|0.58473|0.00072|0.58175|0.00%|0.58165|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/91f0b3bc04)|0.57972|0.58365|0.00064|0.58090|-0.15%|0.58078|-0.15%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/ccda20b8d1)|0.57339|0.57881|0.00131|0.57530|-1.11%|0.57493|-1.16%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ccda20b8d1)|0.52051|0.52609|0.00079|0.52268|-10.15%|0.52275|-10.13%|61.89 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21980|0.22426|0.00101|0.22152|0.00%|0.22134|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/91f0b3bc04)|0.21099|0.21572|0.00095|0.21296|-3.87%|0.21284|-3.84%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/ccda20b8d1)|0.21505|0.21762|0.00062|0.21602|-2.48%|0.21607|-2.38%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ccda20b8d1)|0.07386|0.07720|0.00072|0.07493|-66.18%|0.07483|-66.19%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34434|1.36234|0.00445|1.35227|0.00%|1.35138|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/91f0b3bc04)|1.29440|1.32293|0.00647|1.30580|-3.44%|1.30546|-3.40%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/ccda20b8d1)|1.27671|1.31078|0.00752|1.29037|-4.58%|1.28996|-4.54%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ccda20b8d1)|0.53338|0.55407|0.00542|0.54297|-59.85%|0.54365|-59.77%|21.69 MB|
