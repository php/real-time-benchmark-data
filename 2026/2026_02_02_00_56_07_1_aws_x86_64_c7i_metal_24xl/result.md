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
| Time          |2026-02-02 00:56:07 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21573659303 ([Artifacts](https://github.com/php/php-src/actions/runs/21573659303/artifacts/5337422940))|
| Changeset  |https://github.com/php/php-src/compare/6173a9a109..a01a8e72ac|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45066|0.45791|0.00101|0.22%|0.45129|0.00%|0.45110|0.00%|5.535|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6173a9a109)|0.44575|0.45281|0.00097|0.22%|0.44653|-1.06%|0.44621|-1.08%|3.978|11.935|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/a01a8e72ac)|0.44554|0.45232|0.00086|0.19%|0.44638|-1.09%|0.44616|-1.09%|4.403|11.984|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a01a8e72ac)|0.42575|0.43219|0.00081|0.19%|0.42649|-5.50%|0.42628|-5.50%|4.292|12.216|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 250 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.73473|0.73973|0.00082|0.11%|0.73620|0.00%|0.73609|0.00%|1.961|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6173a9a109)|0.73360|0.74603|0.00138|0.19%|0.73505|-0.16%|0.73483|-0.17%|5.366|9.372|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/a01a8e72ac)|0.73320|0.73694|0.00082|0.11%|0.73467|-0.21%|0.73451|-0.21%|0.901|9.853|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a01a8e72ac)|0.73612|0.74835|0.00144|0.19%|0.73785|0.22%|0.73755|0.20%|4.393|-10.391|0.000|27.01 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.64596|0.65162|0.00068|0.10%|0.64701|0.00%|0.64690|0.00%|3.629|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6173a9a109)|0.64934|0.67215|0.00356|0.55%|0.65078|0.58%|0.65004|0.49%|5.239|-11.988|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/a01a8e72ac)|0.64876|0.66856|0.00215|0.33%|0.65023|0.50%|0.64980|0.45%|6.674|-11.991|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a01a8e72ac)|0.57980|0.58477|0.00115|0.20%|0.58100|-10.20%|0.58069|-10.23%|2.361|12.216|0.000|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42723|0.43407|0.00128|0.30%|0.42975|0.00%|0.42963|0.00%|0.456|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6173a9a109)|0.42282|0.42912|0.00141|0.33%|0.42534|-1.02%|0.42516|-1.04%|0.755|11.857|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/a01a8e72ac)|0.42285|0.42961|0.00130|0.31%|0.42547|-0.99%|0.42536|-0.99%|0.504|11.957|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a01a8e72ac)|0.13848|0.14447|0.00130|0.92%|0.14103|-67.18%|0.14081|-67.23%|0.409|12.216|0.000|27.01 MB|
