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
| Time          |2025-07-05 00:49:37 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44060|0.45146|0.00185|0.44190|0.00%|0.44154|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50ddf6a68f)|0.43535|0.44835|0.00202|0.44172|-0.04%|0.44143|-0.02%|42.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/4560f7037d)|0.44035|0.44381|0.00073|0.44115|-0.17%|0.44094|-0.13%|42.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4560f7037d)|0.42231|0.42577|0.00058|0.42348|-4.17%|0.42340|-4.11%|51.60 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71442|0.71777|0.00084|0.71552|0.00%|0.71535|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50ddf6a68f)|0.71136|0.71480|0.00097|0.71285|-0.37%|0.71291|-0.34%|38.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/4560f7037d)|0.71343|0.71685|0.00084|0.71446|-0.15%|0.71427|-0.15%|38.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4560f7037d)|0.68159|0.68429|0.00067|0.68283|-4.57%|0.68274|-4.56%|45.21 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57779|0.58401|0.00187|0.57985|0.00%|0.57891|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50ddf6a68f)|0.58057|0.58264|0.00050|0.58147|0.28%|0.58147|0.44%|43.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/4560f7037d)|0.58020|0.58264|0.00057|0.58124|0.24%|0.58125|0.40%|43.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4560f7037d)|0.52380|0.52567|0.00048|0.52448|-9.55%|0.52432|-9.43%|61.64 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21453|0.22043|0.00139|0.21670|0.00%|0.21636|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50ddf6a68f)|0.21198|0.21563|0.00085|0.21333|-1.56%|0.21306|-1.53%|26.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/4560f7037d)|0.21165|0.21436|0.00068|0.21250|-1.94%|0.21228|-1.89%|26.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4560f7037d)|0.07501|0.07833|0.00092|0.07642|-64.74%|0.07611|-64.82%|28.01 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42019|1.44769|0.00574|1.42963|0.00%|1.42918|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50ddf6a68f)|1.29482|1.30662|0.00314|1.30143|-8.97%|1.30061|-9.00%|21.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/4560f7037d)|1.29473|1.31120|0.00454|1.30261|-8.88%|1.30229|-8.88%|20.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4560f7037d)|0.56524|0.58260|0.00447|0.57619|-59.70%|0.57675|-59.65%|22.44 MB|
