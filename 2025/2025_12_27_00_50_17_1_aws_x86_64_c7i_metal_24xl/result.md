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
| Time          |2025-12-27 00:50:17 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47677|0.47964|0.00060|0.12%|0.47800|0.00%|0.47795|0.00%|0.296|0.999|180943648|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/85b681a206)|0.46998|0.47503|0.00072|0.15%|0.47088|-1.49%|0.47078|-1.50%|2.487|0.000|176331922|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/77d306ef38)|0.47020|0.47646|0.00093|0.20%|0.47161|-1.34%|0.47140|-1.37%|2.327|0.000|176406310|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/77d306ef38)|0.45207|0.45448|0.00043|0.09%|0.45310|-5.21%|0.45306|-5.21%|0.963|0.000|147891921|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74452|0.75690|0.00190|0.25%|0.74695|0.00%|0.74664|0.00%|4.001|0.999|291621924|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/85b681a206)|0.73645|0.75499|0.00188|0.25%|0.74544|-0.20%|0.74515|-0.20%|1.381|0.000|290411304|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/77d306ef38)|0.74451|0.75758|0.00168|0.22%|0.74647|-0.06%|0.74609|-0.07%|3.496|0.001|290409638|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/77d306ef38)|0.71787|0.72365|0.00092|0.13%|0.71975|-3.64%|0.71969|-3.61%|1.346|0.000|270766426|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57654|0.58402|0.00205|0.35%|0.57882|0.00%|0.57785|0.00%|0.867|0.999|1123344623|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/85b681a206)|0.57695|0.58393|0.00184|0.32%|0.57925|0.07%|0.57856|0.12%|0.823|0.003|1119535518|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/77d306ef38)|0.57780|0.58454|0.00183|0.32%|0.58013|0.23%|0.57926|0.24%|0.843|0.000|1119536615|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/77d306ef38)|0.51430|0.51948|0.00146|0.28%|0.51622|-10.82%|0.51554|-10.78%|0.864|0.000|865598226|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42589|0.44306|0.00351|0.81%|0.43311|0.00%|0.43350|0.00%|-0.010|0.999|2020638121|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/85b681a206)|0.42371|0.44046|0.00291|0.68%|0.42746|-1.30%|0.42685|-1.53%|2.026|0.000|2020586668|27.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/77d306ef38)|0.43371|0.44671|0.00261|0.59%|0.43989|1.57%|0.43992|1.48%|-0.072|0.000|2020586664|27.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/77d306ef38)|0.13768|0.15151|0.00329|2.26%|0.14520|-66.47%|0.14636|-66.24%|-1.078|0.000|536605699|27.87 MB|
