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
| Kernel        |6.1.141-165.249.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250715|
| GCC           |11.5.0|
| Time          |2025-07-21 00:50:11 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43769|0.44350|0.00087|0.44068|0.00%|0.44066|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/03a9f03822)|0.43827|0.44673|0.00159|0.43936|-0.30%|0.43892|-0.39%|42.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/e91d2c719f)|0.43907|0.44068|0.00040|0.43957|-0.25%|0.43952|-0.26%|42.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e91d2c719f)|0.42287|0.42397|0.00031|0.42336|-3.93%|0.42330|-3.94%|51.46 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71228|0.71714|0.00115|0.71367|0.00%|0.71332|0.00%|37.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/03a9f03822)|0.71125|0.71607|0.00122|0.71265|-0.14%|0.71216|-0.16%|38.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/e91d2c719f)|0.71026|0.72315|0.00292|0.71232|-0.19%|0.71154|-0.25%|38.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e91d2c719f)|0.67825|0.68318|0.00116|0.67993|-4.73%|0.67960|-4.73%|45.07 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58246|0.59228|0.00171|0.58381|0.00%|0.58334|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/03a9f03822)|0.58463|0.58642|0.00044|0.58545|0.28%|0.58546|0.36%|43.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/e91d2c719f)|0.58276|0.58425|0.00036|0.58359|-0.04%|0.58358|0.04%|43.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e91d2c719f)|0.52538|0.52682|0.00040|0.52609|-9.89%|0.52611|-9.81%|62.17 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21415|0.21780|0.00106|0.21583|0.00%|0.21593|0.00%|26.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/03a9f03822)|0.21421|0.21940|0.00103|0.21585|0.01%|0.21573|-0.09%|26.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/e91d2c719f)|0.21575|0.21786|0.00052|0.21656|0.34%|0.21645|0.24%|26.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e91d2c719f)|0.07560|0.07899|0.00071|0.07677|-64.43%|0.07663|-64.51%|27.91 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41969|1.44062|0.00512|1.42893|0.00%|1.42868|0.00%|20.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/03a9f03822)|1.29333|1.31015|0.00419|1.30115|-8.94%|1.30109|-8.93%|20.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/e91d2c719f)|1.31480|1.33144|0.00388|1.32297|-7.42%|1.32276|-7.41%|20.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e91d2c719f)|0.56181|0.58007|0.00474|0.57305|-59.90%|0.57394|-59.83%|22.35 MB|
