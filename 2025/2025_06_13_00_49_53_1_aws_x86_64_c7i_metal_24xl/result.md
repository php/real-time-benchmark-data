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
| Kernel        |6.1.140-154.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250609|
| GCC           |11.5.0|
| Time          |2025-06-13 00:49:53 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44006|0.44953|0.00185|0.44153|0.00%|0.44108|0.00%|41.89 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|0.43928|0.44209|0.00067|0.44056|-0.22%|0.44045|-0.14%|42.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/5740038026)|0.43701|0.44003|0.00064|0.43808|-0.78%|0.43806|-0.68%|42.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5740038026)|0.42254|0.42429|0.00037|0.42315|-4.16%|0.42312|-4.07%|51.33 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71464|0.73136|0.00286|0.71632|0.00%|0.71585|0.00%|37.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|0.71099|0.71473|0.00096|0.71240|-0.55%|0.71250|-0.47%|38.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/5740038026)|0.70846|0.71213|0.00096|0.70992|-0.89%|0.70979|-0.85%|38.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5740038026)|0.67637|0.67897|0.00070|0.67786|-5.37%|0.67778|-5.32%|45.01 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58161|0.59134|0.00167|0.58291|0.00%|0.58264|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|0.57953|0.58188|0.00058|0.58066|-0.38%|0.58068|-0.34%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/5740038026)|0.57941|0.58135|0.00057|0.58012|-0.48%|0.58002|-0.45%|43.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5740038026)|0.52362|0.52597|0.00051|0.52453|-10.02%|0.52451|-9.98%|61.32 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21515|0.21961|0.00105|0.21637|0.00%|0.21610|0.00%|26.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|0.21619|0.21889|0.00074|0.21743|0.49%|0.21721|0.51%|26.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/5740038026)|0.21720|0.22122|0.00113|0.21908|1.25%|0.21875|1.23%|26.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5740038026)|0.07546|0.07859|0.00084|0.07662|-64.59%|0.07651|-64.59%|27.79 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34371|1.36787|0.00622|1.35472|0.00%|1.35454|0.00%|20.53 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|1.31728|1.33795|0.00465|1.32684|-2.06%|1.32645|-2.07%|20.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/5740038026)|1.27678|1.29269|0.00402|1.28491|-5.15%|1.28556|-5.09%|20.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5740038026)|0.56065|0.58008|0.00551|0.57066|-57.88%|0.57215|-57.76%|22.24 MB|
