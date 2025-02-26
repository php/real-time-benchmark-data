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
| Time          |2025-02-26 00:49:48 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43771|0.43953|0.00040|0.43855|0.00%|0.43859|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a10b990f2)|0.43572|0.43737|0.00033|0.43657|-0.45%|0.43657|-0.46%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6cd754121)|0.43461|0.43715|0.00053|0.43552|-0.69%|0.43549|-0.71%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6cd754121)|0.42281|0.42522|0.00053|0.42352|-3.43%|0.42338|-3.47%|50.78 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70473|0.71649|0.00194|0.71314|0.00%|0.71328|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a10b990f2)|0.70607|0.70928|0.00082|0.70729|-0.82%|0.70722|-0.85%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6cd754121)|0.70489|0.70783|0.00079|0.70615|-0.98%|0.70577|-1.05%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6cd754121)|0.67787|0.68071|0.00060|0.67934|-4.74%|0.67935|-4.76%|44.54 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57966|0.58240|0.00060|0.58099|0.00%|0.58094|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a10b990f2)|0.57824|0.58062|0.00054|0.57965|-0.23%|0.57960|-0.23%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6cd754121)|0.57789|0.58099|0.00069|0.57909|-0.33%|0.57890|-0.35%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6cd754121)|0.51948|0.52228|0.00075|0.52104|-10.32%|0.52124|-10.28%|61.90 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21461|0.21952|0.00117|0.21655|0.00%|0.21638|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a10b990f2)|0.21721|0.22133|0.00105|0.21899|1.13%|0.21900|1.21%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6cd754121)|0.21631|0.21999|0.00076|0.21772|0.54%|0.21759|0.56%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6cd754121)|0.07512|0.07809|0.00081|0.07628|-64.77%|0.07599|-64.88%|27.36 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33726|1.35651|0.00514|1.34774|0.00%|1.34736|0.00%|20.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a10b990f2)|1.28197|1.30788|0.00589|1.29432|-3.96%|1.29302|-4.03%|20.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6cd754121)|1.37280|1.40358|0.00799|1.38955|3.10%|1.39028|3.19%|20.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6cd754121)|0.55117|0.57656|0.00675|0.56361|-58.18%|0.56494|-58.07%|21.78 MB|
