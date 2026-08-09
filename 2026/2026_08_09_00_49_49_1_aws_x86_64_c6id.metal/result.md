### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Time          |2026-08-09 00:49:49 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/31286978973 ([Artifacts](https://github.com/php/php-src/actions/runs/31286978973/artifacts/9030714592))|
| Changeset  |https://github.com/php/php-src/compare/bf5141c5e6..b9b44872d7|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39650|0.39732|0.00016|0.04%|0.39683|0.00%|0.39681|0.00%|0.718|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf5141c5e6)|0.38562|0.38730|0.00030|0.08%|0.38613|-2.70%|0.38607|-2.71%|1.988|8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9b44872d7)|0.38624|0.39162|0.00086|0.22%|0.38681|-2.52%|0.38654|-2.59%|4.034|8.614|0.000|25.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9b44872d7)|0.36000|0.36132|0.00030|0.08%|0.36045|-9.17%|0.36040|-9.18%|1.381|8.614|0.000|25.79 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66981|0.68307|0.00156|0.23%|0.67597|0.00%|0.67592|0.00%|0.760|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf5141c5e6)|0.66739|0.67272|0.00124|0.19%|0.66841|-1.12%|0.66793|-1.18%|2.457|8.579|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9b44872d7)|0.66834|0.68084|0.00180|0.27%|0.66927|-0.99%|0.66883|-1.05%|5.755|8.248|0.000|25.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9b44872d7)|0.64308|0.64980|0.00095|0.15%|0.64384|-4.75%|0.64363|-4.78%|5.226|8.614|0.000|25.93 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58839|0.59223|0.00099|0.17%|0.59007|0.00%|0.59007|0.00%|0.172|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf5141c5e6)|0.58623|0.59414|0.00135|0.23%|0.58734|-0.46%|0.58694|-0.53%|3.353|7.662|0.000|26.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9b44872d7)|0.58574|0.58958|0.00088|0.15%|0.58671|-0.57%|0.58642|-0.62%|2.248|8.214|0.000|26.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9b44872d7)|0.51588|0.51932|0.00051|0.10%|0.51652|-12.46%|0.51645|-12.48%|3.460|8.614|0.000|26.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44342|0.44552|0.00047|0.11%|0.44451|0.00%|0.44448|0.00%|-0.115|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf5141c5e6)|0.44953|0.45309|0.00056|0.12%|0.45059|1.37%|0.45056|1.37%|2.006|-8.614|0.000|26.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9b44872d7)|0.44985|0.45243|0.00059|0.13%|0.45082|1.42%|0.45072|1.40%|0.816|-8.614|0.000|26.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9b44872d7)|0.14401|0.14491|0.00022|0.15%|0.14448|-67.50%|0.14447|-67.50%|-0.101|8.614|0.000|26.35 MB|
