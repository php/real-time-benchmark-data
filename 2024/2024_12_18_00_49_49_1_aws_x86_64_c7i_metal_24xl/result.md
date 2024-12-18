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
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2024-12-18 00:49:49 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43883|0.44895|0.00137|0.43980|0.00%|0.43963|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4750ce1e6d)|0.43607|0.43801|0.00046|0.43708|-0.62%|0.43709|-0.58%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d140f79e6)|0.43700|0.43909|0.00050|0.43800|-0.41%|0.43795|-0.38%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d140f79e6)|0.42441|0.42638|0.00036|0.42518|-3.32%|0.42516|-3.29%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71271|0.71624|0.00078|0.71414|0.00%|0.71398|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4750ce1e6d)|0.71049|0.71507|0.00085|0.71203|-0.29%|0.71198|-0.28%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d140f79e6)|0.70768|0.71099|0.00077|0.70907|-0.71%|0.70896|-0.70%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d140f79e6)|0.68146|0.68509|0.00076|0.68291|-4.37%|0.68270|-4.38%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58132|0.58412|0.00051|0.58218|0.00%|0.58211|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4750ce1e6d)|0.57865|0.58199|0.00071|0.58007|-0.36%|0.58000|-0.36%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d140f79e6)|0.57591|0.58711|0.00238|0.57848|-0.64%|0.57729|-0.83%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d140f79e6)|0.52069|0.52273|0.00042|0.52139|-10.44%|0.52134|-10.44%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21514|0.21935|0.00099|0.21631|0.00%|0.21602|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4750ce1e6d)|0.21184|0.21469|0.00064|0.21324|-1.42%|0.21320|-1.30%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d140f79e6)|0.21499|0.21935|0.00090|0.21622|-0.04%|0.21594|-0.04%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d140f79e6)|0.07388|0.07697|0.00075|0.07499|-65.33%|0.07488|-65.33%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34199|1.36389|0.00552|1.35265|0.00%|1.35256|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4750ce1e6d)|1.25083|1.26690|0.00392|1.26014|-6.84%|1.26012|-6.83%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d140f79e6)|1.29545|1.31880|0.00565|1.30453|-3.56%|1.30448|-3.55%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d140f79e6)|0.52556|0.54051|0.00431|0.53292|-60.60%|0.53270|-60.62%|21.64 MB|
