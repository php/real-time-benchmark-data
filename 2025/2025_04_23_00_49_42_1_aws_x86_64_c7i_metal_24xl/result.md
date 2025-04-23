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
| Time          |2025-04-23 00:49:42 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43784|0.44607|0.00147|0.43903|0.00%|0.43868|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32a45769d1)|0.43629|0.43895|0.00063|0.43715|-0.43%|0.43708|-0.36%|41.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ac1b0c917)|0.43744|0.43917|0.00037|0.43832|-0.16%|0.43834|-0.08%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ac1b0c917)|0.42319|0.42489|0.00039|0.42384|-3.46%|0.42380|-3.39%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71482|0.72975|0.00260|0.71595|0.00%|0.71541|0.00%|37.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32a45769d1)|0.70932|0.71167|0.00049|0.71039|-0.78%|0.71028|-0.72%|37.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ac1b0c917)|0.70841|0.71129|0.00069|0.70947|-0.90%|0.70927|-0.86%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ac1b0c917)|0.67936|0.68158|0.00056|0.68022|-4.99%|0.68010|-4.94%|44.61 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58053|0.59137|0.00180|0.58222|0.00%|0.58197|0.00%|43.07 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32a45769d1)|0.57919|0.58177|0.00066|0.58030|-0.33%|0.58020|-0.30%|43.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ac1b0c917)|0.57984|0.58288|0.00066|0.58112|-0.19%|0.58105|-0.16%|43.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ac1b0c917)|0.52060|0.52229|0.00043|0.52144|-10.44%|0.52135|-10.42%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21532|0.21959|0.00116|0.21701|0.00%|0.21693|0.00%|26.23 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32a45769d1)|0.21787|0.22130|0.00098|0.21919|1.00%|0.21924|1.07%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ac1b0c917)|0.21393|0.21728|0.00081|0.21535|-0.76%|0.21508|-0.86%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ac1b0c917)|0.07615|0.07966|0.00082|0.07721|-64.42%|0.07694|-64.53%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34013|1.36112|0.00538|1.35080|0.00%|1.35158|0.00%|20.49 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32a45769d1)|1.30936|1.33420|0.00620|1.31859|-2.38%|1.31863|-2.44%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ac1b0c917)|1.29408|1.31432|0.00499|1.30279|-3.55%|1.30310|-3.59%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ac1b0c917)|0.54741|0.56664|0.00446|0.55511|-58.91%|0.55467|-58.96%|21.83 MB|
