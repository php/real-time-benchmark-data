### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-30 00:52:53 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21500318619 ([Artifacts](https://github.com/php/php-src/actions/runs/21500318619/artifacts/5312914874))|
| Changeset  |https://github.com/php/php-src/compare/4d5b651e90..df1a90eadc|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45095|0.45872|0.00143|0.32%|0.45213|0.00%|0.45184|0.00%|3.456|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d5b651e90)|0.44649|0.45160|0.00096|0.22%|0.44774|-0.97%|0.44748|-0.96%|1.530|12.128|0.000|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/df1a90eadc)|0.44684|0.45558|0.00114|0.25%|0.44815|-0.88%|0.44787|-0.88%|3.263|11.902|0.000|26.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/df1a90eadc)|0.42717|0.43003|0.00068|0.16%|0.42822|-5.29%|0.42809|-5.26%|0.837|12.216|0.000|26.99 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 250 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.73415|0.73804|0.00093|0.13%|0.73542|0.00%|0.73512|0.00%|1.172|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d5b651e90)|0.73247|0.74525|0.00140|0.19%|0.73384|-0.21%|0.73364|-0.20%|5.755|10.510|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/df1a90eadc)|0.73274|0.74598|0.00190|0.26%|0.73427|-0.16%|0.73388|-0.17%|4.629|8.716|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/df1a90eadc)|0.73668|0.74995|0.00182|0.25%|0.73849|0.42%|0.73807|0.40%|4.584|-11.693|0.000|27.00 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65936|0.68051|0.00386|0.58%|0.66141|0.00%|0.66059|0.00%|4.617|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d5b651e90)|0.66329|0.68400|0.00266|0.40%|0.66501|0.55%|0.66439|0.57%|5.184|-11.248|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/df1a90eadc)|0.66295|0.66873|0.00103|0.15%|0.66438|0.45%|0.66410|0.53%|2.576|-11.238|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/df1a90eadc)|0.59286|0.59838|0.00107|0.18%|0.59396|-10.20%|0.59375|-10.12%|2.875|12.216|0.000|27.00 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42537|0.43344|0.00130|0.30%|0.42981|0.00%|0.42975|0.00%|-0.069|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d5b651e90)|0.42373|0.43132|0.00138|0.32%|0.42714|-0.62%|0.42698|-0.64%|0.546|10.306|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/df1a90eadc)|0.42365|0.43131|0.00153|0.36%|0.42714|-0.62%|0.42694|-0.65%|0.460|10.004|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/df1a90eadc)|0.13795|0.14340|0.00111|0.79%|0.14050|-67.31%|0.14047|-67.31%|0.176|12.216|0.000|27.00 MB|
