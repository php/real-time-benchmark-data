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
| Kernel        |6.12.55-74.119.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251110|
| GCC           |14.2.1|
| Time          |2025-11-15 00:50:06 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47196|0.47585|0.00066|0.14%|0.47331|0.00%|0.47320|0.00%|1.001|0.999|180952355|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9cd367362d)|0.46352|0.47153|0.00092|0.20%|0.46464|-1.83%|0.46446|-1.85%|4.595|0.000|176334492|43.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/0375060d16)|0.46508|0.47190|0.00087|0.19%|0.46609|-1.52%|0.46599|-1.52%|3.590|0.000|176323203|43.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0375060d16)|0.44102|0.44935|0.00084|0.19%|0.44759|-5.43%|0.44763|-5.40%|-4.547|0.000|147888303|53.23 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70220|0.72701|0.00261|0.37%|0.71169|0.00%|0.71114|0.00%|3.475|0.999|291622160|40.14 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9cd367362d)|0.70794|0.71468|0.00146|0.21%|0.70991|-0.25%|0.70947|-0.23%|1.235|0.000|290398839|40.09 MB|
|[PHP - master](https://github.com/php/php-src/commit/0375060d16)|0.70932|0.72910|0.00268|0.38%|0.71163|-0.01%|0.71108|-0.01%|5.599|0.384|290399550|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0375060d16)|0.68215|0.68693|0.00098|0.14%|0.68367|-3.94%|0.68348|-3.89%|1.488|0.000|270764424|47.23 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57487|0.57939|0.00083|0.14%|0.57630|0.00%|0.57619|0.00%|1.159|0.999|1123396045|43.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9cd367362d)|0.57144|0.58449|0.00143|0.25%|0.57300|-0.57%|0.57277|-0.59%|5.777|0.000|1119674175|43.84 MB|
|[PHP - master](https://github.com/php/php-src/commit/0375060d16)|0.57229|0.57614|0.00078|0.14%|0.57344|-0.50%|0.57328|-0.50%|1.126|0.000|1119680705|43.84 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0375060d16)|0.51099|0.51636|0.00074|0.14%|0.51226|-11.11%|0.51224|-11.10%|1.757|0.000|865736586|61.34 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43029|0.44408|0.00208|0.48%|0.43386|0.00%|0.43392|0.00%|1.222|0.999|2020638193|26.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9cd367362d)|0.42557|0.43996|0.00309|0.72%|0.42861|-1.21%|0.42757|-1.46%|2.203|0.000|2020586689|26.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/0375060d16)|0.42598|0.44009|0.00286|0.67%|0.42881|-1.16%|0.42769|-1.44%|2.173|0.000|2020586651|26.68 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0375060d16)|0.14122|0.15081|0.00118|0.79%|0.14872|-65.72%|0.14870|-65.73%|-2.440|0.000|536605692|27.56 MB|
