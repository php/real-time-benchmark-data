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
| Kernel        |6.1.141-155.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250623|
| GCC           |11.5.0|
| Time          |2025-07-06 00:50:04 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43719|0.44984|0.00195|0.44137|0.00%|0.44099|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4560f7037d)|0.44106|0.44408|0.00066|0.44197|0.13%|0.44174|0.17%|42.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/677a1f80c8)|0.43674|0.44074|0.00088|0.43806|-0.75%|0.43785|-0.71%|42.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/677a1f80c8)|0.42314|0.42487|0.00040|0.42391|-3.96%|0.42389|-3.88%|51.62 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71386|0.71728|0.00083|0.71503|0.00%|0.71479|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4560f7037d)|0.71203|0.71488|0.00076|0.71322|-0.25%|0.71311|-0.23%|38.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/677a1f80c8)|0.70165|0.71274|0.00183|0.71045|-0.64%|0.71067|-0.58%|38.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/677a1f80c8)|0.67967|0.68150|0.00048|0.68060|-4.82%|0.68061|-4.78%|45.23 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57889|0.58789|0.00242|0.58241|0.00%|0.58335|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4560f7037d)|0.58073|0.59202|0.00195|0.58251|0.02%|0.58192|-0.25%|43.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/677a1f80c8)|0.58258|0.58482|0.00060|0.58360|0.20%|0.58358|0.04%|43.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/677a1f80c8)|0.52458|0.52709|0.00051|0.52577|-9.73%|0.52572|-9.88%|61.66 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21368|0.21969|0.00142|0.21593|0.00%|0.21586|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4560f7037d)|0.21183|0.21481|0.00091|0.21308|-1.32%|0.21298|-1.34%|26.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/677a1f80c8)|0.21796|0.22193|0.00101|0.21993|1.85%|0.21988|1.86%|26.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/677a1f80c8)|0.07656|0.07865|0.00051|0.07736|-64.18%|0.07724|-64.22%|28.03 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42082|1.43761|0.00444|1.42987|0.00%|1.42964|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4560f7037d)|1.29020|1.31017|0.00468|1.30465|-8.76%|1.30594|-8.65%|21.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/677a1f80c8)|1.28549|1.30001|0.00408|1.29259|-9.60%|1.29159|-9.66%|21.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/677a1f80c8)|0.54538|0.55937|0.00285|0.55290|-61.33%|0.55274|-61.34%|22.48 MB|
