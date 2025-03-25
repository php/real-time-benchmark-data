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
| Time          |2025-03-25 00:49:38 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43893|0.45402|0.00262|0.44014|0.00%|0.43960|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/345d229385)|0.43716|0.43898|0.00038|0.43789|-0.51%|0.43784|-0.40%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/fec4f7f389)|0.43758|0.44110|0.00067|0.43845|-0.38%|0.43842|-0.27%|41.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fec4f7f389)|0.42756|0.43031|0.00052|0.42857|-2.63%|0.42842|-2.54%|50.81 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71459|0.71721|0.00061|0.71540|0.00%|0.71535|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/345d229385)|0.70896|0.71221|0.00073|0.70993|-0.76%|0.70982|-0.77%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/fec4f7f389)|0.70959|0.71261|0.00079|0.71100|-0.62%|0.71091|-0.62%|37.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fec4f7f389)|0.68177|0.68537|0.00088|0.68310|-4.52%|0.68286|-4.54%|44.57 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58155|0.58300|0.00039|0.58239|0.00%|0.58245|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/345d229385)|0.57834|0.58117|0.00059|0.57925|-0.54%|0.57917|-0.56%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/fec4f7f389)|0.57694|0.58074|0.00094|0.57874|-0.63%|0.57896|-0.60%|43.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fec4f7f389)|0.51934|0.52282|0.00069|0.52128|-10.49%|0.52137|-10.49%|61.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21490|0.21832|0.00085|0.21609|0.00%|0.21591|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/345d229385)|0.21651|0.22040|0.00102|0.21818|0.97%|0.21836|1.14%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/fec4f7f389)|0.21745|0.21987|0.00055|0.21850|1.12%|0.21855|1.23%|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fec4f7f389)|0.07517|0.07758|0.00058|0.07608|-64.79%|0.07597|-64.81%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34014|1.36359|0.00519|1.34831|0.00%|1.34796|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/345d229385)|1.35268|1.37794|0.00731|1.36605|1.32%|1.36580|1.32%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/fec4f7f389)|1.28331|1.29751|0.00327|1.29046|-4.29%|1.29016|-4.29%|20.60 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fec4f7f389)|0.52656|0.53894|0.00322|0.53261|-60.50%|0.53225|-60.51%|21.80 MB|
