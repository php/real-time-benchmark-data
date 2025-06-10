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
| Time          |2025-06-10 00:49:48 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43943|0.45281|0.00277|0.44102|0.00%|0.44025|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3cfa4bcae)|0.44060|0.44251|0.00046|0.44118|0.04%|0.44105|0.18%|42.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/32c6ac9133)|0.43947|0.44141|0.00040|0.44017|-0.19%|0.44014|-0.02%|42.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32c6ac9133)|0.42387|0.42533|0.00031|0.42452|-3.74%|0.42443|-3.59%|51.18 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71372|0.71928|0.00123|0.71526|0.00%|0.71498|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3cfa4bcae)|0.70836|0.71192|0.00089|0.70977|-0.77%|0.70953|-0.76%|37.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/32c6ac9133)|0.71033|0.71357|0.00081|0.71171|-0.50%|0.71167|-0.46%|37.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32c6ac9133)|0.68239|0.68562|0.00063|0.68344|-4.45%|0.68341|-4.42%|44.94 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58128|0.58384|0.00054|0.58204|0.00%|0.58199|0.00%|43.09 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3cfa4bcae)|0.58209|0.58403|0.00057|0.58299|0.16%|0.58289|0.15%|43.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/32c6ac9133)|0.58193|0.58359|0.00045|0.58262|0.10%|0.58253|0.09%|43.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32c6ac9133)|0.52451|0.52639|0.00043|0.52527|-9.75%|0.52512|-9.77%|60.97 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21589|0.21988|0.00101|0.21734|0.00%|0.21722|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3cfa4bcae)|0.21096|0.21489|0.00089|0.21289|-2.05%|0.21287|-2.00%|26.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/32c6ac9133)|0.21673|0.21990|0.00078|0.21787|0.24%|0.21767|0.20%|26.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32c6ac9133)|0.07582|0.07923|0.00092|0.07728|-64.44%|0.07701|-64.55%|27.70 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34137|1.35752|0.00437|1.34937|0.00%|1.34945|0.00%|20.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3cfa4bcae)|1.28838|1.30895|0.00517|1.29842|-3.78%|1.29747|-3.85%|20.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/32c6ac9133)|1.28957|1.30633|0.00382|1.30049|-3.62%|1.30094|-3.60%|20.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32c6ac9133)|0.54837|0.56393|0.00352|0.55624|-58.78%|0.55653|-58.76%|22.11 MB|
