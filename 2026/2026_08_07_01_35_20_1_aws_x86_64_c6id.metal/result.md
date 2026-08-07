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
| Time          |2026-08-07 01:35:20 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/31138456596 ([Artifacts](https://github.com/php/php-src/actions/runs/31138456596/artifacts/8979858619))|
| Changeset  |https://github.com/php/php-src/compare/ac37a9760b..bf2ba7a800|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39722|0.39805|0.00017|0.04%|0.39754|0.00%|0.39753|0.00%|1.031|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac37a9760b)|0.38720|0.38825|0.00028|0.07%|0.38758|-2.51%|0.38751|-2.52%|1.097|8.614|0.000|25.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf2ba7a800)|0.38746|0.38905|0.00033|0.08%|0.38788|-2.43%|0.38779|-2.45%|1.747|8.614|0.000|25.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf2ba7a800)|0.36073|0.36260|0.00037|0.10%|0.36126|-9.12%|0.36115|-9.15%|1.388|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67596|0.67948|0.00091|0.13%|0.67738|0.00%|0.67731|0.00%|0.637|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac37a9760b)|0.67452|0.67680|0.00052|0.08%|0.67511|-0.33%|0.67502|-0.34%|1.892|8.283|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf2ba7a800)|0.67259|0.67531|0.00054|0.08%|0.67360|-0.56%|0.67349|-0.56%|1.010|8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf2ba7a800)|0.64565|0.65996|0.00225|0.35%|0.64683|-4.51%|0.64627|-4.58%|4.690|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58937|0.59527|0.00126|0.21%|0.59214|0.00%|0.59190|0.00%|0.484|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac37a9760b)|0.58818|0.59282|0.00083|0.14%|0.58932|-0.48%|0.58925|-0.45%|1.643|8.145|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf2ba7a800)|0.58774|0.59589|0.00113|0.19%|0.58861|-0.60%|0.58840|-0.59%|5.726|8.262|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf2ba7a800)|0.51711|0.52090|0.00074|0.14%|0.51826|-12.48%|0.51803|-12.48%|2.110|8.614|0.000|26.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44329|0.44720|0.00064|0.14%|0.44461|0.00%|0.44459|0.00%|1.063|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac37a9760b)|0.44938|0.45356|0.00075|0.17%|0.45056|1.34%|0.45056|1.34%|1.332|-8.614|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf2ba7a800)|0.44906|0.45398|0.00086|0.19%|0.45032|1.29%|0.45030|1.29%|2.387|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf2ba7a800)|0.14446|0.14518|0.00019|0.13%|0.14481|-67.43%|0.14481|-67.43%|0.066|8.614|0.000|26.33 MB|
