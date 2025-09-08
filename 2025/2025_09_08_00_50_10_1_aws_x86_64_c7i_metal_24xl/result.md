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
| Time          |2025-09-08 00:50:10 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46388|0.47682|0.00128|0.27%|0.47144|0.00%|0.47150|0.00%|-2.966|0.999|180916856|43.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b90ab8119e)|0.46694|0.47037|0.00061|0.13%|0.46782|-0.77%|0.46770|-0.81%|1.806|0.000|176227514|44.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e8058e776)|0.46429|0.47281|0.00104|0.22%|0.46886|-0.55%|0.46870|-0.59%|0.797|0.000|176367496|43.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e8058e776)|0.44873|0.45130|0.00043|0.10%|0.44954|-4.65%|0.44948|-4.67%|1.089|0.000|147823501|53.38 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73740|0.74817|0.00134|0.18%|0.73921|0.00%|0.73896|0.00%|3.403|0.999|291580911|39.81 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b90ab8119e)|0.73365|0.74325|0.00211|0.29%|0.73614|-0.42%|0.73566|-0.45%|1.716|0.000|287301001|40.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e8058e776)|0.73453|0.74490|0.00205|0.28%|0.73725|-0.27%|0.73663|-0.32%|1.680|0.000|287307145|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e8058e776)|0.70686|0.71248|0.00083|0.12%|0.70812|-4.21%|0.70794|-4.20%|1.849|0.000|267645606|47.58 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57917|0.64330|0.00669|1.15%|0.58104|0.00%|0.58010|0.00%|8.619|0.999|1123075297|43.46 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b90ab8119e)|0.58224|0.64714|0.00886|1.52%|0.58459|0.61%|0.58321|0.54%|6.902|0.000|1120817759|43.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e8058e776)|0.58215|0.64713|0.00856|1.46%|0.58485|0.66%|0.58352|0.59%|6.879|0.000|1120982002|43.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e8058e776)|0.51953|0.58141|0.00679|1.30%|0.52143|-10.26%|0.52051|-10.27%|7.940|0.000|866333800|61.44 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42698|0.44362|0.00199|0.46%|0.43135|0.00%|0.43115|0.00%|2.537|0.999|2020733008|26.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b90ab8119e)|0.42625|0.55534|0.02730|6.27%|0.43562|0.99%|0.42864|-0.58%|3.773|0.000|2020744547|27.02 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e8058e776)|0.42425|0.55303|0.02624|6.06%|0.43331|0.45%|0.42657|-1.06%|3.789|0.000|2020744477|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e8058e776)|0.14782|0.15302|0.00117|0.78%|0.14985|-65.26%|0.14984|-65.25%|0.515|0.000|536712446|28.04 MB|
