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
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2024-12-26 00:49:23 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43833|0.45308|0.00194|0.43999|0.00%|0.43970|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/48b37fe384)|0.43615|0.43905|0.00053|0.43696|-0.69%|0.43684|-0.65%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1c6520c4f)|0.43653|0.44387|0.00103|0.43752|-0.56%|0.43727|-0.55%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1c6520c4f)|0.42434|0.42572|0.00033|0.42497|-3.41%|0.42491|-3.36%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71262|0.71692|0.00081|0.71387|0.00%|0.71379|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/48b37fe384)|0.71066|0.71420|0.00082|0.71209|-0.25%|0.71192|-0.26%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1c6520c4f)|0.71011|0.71337|0.00068|0.71134|-0.35%|0.71127|-0.35%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1c6520c4f)|0.68276|0.68522|0.00058|0.68416|-4.16%|0.68414|-4.15%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58042|0.58374|0.00064|0.58213|0.00%|0.58215|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/48b37fe384)|0.57814|0.58165|0.00066|0.57914|-0.51%|0.57904|-0.53%|42.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1c6520c4f)|0.57459|0.58035|0.00102|0.57863|-0.60%|0.57856|-0.62%|42.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1c6520c4f)|0.52169|0.52411|0.00050|0.52291|-10.17%|0.52290|-10.18%|60.79 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21505|0.21834|0.00076|0.21634|0.00%|0.21617|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/48b37fe384)|0.21578|0.22139|0.00107|0.21753|0.55%|0.21728|0.51%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1c6520c4f)|0.21540|0.22091|0.00120|0.21722|0.41%|0.21690|0.34%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1c6520c4f)|0.07400|0.07781|0.00088|0.07577|-64.98%|0.07563|-65.02%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34484|1.37006|0.00568|1.35377|0.00%|1.35394|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/48b37fe384)|1.33626|1.36093|0.00470|1.35265|-0.08%|1.35287|-0.08%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1c6520c4f)|1.33841|1.36483|0.00537|1.35235|-0.10%|1.35301|-0.07%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1c6520c4f)|0.52954|0.54544|0.00353|0.53754|-60.29%|0.53717|-60.33%|21.65 MB|
