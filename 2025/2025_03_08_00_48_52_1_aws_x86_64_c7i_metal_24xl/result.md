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
| Kernel        |6.1.129-138.220.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250303|
| GCC           |11.4.1|
| Time          |2025-03-08 00:48:52 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43920|0.44099|0.00043|0.43997|0.00%|0.43999|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd586623b6)|0.43771|0.44069|0.00055|0.43830|-0.38%|0.43822|-0.40%|41.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/3772b502f6)|0.43466|0.43757|0.00067|0.43581|-0.95%|0.43563|-0.99%|41.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3772b502f6)|0.42540|0.42693|0.00044|0.42626|-3.12%|0.42624|-3.13%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71372|0.71609|0.00072|0.71488|0.00%|0.71497|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd586623b6)|0.70500|0.70839|0.00083|0.70621|-1.21%|0.70611|-1.24%|37.56 MB|
|[PHP - master](https://github.com/php/php-src/commit/3772b502f6)|0.69574|0.70783|0.00194|0.70533|-1.34%|0.70548|-1.33%|37.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3772b502f6)|0.67664|0.68038|0.00082|0.67784|-5.18%|0.67761|-5.23%|44.56 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58126|0.58324|0.00049|0.58232|0.00%|0.58229|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd586623b6)|0.57258|0.57958|0.00198|0.57642|-1.01%|0.57726|-0.86%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/3772b502f6)|0.57848|0.58107|0.00061|0.57960|-0.47%|0.57955|-0.47%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3772b502f6)|0.52162|0.52425|0.00058|0.52265|-10.25%|0.52252|-10.26%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21470|0.21759|0.00077|0.21577|0.00%|0.21548|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd586623b6)|0.21873|0.22171|0.00086|0.22009|2.00%|0.22017|2.17%|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/3772b502f6)|0.21581|0.21805|0.00065|0.21691|0.53%|0.21690|0.66%|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3772b502f6)|0.07477|0.07772|0.00063|0.07574|-64.90%|0.07574|-64.85%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33490|1.36290|0.00547|1.35006|0.00%|1.34897|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd586623b6)|1.27792|1.29328|0.00355|1.28405|-4.89%|1.28333|-4.87%|20.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/3772b502f6)|1.28654|1.31077|0.00592|1.29985|-3.72%|1.29956|-3.66%|20.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3772b502f6)|0.53302|0.55668|0.00571|0.54747|-59.45%|0.54792|-59.38%|21.80 MB|
