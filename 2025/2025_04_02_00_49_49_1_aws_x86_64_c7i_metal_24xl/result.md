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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-02 00:49:49 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43777|0.44018|0.00049|0.43868|0.00%|0.43862|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/13e0fb92b4)|0.43475|0.43631|0.00048|0.43535|-0.76%|0.43514|-0.79%|41.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/011795bcbe)|0.43599|0.43765|0.00038|0.43657|-0.48%|0.43651|-0.48%|41.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/011795bcbe)|0.42687|0.42874|0.00045|0.42775|-2.49%|0.42775|-2.48%|50.92 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71039|0.71345|0.00071|0.71163|0.00%|0.71153|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/13e0fb92b4)|0.70251|0.70540|0.00063|0.70338|-1.16%|0.70322|-1.17%|37.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/011795bcbe)|0.70475|0.70696|0.00059|0.70584|-0.81%|0.70578|-0.81%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/011795bcbe)|0.67840|0.68025|0.00049|0.67931|-4.54%|0.67922|-4.54%|44.77 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58024|0.58263|0.00060|0.58123|0.00%|0.58102|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/13e0fb92b4)|0.57433|0.59020|0.00297|0.57948|-0.30%|0.58016|-0.15%|43.02 MB|
|[PHP - master](https://github.com/php/php-src/commit/011795bcbe)|0.57950|0.58227|0.00055|0.58046|-0.13%|0.58044|-0.10%|43.02 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/011795bcbe)|0.52182|0.52358|0.00044|0.52266|-10.08%|0.52265|-10.04%|62.19 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21547|0.21898|0.00089|0.21691|0.00%|0.21690|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/13e0fb92b4)|0.21350|0.21668|0.00088|0.21473|-1.00%|0.21458|-1.07%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/011795bcbe)|0.21677|0.22332|0.00127|0.21840|0.69%|0.21834|0.67%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/011795bcbe)|0.07503|0.07859|0.00091|0.07654|-64.71%|0.07650|-64.73%|27.46 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33602|1.35828|0.00539|1.34672|0.00%|1.34764|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/13e0fb92b4)|1.25683|1.27869|0.00507|1.26648|-5.96%|1.26618|-6.04%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/011795bcbe)|1.31181|1.32719|0.00380|1.31992|-1.99%|1.32030|-2.03%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/011795bcbe)|0.54054|0.55246|0.00324|0.54536|-59.50%|0.54550|-59.52%|21.88 MB|
