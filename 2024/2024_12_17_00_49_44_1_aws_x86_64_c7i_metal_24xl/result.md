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
| Time          |2024-12-17 00:49:44 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43890|0.45474|0.00213|0.44009|0.00%|0.43982|0.00%|41.81 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e02c226725)|0.43648|0.43806|0.00039|0.43716|-0.66%|0.43713|-0.61%|41.68 MB|
|[PHP - master](https://github.com/php/php-src/commit/4750ce1e6d)|0.43696|0.44301|0.00113|0.43785|-0.51%|0.43756|-0.51%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4750ce1e6d)|0.42372|0.42542|0.00037|0.42468|-3.50%|0.42475|-3.43%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71328|0.71668|0.00070|0.71502|0.00%|0.71490|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e02c226725)|0.71181|0.72803|0.00223|0.71338|-0.23%|0.71295|-0.27%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/4750ce1e6d)|0.71155|0.71447|0.00067|0.71278|-0.31%|0.71277|-0.30%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4750ce1e6d)|0.68317|0.68573|0.00056|0.68410|-4.33%|0.68396|-4.33%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58130|0.58479|0.00060|0.58243|0.00%|0.58239|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e02c226725)|0.57919|0.58188|0.00072|0.58044|-0.34%|0.58030|-0.36%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/4750ce1e6d)|0.57505|0.58087|0.00166|0.57894|-0.60%|0.57956|-0.49%|42.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4750ce1e6d)|0.51969|0.52245|0.00055|0.52070|-10.60%|0.52065|-10.60%|61.62 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21453|0.21814|0.00083|0.21603|0.00%|0.21595|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e02c226725)|0.21257|0.21581|0.00068|0.21339|-1.22%|0.21326|-1.24%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/4750ce1e6d)|0.21194|0.21593|0.00082|0.21333|-1.25%|0.21324|-1.25%|26.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4750ce1e6d)|0.07428|0.07839|0.00087|0.07571|-64.95%|0.07563|-64.98%|27.22 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33984|1.36738|0.00620|1.35366|0.00%|1.35320|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e02c226725)|1.25206|1.26866|0.00365|1.25971|-6.94%|1.25942|-6.93%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/4750ce1e6d)|1.24962|1.26997|0.00495|1.25995|-6.92%|1.26014|-6.88%|20.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4750ce1e6d)|0.52537|0.54011|0.00357|0.53331|-60.60%|0.53337|-60.58%|21.64 MB|
