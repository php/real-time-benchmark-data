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
| Time          |2025-02-05 00:49:27 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43895|0.44056|0.00041|0.43976|0.00%|0.43974|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9040e795ed)|0.43823|0.44020|0.00043|0.43897|-0.18%|0.43896|-0.18%|41.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/dc7161cffe)|0.43899|0.44164|0.00050|0.43973|-0.01%|0.43967|-0.01%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dc7161cffe)|0.42570|0.43226|0.00094|0.42651|-3.01%|0.42630|-3.05%|50.79 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71281|0.71698|0.00091|0.71423|0.00%|0.71414|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9040e795ed)|0.71053|0.71553|0.00092|0.71196|-0.32%|0.71175|-0.33%|37.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/dc7161cffe)|0.70927|0.72466|0.00287|0.71090|-0.47%|0.71020|-0.55%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dc7161cffe)|0.68200|0.68605|0.00090|0.68347|-4.31%|0.68314|-4.34%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58078|0.58382|0.00067|0.58172|0.00%|0.58160|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9040e795ed)|0.57584|0.58739|0.00166|0.57713|-0.79%|0.57685|-0.82%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/dc7161cffe)|0.57914|0.58176|0.00061|0.58052|-0.21%|0.58053|-0.18%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dc7161cffe)|0.51919|0.52297|0.00062|0.52179|-10.30%|0.52186|-10.27%|60.58 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21497|0.21913|0.00111|0.21639|0.00%|0.21603|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9040e795ed)|0.21443|0.21969|0.00090|0.21570|-0.32%|0.21552|-0.24%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/dc7161cffe)|0.21634|0.22030|0.00083|0.21764|0.58%|0.21749|0.67%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dc7161cffe)|0.07385|0.07745|0.00088|0.07566|-65.03%|0.07543|-65.09%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33935|1.36224|0.00523|1.34899|0.00%|1.34883|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9040e795ed)|1.23982|1.26382|0.00556|1.25190|-7.20%|1.25171|-7.20%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/dc7161cffe)|1.28679|1.31080|0.00551|1.29690|-3.86%|1.29773|-3.79%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dc7161cffe)|0.53323|0.56571|0.00725|0.55183|-59.09%|0.55167|-59.10%|21.71 MB|
