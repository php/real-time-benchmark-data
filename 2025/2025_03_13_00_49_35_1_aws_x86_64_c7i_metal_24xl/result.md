### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.129-138.220.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250303|
| GCC           |11.4.1|
| Time          |2025-03-13 00:49:35 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43911|0.44849|0.00202|0.44042|0.00%|0.43998|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/645cd6a5ad)|0.43660|0.43893|0.00060|0.43742|-0.68%|0.43731|-0.61%|41.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/7faa3decd9)|0.43617|0.43867|0.00060|0.43704|-0.77%|0.43691|-0.70%|41.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7faa3decd9)|0.42577|0.42758|0.00038|0.42661|-3.14%|0.42657|-3.05%|50.81 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70797|0.71541|0.00125|0.71398|0.00%|0.71411|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/645cd6a5ad)|0.70378|0.70632|0.00067|0.70481|-1.28%|0.70477|-1.31%|37.56 MB|
|[PHP - master](https://github.com/php/php-src/commit/7faa3decd9)|0.70380|0.70659|0.00064|0.70528|-1.22%|0.70518|-1.25%|37.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7faa3decd9)|0.67588|0.68039|0.00082|0.67755|-5.10%|0.67754|-5.12%|44.57 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58075|0.58338|0.00061|0.58210|0.00%|0.58204|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/645cd6a5ad)|0.57769|0.58150|0.00070|0.57892|-0.55%|0.57873|-0.57%|42.95 MB|
|[PHP - master](https://github.com/php/php-src/commit/7faa3decd9)|0.57933|0.64545|0.02634|0.59535|2.28%|0.58099|-0.18%|42.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7faa3decd9)|0.51984|0.52253|0.00064|0.52151|-10.41%|0.52155|-10.39%|61.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21412|0.21797|0.00084|0.21587|0.00%|0.21567|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/645cd6a5ad)|0.21658|0.22007|0.00086|0.21773|0.86%|0.21744|0.82%|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/7faa3decd9)|0.21628|0.21976|0.00095|0.21756|0.78%|0.21721|0.71%|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7faa3decd9)|0.07520|0.07759|0.00066|0.07626|-64.67%|0.07603|-64.75%|27.39 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.49021|1.51176|0.00520|1.49868|0.00%|1.49798|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/645cd6a5ad)|1.27201|1.28538|0.00345|1.27865|-14.68%|1.27927|-14.60%|20.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/7faa3decd9)|1.31540|1.32976|0.00409|1.32256|-11.75%|1.32301|-11.68%|20.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7faa3decd9)|0.54234|0.56619|0.00538|0.55067|-63.26%|0.55039|-63.26%|21.81 MB|
