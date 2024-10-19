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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-10-19 00:49:36 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43979|0.45255|0.00179|0.44124|0.00%|0.44099|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/42e179ef9d)|0.43789|0.44081|0.00058|0.43888|-0.53%|0.43881|-0.49%|41.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/a00c73458f)|0.43846|0.44057|0.00046|0.43933|-0.43%|0.43929|-0.39%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a00c73458f)|0.42811|0.43026|0.00044|0.42915|-2.74%|0.42918|-2.68%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.72133|0.72502|0.00082|0.72296|0.00%|0.72300|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/42e179ef9d)|0.71704|0.72241|0.00101|0.71869|-0.59%|0.71860|-0.61%|37.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/a00c73458f)|0.71726|0.73636|0.00256|0.71962|-0.46%|0.71918|-0.53%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a00c73458f)|0.69347|0.69745|0.00079|0.69489|-3.88%|0.69489|-3.89%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58154|0.58555|0.00063|0.58316|0.00%|0.58316|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/42e179ef9d)|0.57778|0.58175|0.00072|0.57949|-0.63%|0.57937|-0.65%|42.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/a00c73458f)|0.57986|0.58248|0.00062|0.58084|-0.40%|0.58078|-0.41%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a00c73458f)|0.52473|0.52702|0.00043|0.52558|-9.87%|0.52560|-9.87%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21504|0.22080|0.00121|0.21692|0.00%|0.21660|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/42e179ef9d)|0.21493|0.21808|0.00070|0.21630|-0.28%|0.21627|-0.15%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/a00c73458f)|0.21624|0.22062|0.00085|0.21793|0.47%|0.21774|0.53%|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a00c73458f)|0.07396|0.07714|0.00065|0.07553|-65.18%|0.07540|-65.19%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34026|1.36478|0.00530|1.34947|0.00%|1.34976|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/42e179ef9d)|1.29753|1.31772|0.00440|1.30659|-3.18%|1.30666|-3.19%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/a00c73458f)|1.26869|1.29163|0.00540|1.28228|-4.98%|1.28236|-4.99%|20.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a00c73458f)|0.51579|0.53420|0.00370|0.52297|-61.25%|0.52241|-61.30%|21.71 MB|
