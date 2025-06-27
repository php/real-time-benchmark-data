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
| Kernel        |6.1.141-155.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250623|
| GCC           |11.5.0|
| Time          |2025-06-27 00:49:57 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44102|0.45359|0.00225|0.44227|0.00%|0.44171|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8b61c49987)|0.44003|0.44262|0.00051|0.44072|-0.35%|0.44065|-0.24%|42.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/1b7f4567cb)|0.43906|0.44185|0.00063|0.44016|-0.48%|0.44022|-0.34%|42.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1b7f4567cb)|0.42352|0.42641|0.00058|0.42438|-4.04%|0.42442|-3.92%|51.60 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71355|0.71737|0.00094|0.71515|0.00%|0.71505|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8b61c49987)|0.70765|0.71225|0.00112|0.70925|-0.83%|0.70907|-0.84%|38.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/1b7f4567cb)|0.70812|0.71318|0.00115|0.71014|-0.70%|0.71006|-0.70%|38.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1b7f4567cb)|0.68160|0.68448|0.00073|0.68280|-4.52%|0.68253|-4.55%|45.21 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58339|0.59372|0.00183|0.58493|0.00%|0.58476|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8b61c49987)|0.58343|0.58688|0.00069|0.58473|-0.03%|0.58482|0.01%|43.72 MB|
|[PHP - master](https://github.com/php/php-src/commit/1b7f4567cb)|0.58219|0.58489|0.00056|0.58307|-0.32%|0.58290|-0.32%|43.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1b7f4567cb)|0.52562|0.52781|0.00042|0.52686|-9.93%|0.52696|-9.88%|61.65 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21358|0.21813|0.00105|0.21598|0.00%|0.21604|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8b61c49987)|0.21440|0.21832|0.00103|0.21601|0.01%|0.21591|-0.06%|26.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/1b7f4567cb)|0.21620|0.22151|0.00141|0.21827|1.06%|0.21798|0.90%|26.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1b7f4567cb)|0.07671|0.07870|0.00053|0.07743|-64.15%|0.07743|-64.16%|28.01 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41357|1.43592|0.00534|1.42762|0.00%|1.42887|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8b61c49987)|1.29231|1.31042|0.00421|1.29843|-9.05%|1.29739|-9.20%|21.02 MB|
|[PHP - master](https://github.com/php/php-src/commit/1b7f4567cb)|1.31473|1.32923|0.00318|1.32032|-7.52%|1.32016|-7.61%|21.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1b7f4567cb)|0.54476|0.56685|0.00499|0.55859|-60.87%|0.55923|-60.86%|22.44 MB|
