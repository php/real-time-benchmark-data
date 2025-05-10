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
| Kernel        |6.1.134-150.224.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250428|
| GCC           |11.5.0|
| Time          |2025-05-10 00:49:35 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43792|0.45219|0.00244|0.43925|0.00%|0.43873|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b0cb760d4)|0.43782|0.43997|0.00054|0.43882|-0.10%|0.43879|0.01%|41.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|0.43777|0.44042|0.00057|0.43866|-0.13%|0.43856|-0.04%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.42586|0.42716|0.00032|0.42654|-2.90%|0.42651|-2.79%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71315|0.71703|0.00080|0.71433|0.00%|0.71422|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b0cb760d4)|0.70870|0.71217|0.00089|0.71018|-0.58%|0.71013|-0.57%|37.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|0.70850|0.72058|0.00213|0.70991|-0.62%|0.70940|-0.67%|37.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.68379|0.68562|0.00053|0.68470|-4.15%|0.68468|-4.14%|44.61 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58083|0.58302|0.00049|0.58213|0.00%|0.58210|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b0cb760d4)|0.58454|0.58675|0.00050|0.58589|0.65%|0.58589|0.65%|43.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|0.58479|0.58733|0.00055|0.58589|0.65%|0.58579|0.63%|43.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.52356|0.52520|0.00042|0.52446|-9.91%|0.52443|-9.91%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21529|0.21854|0.00075|0.21665|0.00%|0.21665|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b0cb760d4)|0.21395|0.21731|0.00097|0.21501|-0.76%|0.21490|-0.81%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|0.21339|0.22105|0.00173|0.21500|-0.76%|0.21443|-1.02%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.07506|0.07842|0.00094|0.07679|-64.55%|0.07663|-64.63%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34327|1.36288|0.00553|1.35197|0.00%|1.35244|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b0cb760d4)|1.27064|1.29125|0.00582|1.28112|-5.24%|1.28113|-5.27%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|1.26781|1.30489|0.00719|1.27926|-5.38%|1.27833|-5.48%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.56234|0.58051|0.00403|0.57385|-57.55%|0.57466|-57.51%|21.83 MB|
