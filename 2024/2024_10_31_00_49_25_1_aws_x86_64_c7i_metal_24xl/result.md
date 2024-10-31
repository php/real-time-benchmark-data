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
| Time          |2024-10-31 00:49:25 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43851|0.45147|0.00176|0.43967|0.00%|0.43940|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b564ccd504)|0.43639|0.43909|0.00051|0.43718|-0.57%|0.43713|-0.52%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.43594|0.43843|0.00047|0.43707|-0.59%|0.43702|-0.54%|41.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.42648|0.42826|0.00038|0.42727|-2.82%|0.42716|-2.79%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71977|0.72368|0.00090|0.72082|0.00%|0.72062|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b564ccd504)|0.71222|0.72919|0.00233|0.71379|-0.98%|0.71334|-1.01%|37.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.71262|0.71598|0.00081|0.71383|-0.97%|0.71368|-0.96%|37.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.69304|0.69561|0.00057|0.69423|-3.69%|0.69427|-3.66%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58217|0.58465|0.00056|0.58312|0.00%|0.58310|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b564ccd504)|0.57940|0.58298|0.00086|0.58098|-0.37%|0.58092|-0.37%|42.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.57518|0.58141|0.00154|0.57903|-0.70%|0.57957|-0.60%|42.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.52382|0.52616|0.00057|0.52492|-9.98%|0.52485|-9.99%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21464|0.21881|0.00091|0.21636|0.00%|0.21615|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b564ccd504)|0.21571|0.21983|0.00092|0.21755|0.55%|0.21750|0.62%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.21525|0.21838|0.00084|0.21683|0.22%|0.21679|0.30%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.07353|0.07715|0.00081|0.07482|-65.42%|0.07461|-65.48%|27.36 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33750|1.36068|0.00562|1.34779|0.00%|1.34808|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b564ccd504)|1.28686|1.30361|0.00429|1.29364|-4.02%|1.29298|-4.09%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a5ef4bb3f)|1.34080|1.36439|0.00470|1.35367|0.44%|1.35294|0.36%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.52261|0.54261|0.00490|0.53123|-60.59%|0.53036|-60.66%|21.77 MB|
