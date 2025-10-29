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
| Time          |2025-10-29 00:50:25 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47721|0.48128|0.00074|0.16%|0.47857|0.00%|0.47842|0.00%|0.838|0.999|180948011|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/be1993bc10)|0.46782|0.47141|0.00077|0.16%|0.46904|-1.99%|0.46889|-1.99%|1.120|0.000|176310648|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/336fbf09d7)|0.46217|0.47420|0.00114|0.24%|0.46919|-1.96%|0.46907|-1.95%|-1.229|0.000|176382196|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/336fbf09d7)|0.45058|0.45327|0.00057|0.13%|0.45157|-5.64%|0.45147|-5.63%|0.802|0.000|147851504|53.38 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74325|0.75664|0.00147|0.20%|0.74510|0.00%|0.74494|0.00%|4.966|0.999|291621411|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/be1993bc10)|0.72792|0.74824|0.00241|0.33%|0.73880|-0.85%|0.73812|-0.92%|0.574|0.000|287324596|40.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/336fbf09d7)|0.73465|0.74620|0.00214|0.29%|0.73791|-0.97%|0.73719|-1.04%|1.444|0.000|287324423|40.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/336fbf09d7)|0.71160|0.71568|0.00077|0.11%|0.71313|-4.29%|0.71309|-4.28%|0.510|0.000|267687406|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58081|0.59314|0.00167|0.29%|0.58289|0.00%|0.58272|0.00%|4.537|0.999|1123345090|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/be1993bc10)|0.57909|0.58618|0.00101|0.17%|0.58323|0.06%|0.58328|0.09%|-0.138|0.000|1120073278|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/336fbf09d7)|0.58080|0.58738|0.00099|0.17%|0.58366|0.13%|0.58354|0.14%|0.456|0.000|1120081952|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/336fbf09d7)|0.51621|0.51987|0.00065|0.13%|0.51843|-11.06%|0.51842|-11.04%|-0.355|0.000|866131804|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42624|0.44230|0.00226|0.52%|0.43368|0.00%|0.43341|0.00%|0.364|0.999|2020638168|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/be1993bc10)|0.42408|0.43839|0.00277|0.65%|0.42730|-1.47%|0.42664|-1.56%|1.964|0.000|2020586644|26.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/336fbf09d7)|0.42414|0.43821|0.00326|0.76%|0.42760|-1.40%|0.42661|-1.57%|1.870|0.000|2020586604|26.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/336fbf09d7)|0.14424|0.14974|0.00125|0.85%|0.14684|-66.14%|0.14684|-66.12%|0.073|0.000|536605590|27.67 MB|
