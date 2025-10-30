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
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250818|
| GCC           |14.2.1|
| Time          |2025-10-30 00:50:27 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47589|0.47870|0.00056|0.12%|0.47700|0.00%|0.47695|0.00%|0.633|0.999|180948176|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/336fbf09d7)|0.46589|0.46955|0.00076|0.16%|0.46730|-2.03%|0.46714|-2.06%|0.956|0.000|176309884|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/6cf45c4bd5)|0.46887|0.47410|0.00102|0.22%|0.47024|-1.42%|0.47004|-1.45%|2.420|0.000|176403908|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6cf45c4bd5)|0.44864|0.45263|0.00057|0.13%|0.44959|-5.75%|0.44948|-5.76%|2.125|0.000|147872038|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74066|0.74448|0.00079|0.11%|0.74213|0.00%|0.74201|0.00%|0.723|0.999|291621380|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/336fbf09d7)|0.73162|0.74422|0.00238|0.32%|0.73405|-1.09%|0.73332|-1.17%|2.450|0.000|287324496|40.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/6cf45c4bd5)|0.73597|0.74592|0.00151|0.20%|0.73770|-0.60%|0.73744|-0.62%|3.278|0.000|287331677|40.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6cf45c4bd5)|0.69867|0.70938|0.00113|0.16%|0.70646|-4.81%|0.70650|-4.79%|-3.346|0.000|267694424|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58046|0.59264|0.00127|0.22%|0.58296|0.00%|0.58286|0.00%|4.492|0.999|1123345402|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/336fbf09d7)|0.58138|0.58538|0.00077|0.13%|0.58361|0.11%|0.58356|0.12%|-0.024|0.000|1120072895|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/6cf45c4bd5)|0.58436|0.58781|0.00071|0.12%|0.58600|0.52%|0.58593|0.53%|0.186|0.000|1120317660|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6cf45c4bd5)|0.51655|0.51969|0.00064|0.12%|0.51842|-11.07%|0.51850|-11.04%|-0.456|0.000|866368374|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42946|0.44138|0.00217|0.50%|0.43318|0.00%|0.43298|0.00%|0.910|0.999|2020638213|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/336fbf09d7)|0.42371|0.43626|0.00215|0.50%|0.42694|-1.44%|0.42654|-1.49%|1.890|0.000|2020586590|26.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/6cf45c4bd5)|0.42334|0.43769|0.00292|0.68%|0.42711|-1.40%|0.42619|-1.57%|2.198|0.000|2020586556|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6cf45c4bd5)|0.14440|0.15150|0.00128|0.87%|0.14698|-66.07%|0.14686|-66.08%|0.861|0.000|536605606|27.67 MB|
