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
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250115|
| GCC           |11.4.1|
| Time          |2025-01-21 00:49:18 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43835|0.45098|0.00169|0.43954|0.00%|0.43924|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.43831|0.44597|0.00110|0.43928|-0.06%|0.43910|-0.03%|41.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/0f8340d0a5)|0.43882|0.44613|0.00115|0.43991|0.08%|0.43966|0.09%|41.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0f8340d0a5)|0.42529|0.42731|0.00043|0.42628|-3.02%|0.42625|-2.96%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71291|0.71639|0.00078|0.71440|0.00%|0.71444|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.71070|0.71378|0.00069|0.71185|-0.36%|0.71180|-0.37%|37.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/0f8340d0a5)|0.71025|0.71345|0.00068|0.71120|-0.45%|0.71100|-0.48%|37.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0f8340d0a5)|0.68175|0.68406|0.00057|0.68277|-4.43%|0.68277|-4.43%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58105|0.58398|0.00059|0.58206|0.00%|0.58197|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.57861|0.58952|0.00159|0.57982|-0.39%|0.57944|-0.43%|42.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/0f8340d0a5)|0.57436|0.58078|0.00173|0.57837|-0.63%|0.57887|-0.53%|42.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0f8340d0a5)|0.51919|0.52497|0.00082|0.52027|-10.62%|0.52024|-10.61%|61.98 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21444|0.22004|0.00104|0.21635|0.00%|0.21619|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.21458|0.22086|0.00131|0.21704|0.32%|0.21692|0.34%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/0f8340d0a5)|0.21444|0.21860|0.00083|0.21608|-0.13%|0.21593|-0.12%|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0f8340d0a5)|0.07459|0.07710|0.00065|0.07573|-65.00%|0.07581|-64.93%|27.31 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34114|1.37885|0.00667|1.35526|0.00%|1.35432|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6bd2b8dfa5)|1.26264|1.28422|0.00476|1.27733|-5.75%|1.27776|-5.65%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/0f8340d0a5)|1.26837|1.28783|0.00439|1.27837|-5.67%|1.27905|-5.56%|20.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0f8340d0a5)|0.54545|0.57741|0.00595|0.56088|-58.62%|0.56030|-58.63%|21.73 MB|
