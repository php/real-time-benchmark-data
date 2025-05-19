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
| Time          |2025-05-19 00:50:08 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43853|0.45097|0.00213|0.43974|0.00%|0.43940|0.00%|41.92 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/419b9a7ff6)|0.43967|0.44182|0.00050|0.44060|0.20%|0.44051|0.25%|42.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/00f0175ba9)|0.43903|0.44170|0.00060|0.44027|0.12%|0.44010|0.16%|42.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/00f0175ba9)|0.42683|0.42804|0.00030|0.42739|-2.81%|0.42738|-2.74%|50.94 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71440|0.71766|0.00075|0.71584|0.00%|0.71566|0.00%|37.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/419b9a7ff6)|0.70815|0.71154|0.00090|0.70969|-0.86%|0.70955|-0.85%|37.72 MB|
|[PHP - master](https://github.com/php/php-src/commit/00f0175ba9)|0.69935|0.71137|0.00192|0.70887|-0.97%|0.70905|-0.92%|37.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/00f0175ba9)|0.68425|0.68721|0.00076|0.68515|-4.29%|0.68491|-4.30%|44.70 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58153|0.58359|0.00057|0.58256|0.00%|0.58246|0.00%|43.13 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/419b9a7ff6)|0.58315|0.58577|0.00060|0.58420|0.28%|0.58422|0.30%|43.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/00f0175ba9)|0.57886|0.58399|0.00125|0.58032|-0.39%|0.57996|-0.43%|43.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/00f0175ba9)|0.52350|0.52531|0.00049|0.52424|-10.01%|0.52421|-10.00%|62.26 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21615|0.21889|0.00072|0.21735|0.00%|0.21761|0.00%|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/419b9a7ff6)|0.21282|0.22103|0.00182|0.21454|-1.30%|0.21403|-1.65%|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/00f0175ba9)|0.21221|0.21715|0.00134|0.21382|-1.62%|0.21379|-1.76%|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/00f0175ba9)|0.07470|0.07889|0.00088|0.07656|-64.77%|0.07656|-64.82%|27.49 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34397|1.36793|0.00533|1.35143|0.00%|1.35000|0.00%|20.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/419b9a7ff6)|1.27394|1.29830|0.00558|1.28574|-4.86%|1.28535|-4.79%|20.59 MB|
|[PHP - master](https://github.com/php/php-src/commit/00f0175ba9)|1.26778|1.29637|0.00711|1.28196|-5.14%|1.27998|-5.19%|20.59 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/00f0175ba9)|0.56468|0.57633|0.00343|0.57038|-57.79%|0.57076|-57.72%|21.91 MB|
