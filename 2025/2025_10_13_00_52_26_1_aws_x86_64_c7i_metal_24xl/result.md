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
| Time          |2025-10-13 00:52:26 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47555|0.48281|0.00089|0.19%|0.47685|0.00%|0.47675|0.00%|3.207|0.999|180947400|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f543f4951c)|0.46165|0.47310|0.00108|0.23%|0.46826|-1.80%|0.46824|-1.79%|-0.963|0.000|176322903|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ec9420db8)|0.46969|0.47298|0.00063|0.13%|0.47086|-1.26%|0.47078|-1.25%|0.873|0.000|176405293|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ec9420db8)|0.45079|0.45623|0.00077|0.17%|0.45211|-5.19%|0.45196|-5.20%|2.799|0.000|147865005|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74109|0.75424|0.00182|0.25%|0.74285|0.00%|0.74259|0.00%|4.806|0.999|291621388|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f543f4951c)|0.72717|0.74326|0.00178|0.24%|0.73660|-0.84%|0.73631|-0.85%|-0.471|0.000|287318662|40.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ec9420db8)|0.73546|0.74263|0.00125|0.17%|0.73735|-0.74%|0.73716|-0.73%|1.258|0.000|287319096|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ec9420db8)|0.70808|0.71175|0.00080|0.11%|0.70962|-4.47%|0.70958|-4.45%|0.270|0.000|267681481|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58125|0.59394|0.00200|0.34%|0.58339|0.00%|0.58277|0.00%|2.741|0.999|1123343298|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f543f4951c)|0.58375|0.58968|0.00138|0.24%|0.58587|0.42%|0.58541|0.45%|0.879|0.000|1120237155|44.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ec9420db8)|0.58366|0.59030|0.00150|0.26%|0.58553|0.37%|0.58493|0.37%|1.205|0.000|1120245612|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ec9420db8)|0.51569|0.52273|0.00117|0.23%|0.51964|-10.93%|0.51932|-10.89%|0.487|0.000|866297893|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42573|0.44439|0.00242|0.56%|0.43345|0.00%|0.43332|0.00%|0.926|0.999|2020638231|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f543f4951c)|0.43854|0.58809|0.02255|5.06%|0.44605|2.91%|0.44122|1.82%|5.018|0.000|2020594980|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ec9420db8)|0.43707|0.55252|0.02768|6.16%|0.44943|3.69%|0.44141|1.87%|3.148|0.000|2020595026|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ec9420db8)|0.14698|0.15180|0.00090|0.60%|0.14936|-65.54%|0.14939|-65.52%|0.264|0.000|536613077|27.68 MB|
