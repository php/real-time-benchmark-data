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
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-05-29 00:50:31 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43853|0.44346|0.00086|0.43924|0.00%|0.43913|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c4fba3708c)|0.43961|0.44618|0.00119|0.44058|0.31%|0.44029|0.26%|42.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/a63d0a49b0)|0.43794|0.43963|0.00042|0.43867|-0.13%|0.43866|-0.11%|42.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a63d0a49b0)|0.42302|0.42467|0.00039|0.42365|-3.55%|0.42355|-3.55%|51.28 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71460|0.71745|0.00069|0.71609|0.00%|0.71608|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c4fba3708c)|0.71332|0.72426|0.00195|0.71466|-0.20%|0.71426|-0.25%|38.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/a63d0a49b0)|0.71421|0.72638|0.00209|0.71594|-0.02%|0.71537|-0.10%|38.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a63d0a49b0)|0.68229|0.68503|0.00070|0.68333|-4.57%|0.68335|-4.57%|45.03 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58097|0.58424|0.00077|0.58221|0.00%|0.58209|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c4fba3708c)|0.58319|0.58586|0.00066|0.58414|0.33%|0.58401|0.33%|43.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/a63d0a49b0)|0.58081|0.58283|0.00049|0.58156|-0.11%|0.58168|-0.07%|43.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a63d0a49b0)|0.52533|0.52789|0.00058|0.52622|-9.62%|0.52612|-9.62%|61.05 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21447|0.21839|0.00087|0.21579|0.00%|0.21584|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c4fba3708c)|0.21587|0.22038|0.00110|0.21751|0.80%|0.21745|0.75%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/a63d0a49b0)|0.21759|0.22276|0.00118|0.21962|1.77%|0.21961|1.75%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a63d0a49b0)|0.07696|0.07907|0.00054|0.07769|-64.00%|0.07764|-64.03%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34266|1.36118|0.00429|1.34983|0.00%|1.34925|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c4fba3708c)|1.30729|1.32815|0.00480|1.31641|-2.48%|1.31661|-2.42%|20.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/a63d0a49b0)|1.28945|1.29984|0.00259|1.29366|-4.16%|1.29292|-4.17%|20.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a63d0a49b0)|0.54468|0.55958|0.00431|0.55330|-59.01%|0.55230|-59.07%|22.20 MB|
