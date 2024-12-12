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
| OS            |Amazon Linux 2023.6.20241209|
| GCC           |11.4.1|
| Time          |2024-12-12 00:49:50 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43864|0.44809|0.00127|0.43987|0.00%|0.43976|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e759e079f)|0.43607|0.43803|0.00044|0.43700|-0.65%|0.43698|-0.63%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/4ef1c5fb91)|0.43687|0.44384|0.00097|0.43768|-0.50%|0.43752|-0.51%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4ef1c5fb91)|0.42438|0.42596|0.00039|0.42526|-3.32%|0.42531|-3.29%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71309|0.71668|0.00082|0.71457|0.00%|0.71464|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e759e079f)|0.70688|0.70962|0.00066|0.70815|-0.90%|0.70810|-0.92%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/4ef1c5fb91)|0.70617|0.71016|0.00097|0.70782|-0.94%|0.70766|-0.98%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4ef1c5fb91)|0.68067|0.68336|0.00062|0.68200|-4.56%|0.68190|-4.58%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58114|0.58467|0.00063|0.58250|0.00%|0.58245|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e759e079f)|0.57787|0.58024|0.00047|0.57886|-0.63%|0.57884|-0.62%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/4ef1c5fb91)|0.57733|0.58028|0.00064|0.57868|-0.66%|0.57863|-0.66%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4ef1c5fb91)|0.52091|0.52278|0.00050|0.52171|-10.44%|0.52171|-10.43%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21454|0.21938|0.00111|0.21625|0.00%|0.21603|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e759e079f)|0.21502|0.21886|0.00085|0.21681|0.26%|0.21665|0.29%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/4ef1c5fb91)|0.21540|0.22037|0.00108|0.21723|0.45%|0.21700|0.45%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4ef1c5fb91)|0.07435|0.07797|0.00081|0.07578|-64.96%|0.07572|-64.95%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34299|1.36467|0.00528|1.35328|0.00%|1.35345|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e759e079f)|1.32846|1.34932|0.00459|1.33632|-1.25%|1.33524|-1.35%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/4ef1c5fb91)|1.32835|1.34855|0.00428|1.33591|-1.28%|1.33602|-1.29%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4ef1c5fb91)|0.53440|0.55373|0.00427|0.54295|-59.88%|0.54262|-59.91%|21.64 MB|
