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
| Kernel        |6.1.140-154.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250609|
| GCC           |11.5.0|
| Time          |2025-06-12 00:49:49 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44026|0.44630|0.00116|0.44142|0.00%|0.44123|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|0.43934|0.44219|0.00064|0.44058|-0.19%|0.44048|-0.17%|42.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|0.43989|0.44166|0.00044|0.44049|-0.21%|0.44049|-0.17%|42.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.42431|0.42565|0.00041|0.42485|-3.75%|0.42472|-3.74%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71471|0.73061|0.00361|0.71673|0.00%|0.71564|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|0.71013|0.71696|0.00132|0.71178|-0.69%|0.71136|-0.60%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|0.71080|0.71407|0.00098|0.71212|-0.64%|0.71201|-0.51%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.67853|0.68092|0.00061|0.67977|-5.16%|0.67982|-5.01%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58083|0.58358|0.00066|0.58198|0.00%|0.58180|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|0.57913|0.58221|0.00071|0.58050|-0.25%|0.58056|-0.21%|43.61 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|0.57961|0.58196|0.00058|0.58074|-0.21%|0.58072|-0.19%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.52484|0.52645|0.00041|0.52565|-9.68%|0.52571|-9.64%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21567|0.21878|0.00091|0.21717|0.00%|0.21690|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|0.21665|0.21906|0.00067|0.21786|0.32%|0.21781|0.42%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|0.21612|0.21799|0.00047|0.21716|-0.01%|0.21716|0.12%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.07554|0.07835|0.00075|0.07678|-64.64%|0.07673|-64.62%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34208|1.36839|0.00529|1.35334|0.00%|1.35380|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dbabbe180b)|1.32310|1.34545|0.00467|1.32881|-1.81%|1.32748|-1.94%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/dbabbe180b)|1.31873|1.34033|0.00455|1.32740|-1.92%|1.32752|-1.94%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dbabbe180b)|0.55335|0.57530|0.00526|0.56316|-58.39%|0.56339|-58.38%|22.23 MB|
