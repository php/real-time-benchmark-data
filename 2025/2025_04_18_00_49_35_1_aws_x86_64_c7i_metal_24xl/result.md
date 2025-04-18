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
| Time          |2025-04-18 00:49:35 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43785|0.44004|0.00049|0.43888|0.00%|0.43883|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87499e44f2)|0.43593|0.43760|0.00046|0.43659|-0.52%|0.43649|-0.53%|41.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|0.43706|0.43980|0.00059|0.43778|-0.25%|0.43768|-0.26%|41.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.42265|0.42411|0.00029|0.42354|-3.50%|0.42351|-3.49%|50.85 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71444|0.73043|0.00276|0.71648|0.00%|0.71582|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87499e44f2)|0.70839|0.71129|0.00066|0.70977|-0.94%|0.70966|-0.86%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|0.70367|0.71105|0.00122|0.70963|-0.96%|0.70973|-0.85%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.67953|0.68214|0.00067|0.68062|-5.01%|0.68046|-4.94%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58166|0.58460|0.00073|0.58249|0.00%|0.58224|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87499e44f2)|0.58116|0.58353|0.00057|0.58197|-0.09%|0.58181|-0.07%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|0.57836|0.58083|0.00056|0.57957|-0.50%|0.57948|-0.47%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.52029|0.52224|0.00056|0.52105|-10.55%|0.52092|-10.53%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21579|0.21920|0.00090|0.21708|0.00%|0.21694|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87499e44f2)|0.25722|0.28179|0.00603|0.27110|24.88%|0.27076|24.81%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|0.21603|0.22026|0.00098|0.21810|0.47%|0.21807|0.52%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.07537|0.07917|0.00100|0.07703|-64.52%|0.07681|-64.59%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34312|1.36493|0.00560|1.35061|0.00%|1.34924|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87499e44f2)|1.30349|1.32422|0.00532|1.31420|-2.70%|1.31429|-2.59%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|1.33576|1.35115|0.00417|1.34120|-0.70%|1.34048|-0.65%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.56633|0.58045|0.00328|0.57371|-57.52%|0.57355|-57.49%|21.82 MB|
