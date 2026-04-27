### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.12.66-88.122.amzn2023.x86_64|
| OS            |Amazon Linux 2023.10.20260202|
| GCC           |14.2.1|
| Time          |2026-04-27 01:11:30 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24971893267 ([Artifacts](https://github.com/php/php-src/actions/runs/24971893267/artifacts/6652182751))|
| Changeset  |https://github.com/php/php-src/compare/9498bc3ee1..bd78496fb3|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39608|0.39815|0.00037|0.09%|0.39651|0.00%|0.39640|0.00%|3.020|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9498bc3ee1)|0.38790|0.38958|0.00031|0.08%|0.38845|-2.03%|0.38840|-2.02%|1.507|8.614|0.000|25.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/bd78496fb3)|0.38780|0.38899|0.00026|0.07%|0.38837|-2.05%|0.38833|-2.04%|0.583|8.614|0.000|25.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bd78496fb3)|0.36322|0.36525|0.00035|0.10%|0.36377|-8.26%|0.36373|-8.24%|1.567|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66800|0.67218|0.00078|0.12%|0.66875|0.00%|0.66851|0.00%|3.227|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9498bc3ee1)|0.66577|0.66834|0.00048|0.07%|0.66628|-0.37%|0.66613|-0.36%|2.283|8.538|0.000|25.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/bd78496fb3)|0.66572|0.66923|0.00060|0.09%|0.66652|-0.33%|0.66642|-0.31%|2.257|8.324|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bd78496fb3)|0.63458|0.63762|0.00049|0.08%|0.63576|-4.93%|0.63567|-4.91%|1.327|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59014|0.59519|0.00103|0.17%|0.59230|0.00%|0.59244|0.00%|0.152|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9498bc3ee1)|0.58664|0.59029|0.00062|0.11%|0.58737|-0.83%|0.58722|-0.88%|3.261|8.607|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/bd78496fb3)|0.58610|0.58898|0.00048|0.08%|0.58693|-0.91%|0.58676|-0.96%|1.891|8.614|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bd78496fb3)|0.51749|0.52036|0.00051|0.10%|0.51821|-12.51%|0.51808|-12.55%|2.834|8.614|0.000|25.67 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44173|0.44638|0.00070|0.16%|0.44294|0.00%|0.44284|0.00%|2.532|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9498bc3ee1)|0.44558|0.44800|0.00058|0.13%|0.44670|0.85%|0.44671|0.87%|0.256|-8.497|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/bd78496fb3)|0.44516|0.44907|0.00066|0.15%|0.44654|0.81%|0.44654|0.84%|0.756|-8.490|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bd78496fb3)|0.14310|0.14396|0.00020|0.14%|0.14360|-67.58%|0.14361|-67.57%|-0.287|8.614|0.000|25.67 MB|
