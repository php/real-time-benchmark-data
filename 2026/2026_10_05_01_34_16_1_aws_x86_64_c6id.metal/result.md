### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-10-05 01:34:16 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/37250913540 ([Artifacts](https://github.com/php/php-src/actions/runs/37250913540/artifacts/11322291377))|
| Changeset  |https://github.com/php/php-src/compare/63b0af4a5c..d6288f77eb|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39906|0.40092|0.00028|0.07%|0.39955|0.00%|0.39954|0.00%|2.560|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/63b0af4a5c)|0.38008|0.38106|0.00020|0.05%|0.38047|-4.77%|0.38044|-4.78%|0.872|8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6288f77eb)|0.37946|0.38210|0.00045|0.12%|0.37983|-4.93%|0.37971|-4.96%|3.245|8.614|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6288f77eb)|0.35540|0.35657|0.00030|0.08%|0.35590|-10.92%|0.35585|-10.93%|0.504|8.614|0.000|26.32 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68006|0.68448|0.00088|0.13%|0.68213|0.00%|0.68204|0.00%|0.219|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/63b0af4a5c)|0.67536|0.68125|0.00102|0.15%|0.67649|-0.83%|0.67630|-0.84%|2.507|8.559|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6288f77eb)|0.67555|0.68110|0.00096|0.14%|0.67666|-0.80%|0.67650|-0.81%|2.656|8.579|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6288f77eb)|0.64501|0.65579|0.00158|0.24%|0.64602|-5.29%|0.64561|-5.34%|5.124|8.614|0.000|26.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59123|0.59604|0.00093|0.16%|0.59265|0.00%|0.59254|0.00%|1.264|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/63b0af4a5c)|0.59569|0.59962|0.00085|0.14%|0.59671|0.69%|0.59643|0.66%|1.450|-8.531|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6288f77eb)|0.59516|0.59893|0.00081|0.14%|0.59616|0.59%|0.59600|0.58%|1.733|-8.435|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6288f77eb)|0.52020|0.53154|0.00162|0.31%|0.52160|-11.99%|0.52130|-12.02%|5.026|8.614|0.000|26.61 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44334|0.45068|0.00100|0.22%|0.44476|0.00%|0.44464|0.00%|4.320|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/63b0af4a5c)|0.45023|0.45419|0.00076|0.17%|0.45212|1.65%|0.45215|1.69%|0.308|-8.607|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6288f77eb)|0.45268|0.45686|0.00092|0.20%|0.45466|2.23%|0.45484|2.29%|0.265|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6288f77eb)|0.14369|0.14482|0.00026|0.18%|0.14434|-67.55%|0.14436|-67.53%|-0.103|8.614|0.000|26.61 MB|
