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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-03-02 00:49:37 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43773|0.45207|0.00247|0.43893|0.00%|0.43850|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|0.43679|0.43911|0.00052|0.43764|-0.29%|0.43753|-0.22%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|0.43638|0.43869|0.00053|0.43742|-0.35%|0.43741|-0.25%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.42489|0.42614|0.00031|0.42543|-3.08%|0.42540|-2.99%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70846|0.71463|0.00105|0.71277|0.00%|0.71286|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|0.70727|0.71029|0.00073|0.70843|-0.61%|0.70830|-0.64%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|0.70701|0.71460|0.00140|0.70836|-0.62%|0.70807|-0.67%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.68033|0.68349|0.00073|0.68165|-4.37%|0.68157|-4.39%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58100|0.58319|0.00063|0.58191|0.00%|0.58180|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|0.57625|0.57880|0.00058|0.57778|-0.71%|0.57783|-0.68%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|0.57577|0.57957|0.00080|0.57750|-0.76%|0.57744|-0.75%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.52033|0.52181|0.00035|0.52109|-10.45%|0.52111|-10.43%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21503|0.22034|0.00118|0.21620|0.00%|0.21584|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|0.25811|0.28316|0.00726|0.26968|24.74%|0.26853|24.41%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|0.21544|0.21933|0.00101|0.21740|0.55%|0.21744|0.74%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.07468|0.07773|0.00082|0.07597|-64.86%|0.07569|-64.93%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33581|1.36645|0.00690|1.34879|0.00%|1.34776|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|1.36333|1.38488|0.00543|1.37232|1.74%|1.37201|1.80%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|1.36027|1.38584|0.00567|1.37252|1.76%|1.37153|1.76%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.53861|0.56698|0.00669|0.55094|-59.15%|0.55026|-59.17%|21.79 MB|
