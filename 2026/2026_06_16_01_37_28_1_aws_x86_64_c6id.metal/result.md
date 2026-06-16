### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-06-16 01:37:28 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27588152166 ([Artifacts](https://github.com/php/php-src/actions/runs/27588152166/artifacts/7656013143))|
| Changeset  |https://github.com/php/php-src/compare/92128ac93f..dee1317c33|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39644|0.39839|0.00030|0.08%|0.39677|0.00%|0.39678|0.00%|3.251|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92128ac93f)|0.38772|0.38922|0.00029|0.08%|0.38821|-2.16%|0.38817|-2.17%|1.640|8.614|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/dee1317c33)|0.38889|0.39060|0.00038|0.10%|0.38941|-1.86%|0.38929|-1.89%|1.507|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dee1317c33)|0.36194|0.36413|0.00042|0.12%|0.36265|-8.60%|0.36255|-8.63%|1.275|8.614|0.000|25.79 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67475|0.68195|0.00115|0.17%|0.67577|0.00%|0.67547|0.00%|3.721|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92128ac93f)|0.67635|0.68396|0.00120|0.18%|0.67829|0.37%|0.67809|0.39%|2.394|-7.862|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/dee1317c33)|0.66685|0.67202|0.00091|0.14%|0.66775|-1.19%|0.66748|-1.18%|3.065|8.614|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dee1317c33)|0.63995|0.64425|0.00105|0.16%|0.64127|-5.10%|0.64113|-5.08%|0.963|8.614|0.000|26.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59028|0.59432|0.00101|0.17%|0.59216|0.00%|0.59198|0.00%|0.125|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92128ac93f)|0.58663|0.59038|0.00073|0.12%|0.58725|-0.83%|0.58709|-0.83%|3.001|8.607|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/dee1317c33)|0.58775|0.59107|0.00082|0.14%|0.58845|-0.63%|0.58820|-0.64%|2.254|8.428|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dee1317c33)|0.52020|0.52395|0.00082|0.16%|0.52102|-12.02%|0.52079|-12.03%|1.947|8.614|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44311|0.44883|0.00083|0.19%|0.44446|0.00%|0.44440|0.00%|3.030|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92128ac93f)|0.44894|0.45210|0.00065|0.15%|0.44991|1.23%|0.44977|1.21%|1.018|-8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/dee1317c33)|0.44873|0.45292|0.00068|0.15%|0.44984|1.21%|0.44978|1.21%|2.055|-8.607|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dee1317c33)|0.14423|0.14574|0.00025|0.17%|0.14471|-67.44%|0.14473|-67.43%|1.312|8.614|0.000|26.25 MB|
