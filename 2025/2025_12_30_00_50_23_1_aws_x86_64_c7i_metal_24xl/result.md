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
| Time          |2025-12-30 00:50:23 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47492|0.47842|0.00062|0.13%|0.47603|0.00%|0.47598|0.00%|1.000|0.999|180948010|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/04bf2e5c4a)|0.46898|0.47494|0.00085|0.18%|0.47045|-1.17%|0.47028|-1.20%|2.206|0.000|176335876|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/434b14e4a3)|0.46836|0.47283|0.00102|0.22%|0.46972|-1.33%|0.46943|-1.38%|1.597|0.000|176410071|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/434b14e4a3)|0.45005|0.45275|0.00047|0.10%|0.45093|-5.27%|0.45083|-5.28%|0.832|0.000|147898977|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74321|0.74742|0.00073|0.10%|0.74486|0.00%|0.74477|0.00%|0.573|0.999|291625158|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/04bf2e5c4a)|0.74462|0.75636|0.00125|0.17%|0.74619|0.18%|0.74604|0.17%|5.593|0.000|290415122|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/434b14e4a3)|0.74368|0.75416|0.00168|0.23%|0.74552|0.09%|0.74503|0.03%|3.306|0.001|290410196|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/434b14e4a3)|0.71682|0.72060|0.00069|0.10%|0.71864|-3.52%|0.71856|-3.52%|0.451|0.000|270766082|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57981|0.59136|0.00135|0.23%|0.58115|0.00%|0.58092|0.00%|4.930|0.999|1123338878|43.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/04bf2e5c4a)|0.58040|0.58997|0.00113|0.19%|0.58166|0.09%|0.58144|0.09%|4.453|0.000|1119543545|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/434b14e4a3)|0.57893|0.58276|0.00077|0.13%|0.58021|-0.16%|0.58010|-0.14%|0.951|0.000|1119546333|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/434b14e4a3)|0.51619|0.51903|0.00049|0.09%|0.51735|-10.98%|0.51735|-10.94%|0.569|0.000|865597807|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42896|0.44075|0.00232|0.53%|0.43459|0.00%|0.43447|0.00%|0.299|0.999|2020638191|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/04bf2e5c4a)|0.43487|0.44935|0.00215|0.49%|0.43978|1.19%|0.43966|1.19%|1.246|0.000|2020586642|27.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/434b14e4a3)|0.42379|0.47825|0.00573|1.34%|0.42793|-1.53%|0.42661|-1.81%|7.097|0.000|2020586689|27.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/434b14e4a3)|0.14395|0.15098|0.00146|0.99%|0.14684|-66.21%|0.14674|-66.23%|0.451|0.000|536605639|27.87 MB|
