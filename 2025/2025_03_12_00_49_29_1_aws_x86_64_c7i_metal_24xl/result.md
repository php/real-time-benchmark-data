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
| Kernel        |6.1.129-138.220.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250303|
| GCC           |11.4.1|
| Time          |2025-03-12 00:49:29 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44062|0.44493|0.00084|0.44154|0.00%|0.44142|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9d60dc16b8)|0.43947|0.44115|0.00040|0.44006|-0.34%|0.43995|-0.33%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/645cd6a5ad)|0.43909|0.44251|0.00070|0.44008|-0.33%|0.43998|-0.32%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/645cd6a5ad)|0.42759|0.42979|0.00049|0.42843|-2.97%|0.42837|-2.96%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71587|0.71895|0.00064|0.71730|0.00%|0.71711|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9d60dc16b8)|0.70780|0.72090|0.00224|0.70948|-1.09%|0.70904|-1.13%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/645cd6a5ad)|0.70623|0.70925|0.00090|0.70754|-1.36%|0.70746|-1.35%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/645cd6a5ad)|0.67965|0.68309|0.00085|0.68120|-5.03%|0.68095|-5.04%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58167|0.58408|0.00051|0.58264|0.00%|0.58263|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9d60dc16b8)|0.57925|0.58202|0.00074|0.58014|-0.43%|0.58000|-0.45%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/645cd6a5ad)|0.57761|0.57989|0.00058|0.57869|-0.68%|0.57863|-0.69%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/645cd6a5ad)|0.52062|0.52223|0.00046|0.52148|-10.50%|0.52152|-10.49%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21534|0.21925|0.00107|0.21667|0.00%|0.21666|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9d60dc16b8)|0.21463|0.21740|0.00060|0.21572|-0.44%|0.21566|-0.46%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/645cd6a5ad)|0.21554|0.21959|0.00110|0.21679|0.06%|0.21636|-0.13%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/645cd6a5ad)|0.07492|0.07710|0.00056|0.07583|-65.00%|0.07567|-65.07%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33656|1.35449|0.00501|1.34599|0.00%|1.34506|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9d60dc16b8)|1.25660|1.27601|0.00488|1.26460|-6.05%|1.26413|-6.02%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/645cd6a5ad)|1.26762|1.28457|0.00375|1.27787|-5.06%|1.27813|-4.98%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/645cd6a5ad)|0.52606|0.53879|0.00315|0.53291|-60.41%|0.53345|-60.34%|21.79 MB|
