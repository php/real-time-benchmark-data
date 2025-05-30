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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-07 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43983|0.44196|0.00059|0.44094|0.00%|0.44097|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac9392b855)|0.43913|0.44142|0.00062|0.44034|-0.14%|0.44058|-0.09%|41.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/633400bb56)|0.43837|0.44069|0.00060|0.43948|-0.33%|0.43939|-0.36%|41.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/633400bb56)|0.42729|0.42920|0.00041|0.42831|-2.87%|0.42823|-2.89%|50.88 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71374|0.71752|0.00089|0.71554|0.00%|0.71535|0.00%|37.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac9392b855)|0.70596|0.71454|0.00144|0.71272|-0.39%|0.71286|-0.35%|37.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/633400bb56)|0.71296|0.71525|0.00052|0.71394|-0.22%|0.71397|-0.19%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/633400bb56)|0.68188|0.68551|0.00074|0.68338|-4.49%|0.68330|-4.48%|44.73 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58157|0.58429|0.00062|0.58260|0.00%|0.58261|0.00%|43.07 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac9392b855)|0.57921|0.58170|0.00054|0.58058|-0.35%|0.58051|-0.36%|43.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/633400bb56)|0.58075|0.58276|0.00052|0.58180|-0.14%|0.58180|-0.14%|43.04 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/633400bb56)|0.52149|0.52461|0.00075|0.52325|-10.19%|0.52341|-10.16%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21553|0.21876|0.00076|0.21670|0.00%|0.21668|0.00%|26.23 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac9392b855)|0.21766|0.22250|0.00108|0.21984|1.45%|0.21977|1.42%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/633400bb56)|0.21737|0.22137|0.00106|0.21910|1.10%|0.21868|0.92%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/633400bb56)|0.07472|0.07826|0.00101|0.07662|-64.64%|0.07673|-64.59%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33854|1.35842|0.00455|1.34744|0.00%|1.34787|0.00%|20.49 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac9392b855)|1.29105|1.31009|0.00459|1.29869|-3.62%|1.29892|-3.63%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/633400bb56)|1.29151|1.30704|0.00414|1.29861|-3.62%|1.29736|-3.75%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/633400bb56)|0.53241|0.54841|0.00431|0.54138|-59.82%|0.54228|-59.77%|21.83 MB|
