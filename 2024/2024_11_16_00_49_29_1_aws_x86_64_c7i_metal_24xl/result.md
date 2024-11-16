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
| Kernel        |6.1.115-126.197.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241111|
| GCC           |11.4.1|
| Time          |2024-11-16 00:49:29 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43947|0.44142|0.00044|0.44020|0.00%|0.44015|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3f4bcd8cba)|0.43547|0.43737|0.00042|0.43627|-0.89%|0.43622|-0.89%|41.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/0de8e401db)|0.43596|0.43777|0.00045|0.43696|-0.74%|0.43700|-0.72%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0de8e401db)|0.42453|0.42680|0.00039|0.42528|-3.39%|0.42521|-3.40%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71271|0.71556|0.00068|0.71397|0.00%|0.71386|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3f4bcd8cba)|0.70922|0.71303|0.00072|0.71025|-0.52%|0.71014|-0.52%|37.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/0de8e401db)|0.70821|0.72528|0.00229|0.71036|-0.51%|0.70995|-0.55%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0de8e401db)|0.68159|0.68431|0.00060|0.68286|-4.36%|0.68295|-4.33%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57727|0.58403|0.00174|0.58122|0.00%|0.58178|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3f4bcd8cba)|0.58005|0.58204|0.00051|0.58095|-0.05%|0.58091|-0.15%|43.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/0de8e401db)|0.57885|0.58171|0.00060|0.58002|-0.21%|0.58006|-0.30%|43.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0de8e401db)|0.52140|0.52377|0.00042|0.52260|-10.09%|0.52258|-10.17%|61.89 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21470|0.21986|0.00105|0.21655|0.00%|0.21632|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3f4bcd8cba)|0.21170|0.21643|0.00111|0.21347|-1.42%|0.21320|-1.45%|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/0de8e401db)|0.21523|0.21821|0.00072|0.21659|0.02%|0.21646|0.06%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0de8e401db)|0.07302|0.07681|0.00088|0.07426|-65.71%|0.07401|-65.79%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34208|1.37140|0.00561|1.35097|0.00%|1.35046|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3f4bcd8cba)|1.27474|1.29562|0.00450|1.28466|-4.91%|1.28458|-4.88%|20.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/0de8e401db)|1.27285|1.30340|0.00659|1.28958|-4.54%|1.28935|-4.52%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0de8e401db)|0.51373|0.53461|0.00462|0.52405|-61.21%|0.52364|-61.23%|21.69 MB|
