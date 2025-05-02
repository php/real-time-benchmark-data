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
| Time          |2025-05-02 00:49:44 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43801|0.45224|0.00246|0.43920|0.00%|0.43877|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/156d034d3d)|0.43945|0.44106|0.00038|0.44034|0.26%|0.44040|0.37%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd5733202d)|0.43916|0.44197|0.00074|0.44017|0.22%|0.43996|0.27%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd5733202d)|0.42498|0.42796|0.00058|0.42595|-3.02%|0.42583|-2.95%|50.84 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71426|0.72971|0.00271|0.71558|0.00%|0.71502|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/156d034d3d)|0.70994|0.71328|0.00093|0.71167|-0.55%|0.71154|-0.49%|37.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd5733202d)|0.70956|0.71251|0.00072|0.71109|-0.63%|0.71107|-0.55%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd5733202d)|0.68291|0.68610|0.00073|0.68439|-4.36%|0.68437|-4.29%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58064|0.59168|0.00187|0.58215|0.00%|0.58178|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/156d034d3d)|0.58377|0.58686|0.00073|0.58477|0.45%|0.58479|0.52%|43.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd5733202d)|0.58005|0.58585|0.00184|0.58396|0.31%|0.58458|0.48%|43.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd5733202d)|0.52255|0.52407|0.00038|0.52343|-10.09%|0.52346|-10.03%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21565|0.21843|0.00066|0.21684|0.00%|0.21674|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/156d034d3d)|0.21620|0.22318|0.00143|0.21770|0.40%|0.21729|0.25%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd5733202d)|0.21623|0.21988|0.00103|0.21740|0.26%|0.21698|0.11%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd5733202d)|0.07584|0.07823|0.00067|0.07684|-64.56%|0.07668|-64.62%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34581|1.35959|0.00388|1.35095|0.00%|1.35032|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/156d034d3d)|1.28149|1.29600|0.00457|1.28844|-4.63%|1.28856|-4.57%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd5733202d)|1.27842|1.29249|0.00358|1.28648|-4.77%|1.28623|-4.75%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd5733202d)|0.56491|0.57437|0.00246|0.56967|-57.83%|0.56962|-57.82%|21.82 MB|
