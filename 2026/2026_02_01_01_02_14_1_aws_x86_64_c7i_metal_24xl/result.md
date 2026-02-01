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
| Time          |2026-02-01 01:02:14 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21553877091 ([Artifacts](https://github.com/php/php-src/actions/runs/21553877091/artifacts/5331568009))|
| Changeset  |https://github.com/php/php-src/compare/927b9eecb6..6173a9a109|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45046|0.45809|0.00103|0.23%|0.45132|0.00%|0.45111|0.00%|5.898|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/927b9eecb6)|0.44681|0.45400|0.00130|0.29%|0.44802|-0.73%|0.44766|-0.76%|3.409|11.233|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/6173a9a109)|0.44595|0.45260|0.00108|0.24%|0.44685|-0.99%|0.44653|-1.02%|3.589|11.742|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6173a9a109)|0.42624|0.43266|0.00092|0.21%|0.42686|-5.42%|0.42671|-5.41%|5.342|12.216|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 250 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.73451|0.73930|0.00061|0.08%|0.73581|0.00%|0.73574|0.00%|2.441|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/927b9eecb6)|0.73257|0.73554|0.00063|0.09%|0.73351|-0.31%|0.73336|-0.32%|1.169|12.072|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/6173a9a109)|0.73261|0.73848|0.00090|0.12%|0.73391|-0.26%|0.73369|-0.28%|2.292|10.882|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6173a9a109)|0.73643|0.74010|0.00079|0.11%|0.73752|0.23%|0.73729|0.21%|1.499|-11.549|0.000|27.01 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.64603|0.65174|0.00067|0.10%|0.64697|0.00%|0.64687|0.00%|3.940|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/927b9eecb6)|0.64865|0.66919|0.00230|0.35%|0.65017|0.50%|0.64964|0.43%|6.119|-11.993|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/6173a9a109)|0.64916|0.66882|0.00333|0.51%|0.65067|0.57%|0.64991|0.47%|4.955|-11.988|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6173a9a109)|0.57999|0.58492|0.00071|0.12%|0.58077|-10.23%|0.58072|-10.23%|4.185|12.216|0.000|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42780|0.46178|0.00465|1.08%|0.43092|0.00%|0.43010|0.00%|5.706|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/927b9eecb6)|0.42330|0.42997|0.00143|0.34%|0.42602|-1.14%|0.42585|-0.99%|0.655|11.664|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/6173a9a109)|0.42138|0.42855|0.00141|0.33%|0.42533|-1.30%|0.42529|-1.12%|0.157|12.125|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6173a9a109)|0.13736|0.14420|0.00139|0.98%|0.14100|-67.28%|0.14107|-67.20%|0.053|12.216|0.000|27.01 MB|
