### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-11-03 00:44:50 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/41554988825 ([Artifacts](https://github.com/php/php-src/actions/runs/41554988825/artifacts/13196595846))|
| Changeset  |https://github.com/php/php-src/compare/f4d80ce83e..0c7255dc52|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39708|0.39967|0.00074|0.19%|0.39793|0.00%|0.39762|0.00%|1.233|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f4d80ce83e)|0.38044|0.38186|0.00025|0.07%|0.38084|-4.30%|0.38082|-4.22%|1.649|8.614|0.000|25.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/0c7255dc52)|0.38078|0.38225|0.00030|0.08%|0.38123|-4.20%|0.38115|-4.14%|1.602|8.614|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0c7255dc52)|0.35562|0.35669|0.00026|0.07%|0.35601|-10.53%|0.35599|-10.47%|0.838|8.614|0.000|26.35 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67587|0.69939|0.00344|0.51%|0.67700|0.00%|0.67621|0.00%|6.019|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f4d80ce83e)|0.68609|0.68988|0.00071|0.10%|0.68706|1.49%|0.68686|1.57%|1.771|-8.269|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/0c7255dc52)|0.68092|0.68680|0.00094|0.14%|0.68179|0.71%|0.68160|0.80%|3.731|-7.938|0.000|26.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0c7255dc52)|0.64750|0.65685|0.00206|0.32%|0.64852|-4.21%|0.64797|-4.18%|3.689|8.614|0.000|26.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59084|0.59528|0.00094|0.16%|0.59238|0.00%|0.59238|0.00%|0.738|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f4d80ce83e)|0.59634|0.59901|0.00056|0.09%|0.59714|0.80%|0.59701|0.78%|1.659|-8.614|0.000|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/0c7255dc52)|0.59697|0.60050|0.00071|0.12%|0.59775|0.91%|0.59758|0.88%|2.334|-8.614|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0c7255dc52)|0.52487|0.52772|0.00060|0.11%|0.52561|-11.27%|0.52545|-11.30%|2.497|8.614|0.000|26.43 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44361|0.45104|0.00114|0.26%|0.44484|0.00%|0.44467|0.00%|3.781|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f4d80ce83e)|0.45202|0.45563|0.00073|0.16%|0.45423|2.11%|0.45416|2.13%|-0.442|-8.614|0.000|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/0c7255dc52)|0.45298|0.45596|0.00065|0.14%|0.45452|2.18%|0.45456|2.22%|-0.314|-8.614|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0c7255dc52)|0.14460|0.14732|0.00046|0.32%|0.14510|-67.38%|0.14500|-67.39%|3.055|8.614|0.000|26.43 MB|
