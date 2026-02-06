### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-02-06 00:52:34 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21734469308 ([Artifacts](https://github.com/php/php-src/actions/runs/21734469308/artifacts/5400021815))|
| Changeset  |https://github.com/php/php-src/compare/06dac62747..10fb64fed7|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40262|0.40464|0.00033|0.08%|0.40307|0.00%|0.40298|0.00%|2.568|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/06dac62747)|0.39551|0.39825|0.00059|0.15%|0.39602|-1.75%|0.39579|-1.78%|2.119|8.614|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/10fb64fed7)|0.39822|0.40123|0.00051|0.13%|0.39871|-1.08%|0.39862|-1.08%|3.351|8.614|0.000|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10fb64fed7)|0.37145|0.37350|0.00040|0.11%|0.37199|-7.71%|0.37190|-7.71%|2.357|8.614|0.000|26.98 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68933|0.69144|0.00063|0.09%|0.69013|0.00%|0.68988|0.00%|0.758|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/06dac62747)|0.68735|0.69082|0.00073|0.11%|0.68801|-0.31%|0.68769|-0.32%|1.951|8.111|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/10fb64fed7)|0.68775|0.69222|0.00076|0.11%|0.68859|-0.22%|0.68840|-0.22%|2.632|7.725|0.000|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10fb64fed7)|0.65493|0.65957|0.00076|0.12%|0.65575|-4.98%|0.65564|-4.96%|2.832|8.614|0.000|26.98 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59946|0.60608|0.00131|0.22%|0.60139|0.00%|0.60121|0.00%|1.201|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/06dac62747)|0.59906|0.60309|0.00104|0.17%|0.60011|-0.21%|0.59974|-0.25%|1.621|5.539|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/10fb64fed7)|0.59933|0.60326|0.00061|0.10%|0.60011|-0.21%|0.59998|-0.20%|3.144|5.939|0.000|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10fb64fed7)|0.53054|0.53344|0.00059|0.11%|0.53128|-11.66%|0.53117|-11.65%|2.268|8.614|0.000|26.98 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44148|0.45479|0.00184|0.41%|0.44283|0.00%|0.44245|0.00%|5.871|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/06dac62747)|0.44109|0.44575|0.00087|0.20%|0.44339|0.13%|0.44337|0.21%|-0.018|-4.836|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/10fb64fed7)|0.44219|0.44553|0.00079|0.18%|0.44375|0.21%|0.44386|0.32%|0.080|-6.298|0.000|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10fb64fed7)|0.14325|0.14413|0.00021|0.14%|0.14371|-67.55%|0.14371|-67.52%|0.008|8.614|0.000|26.98 MB|
