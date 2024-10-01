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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20240916|
| GCC           |11.4.1|
| Time          |2024-10-01 00:49:37 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43782|0.45176|0.00239|0.43915|0.00%|0.43880|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bca73f1c69)|0.43789|0.43980|0.00043|0.43879|-0.08%|0.43884|0.01%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/a6d111ff2a)|0.43883|0.44100|0.00053|0.43958|0.10%|0.43941|0.14%|41.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a6d111ff2a)|0.43790|0.44176|0.00066|0.43904|-0.02%|0.43899|0.04%|41.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71452|0.71805|0.00078|0.71575|0.00%|0.71564|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bca73f1c69)|0.71457|0.71786|0.00077|0.71584|0.01%|0.71571|0.01%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/a6d111ff2a)|0.70655|0.73281|0.00360|0.71581|0.01%|0.71549|-0.02%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a6d111ff2a)|0.71483|0.72415|0.00177|0.71639|0.09%|0.71582|0.03%|37.38 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58014|0.58297|0.00068|0.58153|0.00%|0.58155|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bca73f1c69)|0.57810|0.58051|0.00051|0.57887|-0.46%|0.57878|-0.48%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/a6d111ff2a)|0.57768|0.58035|0.00063|0.57874|-0.48%|0.57868|-0.49%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a6d111ff2a)|0.57718|0.57923|0.00051|0.57845|-0.53%|0.57853|-0.52%|42.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21462|0.21777|0.00076|0.21585|0.00%|0.21563|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bca73f1c69)|0.21478|0.21816|0.00087|0.21646|0.29%|0.21643|0.37%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/a6d111ff2a)|0.21202|0.21862|0.00134|0.21394|-0.88%|0.21359|-0.95%|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a6d111ff2a)|0.21175|0.21610|0.00104|0.21364|-1.02%|0.21339|-1.04%|26.17 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34229|1.36281|0.00502|1.35294|0.00%|1.35371|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bca73f1c69)|1.41863|1.44519|0.00631|1.42937|5.65%|1.42702|5.42%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/a6d111ff2a)|1.35772|1.37709|0.00518|1.36877|1.17%|1.36936|1.16%|20.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a6d111ff2a)|1.35861|1.38905|0.00591|1.37041|1.29%|1.36948|1.16%|20.42 MB|
