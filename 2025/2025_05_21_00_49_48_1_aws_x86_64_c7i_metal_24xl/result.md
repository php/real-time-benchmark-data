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
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-05-21 00:49:48 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43804|0.43975|0.00042|0.43873|0.00%|0.43872|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/63657df6e1)|0.43742|0.44345|0.00122|0.43877|0.01%|0.43845|-0.06%|42.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/16a3fb1c3f)|0.43954|0.44274|0.00066|0.44028|0.35%|0.44013|0.32%|42.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/16a3fb1c3f)|0.42212|0.42331|0.00030|0.42268|-3.66%|0.42267|-3.66%|50.93 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71339|0.72887|0.00273|0.71488|0.00%|0.71414|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/63657df6e1)|0.70662|0.70986|0.00076|0.70800|-0.96%|0.70787|-0.88%|37.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/16a3fb1c3f)|0.70738|0.71129|0.00084|0.70878|-0.85%|0.70871|-0.76%|37.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/16a3fb1c3f)|0.67592|0.67942|0.00079|0.67726|-5.26%|0.67721|-5.17%|44.68 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57977|0.59109|0.00181|0.58263|0.00%|0.58247|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/63657df6e1)|0.58098|0.58447|0.00074|0.58243|-0.04%|0.58232|-0.03%|43.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/16a3fb1c3f)|0.57910|0.58397|0.00086|0.58031|-0.40%|0.58010|-0.41%|43.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/16a3fb1c3f)|0.52164|0.52548|0.00071|0.52417|-10.04%|0.52417|-10.01%|60.77 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21591|0.21920|0.00075|0.21701|0.00%|0.21693|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/63657df6e1)|0.21260|0.21649|0.00098|0.21428|-1.26%|0.21430|-1.21%|26.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/16a3fb1c3f)|0.21349|0.21961|0.00126|0.21479|-1.02%|0.21462|-1.07%|26.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/16a3fb1c3f)|0.07504|0.07871|0.00088|0.07680|-64.61%|0.07664|-64.67%|27.49 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33938|1.36343|0.00619|1.35107|0.00%|1.35054|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/63657df6e1)|1.29799|1.31483|0.00422|1.30536|-3.38%|1.30504|-3.37%|20.66 MB|
|[PHP - master](https://github.com/php/php-src/commit/16a3fb1c3f)|1.31128|1.33216|0.00452|1.32122|-2.21%|1.32127|-2.17%|20.66 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/16a3fb1c3f)|0.53831|0.55226|0.00337|0.54521|-59.65%|0.54526|-59.63%|21.91 MB|
