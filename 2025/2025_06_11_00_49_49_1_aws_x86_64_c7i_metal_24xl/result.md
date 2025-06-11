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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250527|
| GCC           |11.5.0|
| Time          |2025-06-11 00:49:49 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43902|0.45087|0.00261|0.44064|0.00%|0.44000|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32c6ac9133)|0.43921|0.44104|0.00045|0.43983|-0.18%|0.43976|-0.05%|42.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|0.43949|0.44301|0.00067|0.44030|-0.08%|0.44022|0.05%|42.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.42428|0.42649|0.00043|0.42517|-3.51%|0.42517|-3.37%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71372|0.71817|0.00109|0.71573|0.00%|0.71567|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32c6ac9133)|0.71121|0.71609|0.00105|0.71344|-0.32%|0.71350|-0.30%|37.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|0.71133|0.72449|0.00225|0.71325|-0.35%|0.71280|-0.40%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.67992|0.68422|0.00088|0.68221|-4.68%|0.68214|-4.69%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58282|0.58501|0.00054|0.58364|0.00%|0.58361|0.00%|43.09 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32c6ac9133)|0.58283|0.58554|0.00071|0.58401|0.06%|0.58381|0.03%|43.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|0.58253|0.58480|0.00050|0.58375|0.02%|0.58372|0.02%|43.59 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.52649|0.52862|0.00056|0.52772|-9.58%|0.52777|-9.57%|61.29 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21573|0.21893|0.00078|0.21730|0.00%|0.21739|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32c6ac9133)|0.21667|0.22027|0.00082|0.21828|0.45%|0.21830|0.42%|26.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|0.21584|0.21779|0.00055|0.21690|-0.18%|0.21697|-0.19%|26.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.07631|0.07924|0.00090|0.07768|-64.25%|0.07779|-64.22%|27.77 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34216|1.35757|0.00422|1.35023|0.00%|1.35015|0.00%|20.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32c6ac9133)|1.28493|1.30037|0.00422|1.29357|-4.20%|1.29435|-4.13%|20.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|1.31255|1.33293|0.00461|1.32167|-2.12%|1.32171|-2.11%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.55247|0.57055|0.00438|0.56192|-58.38%|0.56201|-58.37%|22.23 MB|
