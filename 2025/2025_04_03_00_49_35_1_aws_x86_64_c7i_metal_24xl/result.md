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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-03 00:49:35 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43831|0.44030|0.00048|0.43920|0.00%|0.43911|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/011795bcbe)|0.43602|0.43794|0.00051|0.43699|-0.50%|0.43691|-0.50%|41.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/f4954df0c9)|0.43875|0.44114|0.00050|0.43971|0.11%|0.43958|0.11%|41.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f4954df0c9)|0.42673|0.42862|0.00036|0.42768|-2.62%|0.42768|-2.60%|50.88 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71304|0.71645|0.00084|0.71432|0.00%|0.71402|0.00%|37.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/011795bcbe)|0.70756|0.71048|0.00076|0.70872|-0.78%|0.70857|-0.76%|37.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/f4954df0c9)|0.70942|0.71219|0.00056|0.71065|-0.51%|0.71065|-0.47%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f4954df0c9)|0.68000|0.68298|0.00069|0.68119|-4.64%|0.68119|-4.60%|44.73 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58128|0.58349|0.00061|0.58229|0.00%|0.58233|0.00%|43.07 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/011795bcbe)|0.58068|0.58250|0.00049|0.58149|-0.14%|0.58145|-0.15%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/f4954df0c9)|0.57944|0.58221|0.00055|0.58045|-0.32%|0.58042|-0.33%|43.04 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f4954df0c9)|0.52033|0.52502|0.00076|0.52335|-10.12%|0.52329|-10.14%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21547|0.21955|0.00088|0.21692|0.00%|0.21695|0.00%|26.23 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/011795bcbe)|0.21765|0.22201|0.00118|0.21971|1.29%|0.21948|1.17%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/f4954df0c9)|0.21576|0.21923|0.00074|0.21686|-0.03%|0.21676|-0.09%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f4954df0c9)|0.07510|0.07791|0.00080|0.07638|-64.79%|0.07631|-64.83%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34956|1.37611|0.00564|1.35569|0.00%|1.35453|0.00%|20.49 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/011795bcbe)|1.31376|1.32938|0.00477|1.32070|-2.58%|1.32003|-2.55%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/f4954df0c9)|1.24820|1.26624|0.00479|1.25696|-7.28%|1.25629|-7.25%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f4954df0c9)|0.53470|0.55329|0.00442|0.54695|-59.66%|0.54701|-59.62%|21.83 MB|
