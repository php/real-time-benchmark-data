### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.12.66-88.122.amzn2023.x86_64|
| OS            |Amazon Linux 2023.10.20260202|
| GCC           |14.2.1|
| Time          |2026-03-06 00:57:27 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22743920616 ([Artifacts](https://github.com/php/php-src/actions/runs/22743920616/artifacts/5790397928))|
| Changeset  |https://github.com/php/php-src/compare/11a95749b1..77925b971a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39440|0.39569|0.00024|0.06%|0.39475|0.00%|0.39470|0.00%|1.724|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/11a95749b1)|0.38816|0.38961|0.00029|0.07%|0.38864|-1.55%|0.38860|-1.55%|1.035|8.614|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/77925b971a)|0.38849|0.38963|0.00027|0.07%|0.38888|-1.49%|0.38883|-1.49%|1.176|8.614|0.000|25.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/77925b971a)|0.36065|0.36400|0.00057|0.16%|0.36122|-8.50%|0.36107|-8.52%|3.152|8.614|0.000|25.28 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66605|0.67194|0.00118|0.18%|0.66703|0.00%|0.66656|0.00%|3.020|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/11a95749b1)|0.66343|0.66969|0.00101|0.15%|0.66422|-0.42%|0.66393|-0.40%|3.990|8.028|0.000|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/77925b971a)|0.66337|0.66502|0.00042|0.06%|0.66402|-0.45%|0.66394|-0.39%|0.746|8.614|0.000|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/77925b971a)|0.63138|0.63699|0.00086|0.14%|0.63206|-5.24%|0.63183|-5.21%|4.269|8.614|0.000|25.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58731|0.59272|0.00107|0.18%|0.58974|0.00%|0.58960|0.00%|0.348|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/11a95749b1)|0.58537|0.58858|0.00075|0.13%|0.58605|-0.63%|0.58583|-0.64%|2.635|8.504|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/77925b971a)|0.58529|0.58930|0.00086|0.15%|0.58620|-0.60%|0.58592|-0.62%|2.460|8.338|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/77925b971a)|0.51501|0.51690|0.00035|0.07%|0.51559|-12.57%|0.51560|-12.55%|1.244|8.614|0.000|25.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44140|0.44389|0.00058|0.13%|0.44273|0.00%|0.44283|0.00%|-0.292|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/11a95749b1)|0.44466|0.44698|0.00052|0.12%|0.44586|0.71%|0.44585|0.68%|-0.181|-8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/77925b971a)|0.44476|0.44839|0.00057|0.13%|0.44585|0.71%|0.44577|0.66%|1.718|-8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/77925b971a)|0.14330|0.14475|0.00026|0.18%|0.14382|-67.52%|0.14376|-67.54%|1.444|8.614|0.000|25.64 MB|
