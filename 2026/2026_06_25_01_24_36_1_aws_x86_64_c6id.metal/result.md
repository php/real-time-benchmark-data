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
| Time          |2026-06-25 01:24:36 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28140590959 ([Artifacts](https://github.com/php/php-src/actions/runs/28140590959/artifacts/7867229741))|
| Changeset  |https://github.com/php/php-src/compare/6f0aa11d23..5cd9a3b047|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39978|0.40064|0.00020|0.05%|0.40022|0.00%|0.40020|0.00%|0.193|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f0aa11d23)|0.39243|0.39374|0.00025|0.06%|0.39307|-1.79%|0.39304|-1.79%|0.377|8.614|0.000|25.72 MB|
|[PHP - master](https://github.com/php/php-src/commit/5cd9a3b047)|0.39216|0.39353|0.00032|0.08%|0.39266|-1.89%|0.39261|-1.90%|1.166|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5cd9a3b047)|0.36621|0.36855|0.00042|0.11%|0.36669|-8.38%|0.36659|-8.40%|2.322|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67949|0.68453|0.00080|0.12%|0.68040|0.00%|0.68027|0.00%|3.011|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f0aa11d23)|0.67288|0.67603|0.00067|0.10%|0.67383|-0.97%|0.67372|-0.96%|1.065|8.614|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/5cd9a3b047)|0.67080|0.67493|0.00070|0.10%|0.67159|-1.29%|0.67138|-1.31%|2.747|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5cd9a3b047)|0.64144|0.64350|0.00046|0.07%|0.64206|-5.63%|0.64193|-5.64%|1.277|8.614|0.000|25.82 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58900|0.59763|0.00134|0.23%|0.59523|0.00%|0.59537|0.00%|-1.910|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f0aa11d23)|0.59019|0.59900|0.00142|0.24%|0.59140|-0.64%|0.59100|-0.73%|3.470|7.876|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/5cd9a3b047)|0.58931|0.59238|0.00062|0.10%|0.59018|-0.85%|0.58998|-0.90%|1.483|8.269|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5cd9a3b047)|0.52092|0.52445|0.00062|0.12%|0.52183|-12.33%|0.52177|-12.36%|1.772|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44346|0.44613|0.00053|0.12%|0.44466|0.00%|0.44468|0.00%|0.201|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f0aa11d23)|0.44886|0.45192|0.00065|0.14%|0.45029|1.27%|0.45039|1.28%|-0.368|-8.614|0.000|25.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/5cd9a3b047)|0.44954|0.45218|0.00060|0.13%|0.45083|1.39%|0.45082|1.38%|0.183|-8.614|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5cd9a3b047)|0.14436|0.14522|0.00020|0.14%|0.14479|-67.44%|0.14481|-67.44%|-0.109|8.614|0.000|26.29 MB|
