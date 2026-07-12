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
| Time          |2026-07-12 01:03:23 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29174661279 ([Artifacts](https://github.com/php/php-src/actions/runs/29174661279/artifacts/8254926457))|
| Changeset  |https://github.com/php/php-src/compare/9073875eb9..1fd15d4254|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39835|0.40096|0.00083|0.21%|0.39932|0.00%|0.39889|0.00%|0.642|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9073875eb9)|0.38881|0.39094|0.00040|0.10%|0.38957|-2.44%|0.38947|-2.36%|1.501|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fd15d4254)|0.38929|0.39264|0.00057|0.15%|0.38986|-2.37%|0.38968|-2.31%|3.325|8.614|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fd15d4254)|0.36322|0.36727|0.00099|0.27%|0.36441|-8.74%|0.36395|-8.76%|1.128|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67754|0.67984|0.00052|0.08%|0.67829|0.00%|0.67813|0.00%|1.205|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9073875eb9)|0.66915|0.67076|0.00043|0.06%|0.66975|-1.26%|0.66967|-1.25%|0.701|8.614|0.000|25.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fd15d4254)|0.66918|0.67163|0.00047|0.07%|0.66984|-1.25%|0.66974|-1.24%|2.207|8.614|0.000|25.68 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fd15d4254)|0.64188|0.64446|0.00047|0.07%|0.64298|-5.20%|0.64300|-5.18%|0.210|8.614|0.000|26.17 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59234|0.59645|0.00100|0.17%|0.59422|0.00%|0.59440|0.00%|0.008|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9073875eb9)|0.58920|0.59439|0.00098|0.17%|0.59008|-0.70%|0.58984|-0.77%|3.334|8.290|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fd15d4254)|0.58934|0.59268|0.00068|0.12%|0.59004|-0.70%|0.58986|-0.77%|2.249|8.586|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fd15d4254)|0.52100|0.52489|0.00096|0.18%|0.52209|-12.14%|0.52178|-12.22%|1.917|8.614|0.000|26.27 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44325|0.44763|0.00078|0.17%|0.44473|0.00%|0.44459|0.00%|1.664|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9073875eb9)|0.44920|0.45175|0.00061|0.14%|0.45065|1.33%|0.45070|1.37%|-0.294|-8.614|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fd15d4254)|0.44959|0.45220|0.00064|0.14%|0.45094|1.40%|0.45090|1.42%|-0.087|-8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fd15d4254)|0.14406|0.14565|0.00024|0.17%|0.14458|-67.49%|0.14453|-67.49%|1.863|8.614|0.000|26.27 MB|
