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
| Kernel        |6.1.132-147.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250414|
| GCC           |11.5.0|
| Time          |2025-04-20 00:49:59 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43830|0.45267|0.00247|0.43950|0.00%|0.43907|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|0.43709|0.43966|0.00051|0.43795|-0.35%|0.43789|-0.27%|41.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/f39c07a3bb)|0.43679|0.43923|0.00054|0.43795|-0.35%|0.43788|-0.27%|41.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f39c07a3bb)|0.42373|0.42535|0.00041|0.42447|-3.42%|0.42444|-3.33%|50.85 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71461|0.71887|0.00091|0.71568|0.00%|0.71557|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|0.70854|0.72046|0.00275|0.71029|-0.75%|0.70956|-0.84%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/f39c07a3bb)|0.70711|0.71903|0.00207|0.70818|-1.05%|0.70771|-1.10%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f39c07a3bb)|0.67904|0.68127|0.00052|0.67983|-5.01%|0.67975|-5.00%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57974|0.58377|0.00115|0.58146|0.00%|0.58143|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|0.57877|0.58076|0.00050|0.57987|-0.27%|0.57986|-0.27%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/f39c07a3bb)|0.57875|0.58314|0.00108|0.58137|-0.02%|0.58163|0.03%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f39c07a3bb)|0.52095|0.52229|0.00038|0.52167|-10.28%|0.52170|-10.27%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21536|0.21850|0.00091|0.21675|0.00%|0.21658|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|0.21649|0.22170|0.00110|0.21853|0.82%|0.21831|0.80%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/f39c07a3bb)|0.25608|0.27256|0.00499|0.26348|21.56%|0.26308|21.47%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f39c07a3bb)|0.07523|0.07825|0.00078|0.07688|-64.53%|0.07686|-64.51%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34201|1.36222|0.00507|1.35513|0.00%|1.35646|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|1.33258|1.34737|0.00367|1.33917|-1.18%|1.33935|-1.26%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/f39c07a3bb)|1.26663|1.28334|0.00482|1.27615|-5.83%|1.27567|-5.96%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f39c07a3bb)|0.54944|0.56083|0.00301|0.55489|-59.05%|0.55408|-59.15%|21.82 MB|
