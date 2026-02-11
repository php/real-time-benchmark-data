### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-02-11 01:01:12 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21888570992 ([Artifacts](https://github.com/php/php-src/actions/runs/21888570992/artifacts/5458964459))|
| Changeset  |https://github.com/php/php-src/compare/a760cf73f0..defc0bec2e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39949|0.40131|0.00028|0.07%|0.39996|0.00%|0.39991|0.00%|3.000|0.000|1.000|26.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a760cf73f0)|0.39566|0.39716|0.00036|0.09%|0.39607|-0.97%|0.39599|-0.98%|1.821|8.614|0.000|25.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/defc0bec2e)|0.39539|0.39789|0.00045|0.11%|0.39603|-0.98%|0.39592|-1.00%|2.337|8.614|0.000|25.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/defc0bec2e)|0.36921|0.37152|0.00043|0.12%|0.37000|-7.49%|0.36995|-7.49%|1.734|8.614|0.000|25.59 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68153|0.68491|0.00066|0.10%|0.68212|0.00%|0.68190|0.00%|2.616|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a760cf73f0)|0.68172|0.68406|0.00040|0.06%|0.68222|0.01%|0.68215|0.04%|2.303|-3.168|0.002|25.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/defc0bec2e)|0.68159|0.68546|0.00057|0.08%|0.68206|-0.01%|0.68197|0.01%|4.568|-0.452|0.652|25.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/defc0bec2e)|0.64873|0.65028|0.00034|0.05%|0.64925|-4.82%|0.64921|-4.79%|1.191|8.614|0.000|25.67 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59171|0.59603|0.00105|0.18%|0.59346|0.00%|0.59344|0.00%|0.382|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a760cf73f0)|0.59235|0.59702|0.00110|0.19%|0.59351|0.01%|0.59318|-0.04%|2.357|0.465|0.642|25.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/defc0bec2e)|0.59195|0.60331|0.00218|0.37%|0.59328|-0.03%|0.59269|-0.13%|4.125|2.844|0.004|25.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/defc0bec2e)|0.52221|0.53180|0.00132|0.25%|0.52340|-11.81%|0.52314|-11.85%|5.489|8.614|0.000|25.77 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44079|0.44407|0.00061|0.14%|0.44241|0.00%|0.44245|0.00%|0.008|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a760cf73f0)|0.44387|0.44651|0.00065|0.15%|0.44501|0.59%|0.44492|0.56%|0.318|-8.593|0.000|25.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/defc0bec2e)|0.44374|0.44702|0.00071|0.16%|0.44503|0.59%|0.44499|0.57%|0.805|-8.593|0.000|25.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/defc0bec2e)|0.14314|0.14411|0.00021|0.15%|0.14354|-67.56%|0.14352|-67.56%|0.300|8.614|0.000|25.77 MB|
