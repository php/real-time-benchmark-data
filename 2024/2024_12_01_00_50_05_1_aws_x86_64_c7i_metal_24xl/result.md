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
| Kernel        |6.1.115-126.197.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241121|
| GCC           |11.4.1|
| Time          |2024-12-01 00:50:05 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44044|0.44967|0.00152|0.44218|0.00%|0.44192|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fdd3839d80)|0.43962|0.44177|0.00055|0.44062|-0.35%|0.44062|-0.29%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/b06f2bc67c)|0.44007|0.44271|0.00051|0.44086|-0.30%|0.44077|-0.26%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b06f2bc67c)|0.42679|0.42914|0.00046|0.42789|-3.23%|0.42793|-3.16%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71543|0.71880|0.00077|0.71733|0.00%|0.71732|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fdd3839d80)|0.71337|0.71675|0.00084|0.71472|-0.36%|0.71468|-0.37%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/b06f2bc67c)|0.71012|0.71653|0.00101|0.71361|-0.52%|0.71359|-0.52%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b06f2bc67c)|0.68354|0.68737|0.00080|0.68514|-4.49%|0.68517|-4.48%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58166|0.58922|0.00179|0.58649|0.00%|0.58702|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fdd3839d80)|0.58022|0.58471|0.00113|0.58244|-0.69%|0.58269|-0.74%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/b06f2bc67c)|0.57677|0.58328|0.00141|0.58136|-0.88%|0.58158|-0.93%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b06f2bc67c)|0.52113|0.52721|0.00217|0.52398|-10.66%|0.52435|-10.68%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21448|0.22030|0.00116|0.21684|0.00%|0.21684|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fdd3839d80)|0.21508|0.22211|0.00112|0.21746|0.29%|0.21743|0.27%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/b06f2bc67c)|0.21381|0.21790|0.00087|0.21596|-0.40%|0.21593|-0.42%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b06f2bc67c)|0.07412|0.07802|0.00096|0.07581|-65.04%|0.07564|-65.12%|27.29 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33848|1.37098|0.00683|1.35284|0.00%|1.35217|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fdd3839d80)|1.25421|1.27096|0.00420|1.26048|-6.83%|1.25962|-6.84%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/b06f2bc67c)|1.25175|1.27384|0.00488|1.25936|-6.91%|1.25961|-6.84%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b06f2bc67c)|0.54647|0.56450|0.00406|0.55437|-59.02%|0.55419|-59.01%|21.70 MB|
