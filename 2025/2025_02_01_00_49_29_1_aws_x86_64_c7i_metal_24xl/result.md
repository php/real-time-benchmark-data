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
| Kernel        |6.1.124-134.200.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250128|
| GCC           |11.4.1|
| Time          |2025-02-01 00:49:29 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44027|0.45130|0.00147|0.44153|0.00%|0.44136|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3ff7758bcf)|0.44012|0.44254|0.00058|0.44111|-0.09%|0.44099|-0.08%|41.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/8deca2838c)|0.44149|0.44397|0.00056|0.44250|0.22%|0.44249|0.26%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8deca2838c)|0.42868|0.43559|0.00096|0.42978|-2.66%|0.42959|-2.67%|50.79 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71411|0.71707|0.00071|0.71553|0.00%|0.71560|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3ff7758bcf)|0.71148|0.72873|0.00232|0.71325|-0.32%|0.71282|-0.39%|37.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/8deca2838c)|0.71284|0.71549|0.00056|0.71395|-0.22%|0.71393|-0.23%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8deca2838c)|0.68468|0.68848|0.00092|0.68626|-4.09%|0.68618|-4.11%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58100|0.58455|0.00071|0.58257|0.00%|0.58242|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3ff7758bcf)|0.57665|0.58162|0.00096|0.57872|-0.66%|0.57874|-0.63%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/8deca2838c)|0.58237|0.58463|0.00043|0.58316|0.10%|0.58318|0.13%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8deca2838c)|0.52151|0.52366|0.00048|0.52257|-10.30%|0.52266|-10.26%|60.58 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21452|0.21757|0.00073|0.21566|0.00%|0.21571|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3ff7758bcf)|0.21456|0.21776|0.00077|0.21583|0.08%|0.21575|0.02%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/8deca2838c)|0.21166|0.21526|0.00078|0.21287|-1.30%|0.21272|-1.38%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8deca2838c)|0.07411|0.07807|0.00095|0.07590|-64.81%|0.07568|-64.92%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33467|1.36658|0.00631|1.35025|0.00%|1.35062|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3ff7758bcf)|1.24771|1.27452|0.00731|1.25903|-6.76%|1.25854|-6.82%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/8deca2838c)|1.27970|1.30935|0.00662|1.29285|-4.25%|1.29095|-4.42%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8deca2838c)|0.56819|0.59983|0.00745|0.58479|-56.69%|0.58479|-56.70%|21.71 MB|
