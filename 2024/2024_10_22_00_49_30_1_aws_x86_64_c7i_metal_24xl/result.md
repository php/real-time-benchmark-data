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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-10-22 00:49:30 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43806|0.44026|0.00045|0.43902|0.00%|0.43900|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/514c2b3587)|0.43652|0.43840|0.00051|0.43733|-0.39%|0.43726|-0.40%|41.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/6dd67bbb76)|0.43659|0.43980|0.00053|0.43751|-0.35%|0.43739|-0.37%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6dd67bbb76)|0.42610|0.43041|0.00061|0.42681|-2.78%|0.42677|-2.79%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71844|0.73321|0.00200|0.71980|0.00%|0.71953|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/514c2b3587)|0.71500|0.71836|0.00072|0.71628|-0.49%|0.71627|-0.45%|37.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/6dd67bbb76)|0.71528|0.71794|0.00059|0.71629|-0.49%|0.71614|-0.47%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6dd67bbb76)|0.69189|0.69419|0.00059|0.69300|-3.72%|0.69290|-3.70%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58202|0.58472|0.00061|0.58302|0.00%|0.58294|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/514c2b3587)|0.57861|0.58354|0.00076|0.58016|-0.49%|0.58004|-0.50%|42.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/6dd67bbb76)|0.57844|0.58143|0.00060|0.57985|-0.54%|0.57978|-0.54%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6dd67bbb76)|0.52043|0.52525|0.00068|0.52394|-10.13%|0.52401|-10.11%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21497|0.22070|0.00123|0.21679|0.00%|0.21638|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/514c2b3587)|0.21625|0.21981|0.00071|0.21778|0.46%|0.21778|0.65%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/6dd67bbb76)|0.21900|0.22308|0.00076|0.22079|1.84%|0.22070|2.00%|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6dd67bbb76)|0.07432|0.07675|0.00057|0.07555|-65.15%|0.07546|-65.13%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33571|1.36562|0.00652|1.34972|0.00%|1.34951|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/514c2b3587)|1.26361|1.29400|0.00570|1.27872|-5.26%|1.27858|-5.26%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/6dd67bbb76)|1.27882|1.30145|0.00491|1.28775|-4.59%|1.28813|-4.55%|20.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6dd67bbb76)|0.51617|0.53949|0.00413|0.52414|-61.17%|0.52374|-61.19%|21.71 MB|
