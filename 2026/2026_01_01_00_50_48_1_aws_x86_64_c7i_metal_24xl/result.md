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
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-01 00:50:48 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47507|0.47811|0.00060|0.13%|0.47624|0.00%|0.47619|0.00%|0.894|0.999|180950433|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bc15a0dd4c)|0.47067|0.47349|0.00052|0.11%|0.47176|-0.94%|0.47175|-0.93%|0.538|0.000|176334752|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/241e43f2d8)|0.47056|0.47627|0.00071|0.15%|0.47159|-0.98%|0.47146|-0.99%|3.297|0.000|176411415|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/241e43f2d8)|0.44984|0.45469|0.00079|0.18%|0.45082|-5.34%|0.45068|-5.36%|3.283|0.000|147899412|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74328|0.75752|0.00175|0.23%|0.74487|0.00%|0.74460|0.00%|5.288|0.999|291623883|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bc15a0dd4c)|0.74475|0.74860|0.00075|0.10%|0.74611|0.17%|0.74604|0.19%|0.791|0.000|290412220|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/241e43f2d8)|0.73765|0.75427|0.00200|0.27%|0.74517|0.04%|0.74475|0.02%|1.734|0.164|290408652|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/241e43f2d8)|0.71710|0.72365|0.00089|0.12%|0.71883|-3.50%|0.71874|-3.47%|1.921|0.000|270763783|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57983|0.59111|0.00120|0.21%|0.58133|0.00%|0.58122|0.00%|5.624|0.999|1123339201|43.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bc15a0dd4c)|0.58024|0.58556|0.00078|0.13%|0.58177|0.08%|0.58165|0.07%|1.445|0.000|1119544312|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/241e43f2d8)|0.58015|0.58447|0.00078|0.13%|0.58159|0.04%|0.58152|0.05%|1.010|0.001|1119547151|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/241e43f2d8)|0.51437|0.52122|0.00072|0.14%|0.51860|-10.79%|0.51863|-10.77%|-1.432|0.000|865594999|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42690|0.44995|0.00271|0.62%|0.43412|0.00%|0.43378|0.00%|1.931|0.999|2020638167|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bc15a0dd4c)|0.42392|0.47902|0.00576|1.35%|0.42800|-1.41%|0.42665|-1.64%|7.254|0.000|2020586641|27.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/241e43f2d8)|0.42459|0.43821|0.00332|0.78%|0.42789|-1.44%|0.42673|-1.63%|1.818|0.000|2020586633|27.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/241e43f2d8)|0.14475|0.15009|0.00119|0.81%|0.14702|-66.13%|0.14711|-66.09%|0.148|0.000|536605706|27.93 MB|
