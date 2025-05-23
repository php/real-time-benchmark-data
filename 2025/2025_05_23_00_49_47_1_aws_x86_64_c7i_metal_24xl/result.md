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
| Time          |2025-05-23 00:49:47 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43825|0.44014|0.00048|0.43900|0.00%|0.43894|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd43536b27)|0.43727|0.44147|0.00084|0.43844|-0.13%|0.43813|-0.18%|42.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|0.43737|0.44059|0.00074|0.43845|-0.13%|0.43828|-0.15%|42.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.42189|0.42500|0.00054|0.42251|-3.76%|0.42241|-3.77%|50.93 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71345|0.71552|0.00062|0.71452|0.00%|0.71442|0.00%|37.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd43536b27)|0.71347|0.72456|0.00192|0.71498|0.06%|0.71464|0.03%|37.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|0.71349|0.72379|0.00189|0.71512|0.08%|0.71461|0.03%|37.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.67933|0.68175|0.00062|0.68030|-4.79%|0.68018|-4.79%|44.68 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58074|0.58306|0.00058|0.58173|0.00%|0.58168|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd43536b27)|0.58027|0.58260|0.00049|0.58107|-0.11%|0.58100|-0.12%|43.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|0.57950|0.58217|0.00059|0.58112|-0.10%|0.58125|-0.07%|43.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.52470|0.52646|0.00039|0.52562|-9.64%|0.52554|-9.65%|60.78 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21527|0.22000|0.00111|0.21684|0.00%|0.21632|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd43536b27)|0.21882|0.22468|0.00119|0.22054|1.71%|0.22033|1.85%|26.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|0.21722|0.22043|0.00076|0.21840|0.72%|0.21826|0.90%|26.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.07477|0.07864|0.00088|0.07680|-64.58%|0.07677|-64.51%|27.50 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34187|1.36729|0.00548|1.35149|0.00%|1.35074|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cd43536b27)|1.28260|1.30764|0.00588|1.29602|-4.10%|1.29515|-4.12%|20.67 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|1.28614|1.30086|0.00448|1.29501|-4.18%|1.29545|-4.09%|20.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.54272|0.55776|0.00315|0.54819|-59.44%|0.54781|-59.44%|21.91 MB|
