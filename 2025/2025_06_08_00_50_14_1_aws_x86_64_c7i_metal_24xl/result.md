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
| OS            |Amazon Linux 2023.7.20250527|
| GCC           |11.5.0|
| Time          |2025-06-08 00:50:14 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44076|0.45513|0.00247|0.44220|0.00%|0.44161|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cce0efdff8)|0.44196|0.44513|0.00056|0.44292|0.16%|0.44278|0.26%|42.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/ceffa70b97)|0.44265|0.44633|0.00077|0.44364|0.33%|0.44351|0.43%|42.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ceffa70b97)|0.42759|0.42906|0.00044|0.42819|-3.17%|0.42814|-3.05%|51.18 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71720|0.72149|0.00090|0.71902|0.00%|0.71909|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cce0efdff8)|0.71271|0.71617|0.00069|0.71466|-0.61%|0.71464|-0.62%|37.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/ceffa70b97)|0.71375|0.71691|0.00067|0.71501|-0.56%|0.71495|-0.58%|37.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ceffa70b97)|0.68318|0.68632|0.00073|0.68460|-4.79%|0.68455|-4.80%|44.94 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58144|0.58396|0.00057|0.58244|0.00%|0.58236|0.00%|43.09 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cce0efdff8)|0.58235|0.58590|0.00067|0.58309|0.11%|0.58297|0.10%|43.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/ceffa70b97)|0.58297|0.58596|0.00061|0.58431|0.32%|0.58435|0.34%|43.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ceffa70b97)|0.52664|0.52828|0.00041|0.52737|-9.46%|0.52733|-9.45%|60.97 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21526|0.21869|0.00076|0.21674|0.00%|0.21681|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cce0efdff8)|0.21124|0.21628|0.00158|0.21341|-1.54%|0.21316|-1.68%|26.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/ceffa70b97)|0.21607|0.21952|0.00090|0.21748|0.34%|0.21731|0.23%|26.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ceffa70b97)|0.07583|0.07936|0.00091|0.07717|-64.39%|0.07690|-64.53%|27.70 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34439|1.36488|0.00532|1.35505|0.00%|1.35482|0.00%|20.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cce0efdff8)|1.29338|1.31389|0.00535|1.30376|-3.79%|1.30436|-3.72%|20.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/ceffa70b97)|1.31067|1.33414|0.00631|1.32232|-2.42%|1.32321|-2.33%|20.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ceffa70b97)|0.56682|0.58326|0.00424|0.57609|-57.49%|0.57512|-57.55%|22.11 MB|
