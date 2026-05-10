### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-05-10 01:19:43 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25616414559 ([Artifacts](https://github.com/php/php-src/actions/runs/25616414559/artifacts/6900244571))|
| Changeset  |https://github.com/php/php-src/compare/eedda2a03c..fe52e5b64b|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39251|0.39967|0.00091|0.23%|0.39818|0.00%|0.39822|0.00%|-4.916|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eedda2a03c)|0.38711|0.39345|0.00072|0.18%|0.39131|-1.73%|0.39132|-1.73%|-3.586|8.607|0.000|25.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe52e5b64b)|0.39139|0.39355|0.00046|0.12%|0.39183|-1.59%|0.39169|-1.64%|2.061|8.572|0.000|25.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe52e5b64b)|0.36372|0.36646|0.00060|0.17%|0.36454|-8.45%|0.36436|-8.50%|1.603|8.614|0.000|25.53 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66232|0.68163|0.00230|0.34%|0.67750|0.00%|0.67759|0.00%|-5.986|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eedda2a03c)|0.66898|0.67121|0.00040|0.06%|0.66977|-1.14%|0.66968|-1.17%|1.258|8.269|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe52e5b64b)|0.67135|0.67368|0.00045|0.07%|0.67185|-0.83%|0.67173|-0.86%|2.112|8.269|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe52e5b64b)|0.63917|0.71544|0.01163|1.81%|0.64260|-5.15%|0.63959|-5.61%|5.409|8.262|0.000|25.40 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59577|0.60007|0.00104|0.17%|0.59717|0.00%|0.59692|0.00%|0.974|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eedda2a03c)|0.58453|0.59497|0.00167|0.28%|0.59305|-0.69%|0.59324|-0.62%|-4.180|8.614|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe52e5b64b)|0.59204|0.59545|0.00080|0.13%|0.59301|-0.70%|0.59278|-0.69%|1.610|8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe52e5b64b)|0.51726|0.52722|0.00126|0.24%|0.52472|-12.13%|0.52466|-12.10%|-3.996|8.614|0.000|25.41 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44179|0.44938|0.00107|0.24%|0.44316|0.00%|0.44303|0.00%|4.199|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eedda2a03c)|0.44577|0.44783|0.00049|0.11%|0.44684|0.83%|0.44684|0.86%|-0.074|-8.269|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe52e5b64b)|0.44570|0.44980|0.00065|0.15%|0.44689|0.84%|0.44682|0.86%|1.735|-8.276|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe52e5b64b)|0.14383|0.14575|0.00046|0.32%|0.14428|-67.44%|0.14416|-67.46%|2.161|8.614|0.000|25.41 MB|
