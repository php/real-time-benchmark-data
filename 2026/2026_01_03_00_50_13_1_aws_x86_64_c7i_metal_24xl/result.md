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
| Time          |2026-01-03 00:50:13 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47437|0.48197|0.00087|0.18%|0.47568|0.00%|0.47555|0.00%|4.140|0.999|180946768|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8c4f806fe8)|0.46993|0.47603|0.00081|0.17%|0.47141|-0.90%|0.47125|-0.90%|2.524|0.000|176329315|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/4c9bbaa79d)|0.46429|0.47176|0.00083|0.18%|0.47016|-1.16%|0.47012|-1.14%|-3.315|0.000|176406001|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4c9bbaa79d)|0.44995|0.45479|0.00058|0.13%|0.45090|-5.21%|0.45083|-5.20%|3.255|0.000|147897067|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74280|0.75512|0.00136|0.18%|0.74476|0.00%|0.74449|0.00%|4.594|0.999|291620720|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8c4f806fe8)|0.74473|0.75872|0.00181|0.24%|0.74682|0.28%|0.74654|0.28%|4.591|0.000|290411947|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/4c9bbaa79d)|0.74232|0.75436|0.00158|0.21%|0.74436|-0.05%|0.74410|-0.05%|3.090|0.000|290408120|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4c9bbaa79d)|0.71599|0.72026|0.00093|0.13%|0.71780|-3.62%|0.71759|-3.61%|0.698|0.000|270763895|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57908|0.58353|0.00079|0.14%|0.58110|0.00%|0.58098|0.00%|0.536|0.999|1123345324|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8c4f806fe8)|0.57985|0.58371|0.00072|0.12%|0.58159|0.08%|0.58155|0.10%|0.447|0.000|1119531387|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/4c9bbaa79d)|0.57970|0.58462|0.00083|0.14%|0.58206|0.17%|0.58197|0.17%|0.388|0.000|1119535793|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4c9bbaa79d)|0.51663|0.51950|0.00057|0.11%|0.51801|-10.86%|0.51805|-10.83%|-0.030|0.000|865596739|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42535|0.43777|0.00224|0.52%|0.43410|0.00%|0.43412|0.00%|-0.690|0.999|2020638245|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8c4f806fe8)|0.42413|0.43695|0.00291|0.68%|0.42820|-1.36%|0.42716|-1.60%|1.477|0.000|2020586696|27.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/4c9bbaa79d)|0.42463|0.43900|0.00225|0.53%|0.42730|-1.57%|0.42666|-1.72%|2.371|0.000|2020586649|27.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4c9bbaa79d)|0.14633|0.15099|0.00098|0.66%|0.14858|-65.77%|0.14855|-65.78%|0.225|0.000|536605610|27.93 MB|
