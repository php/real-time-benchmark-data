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
| Time          |2025-04-10 00:49:41 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43984|0.44163|0.00046|0.44073|0.00%|0.44070|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c20b429a90)|0.43951|0.44238|0.00063|0.44062|-0.02%|0.44062|-0.02%|41.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/787f26c882)|0.44015|0.44235|0.00055|0.44116|0.10%|0.44117|0.11%|41.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/787f26c882)|0.42764|0.42924|0.00037|0.42840|-2.80%|0.42840|-2.79%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71406|0.71808|0.00102|0.71577|0.00%|0.71574|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c20b429a90)|0.70504|0.71141|0.00106|0.70967|-0.85%|0.70963|-0.85%|37.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/787f26c882)|0.70945|0.71370|0.00098|0.71131|-0.62%|0.71125|-0.63%|37.57 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/787f26c882)|0.68071|0.68396|0.00092|0.68210|-4.70%|0.68202|-4.71%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58023|0.59068|0.00167|0.58217|0.00%|0.58178|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c20b429a90)|0.57824|0.58084|0.00059|0.57934|-0.49%|0.57933|-0.42%|42.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/787f26c882)|0.58079|0.58531|0.00083|0.58241|0.04%|0.58228|0.09%|42.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/787f26c882)|0.52228|0.52363|0.00037|0.52293|-10.18%|0.52291|-10.12%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21605|0.22000|0.00095|0.21750|0.00%|0.21737|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c20b429a90)|0.21743|0.22039|0.00073|0.21909|0.73%|0.21914|0.82%|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/787f26c882)|0.21338|0.21611|0.00070|0.21447|-1.39%|0.21445|-1.34%|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/787f26c882)|0.07457|0.07787|0.00077|0.07626|-64.94%|0.07623|-64.93%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33761|1.36029|0.00559|1.34766|0.00%|1.34790|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c20b429a90)|1.30950|1.32663|0.00420|1.31819|-2.19%|1.31845|-2.18%|20.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/787f26c882)|1.29627|1.31459|0.00452|1.30718|-3.00%|1.30754|-2.99%|20.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/787f26c882)|0.54081|0.57249|0.00698|0.54959|-59.22%|0.54749|-59.38%|21.82 MB|
