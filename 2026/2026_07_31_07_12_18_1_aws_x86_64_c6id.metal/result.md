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
| Time          |2026-07-31 07:12:18 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/30595254458 ([Artifacts](https://github.com/php/php-src/actions/runs/30595254458/artifacts/8786977480))|
| Changeset  |https://github.com/php/php-src/compare/c5cdea5ada..7b78eb4fcc|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40015|0.40279|0.00054|0.13%|0.40070|0.00%|0.40055|0.00%|2.863|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5cdea5ada)|0.39020|0.39157|0.00026|0.07%|0.39060|-2.52%|0.39055|-2.50%|1.911|8.614|0.000|25.66 MB|
|[PHP - master](https://github.com/php/php-src/commit/7b78eb4fcc)|0.39064|0.39250|0.00039|0.10%|0.39097|-2.43%|0.39084|-2.42%|2.644|8.614|0.000|25.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7b78eb4fcc)|0.36389|0.36703|0.00057|0.16%|0.36450|-9.03%|0.36430|-9.05%|2.627|8.614|0.000|26.21 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68078|0.68450|0.00082|0.12%|0.68214|0.00%|0.68206|0.00%|0.533|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5cdea5ada)|0.67418|0.67703|0.00065|0.10%|0.67501|-1.05%|0.67484|-1.06%|1.454|8.614|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/7b78eb4fcc)|0.67660|0.67916|0.00043|0.06%|0.67737|-0.70%|0.67728|-0.70%|2.038|8.614|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7b78eb4fcc)|0.64265|0.66804|0.00412|0.64%|0.64417|-5.57%|0.64307|-5.72%|4.798|8.614|0.000|26.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59227|0.59693|0.00108|0.18%|0.59421|0.00%|0.59406|0.00%|0.367|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5cdea5ada)|0.58725|0.59041|0.00075|0.13%|0.58814|-1.02%|0.58799|-1.02%|1.813|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/7b78eb4fcc)|0.58751|0.59185|0.00101|0.17%|0.58854|-0.95%|0.58817|-0.99%|1.656|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7b78eb4fcc)|0.51940|0.52303|0.00078|0.15%|0.52039|-12.42%|0.52012|-12.45%|1.854|8.614|0.000|26.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44373|0.44577|0.00048|0.11%|0.44467|0.00%|0.44461|0.00%|0.556|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5cdea5ada)|0.44887|0.45019|0.00027|0.06%|0.44954|1.10%|0.44955|1.11%|-0.064|-8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/7b78eb4fcc)|0.44824|0.45062|0.00041|0.09%|0.44958|1.11%|0.44954|1.11%|-0.168|-8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7b78eb4fcc)|0.14438|0.14502|0.00016|0.11%|0.14466|-67.47%|0.14464|-67.47%|0.209|8.614|0.000|26.21 MB|
