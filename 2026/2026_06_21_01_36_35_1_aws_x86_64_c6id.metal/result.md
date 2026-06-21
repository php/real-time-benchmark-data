### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-06-21 01:36:35 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27889842192 ([Artifacts](https://github.com/php/php-src/actions/runs/27889842192/artifacts/7771021478))|
| Changeset  |https://github.com/php/php-src/compare/4d559cad69..0fff3ccce2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39453|0.39547|0.00021|0.05%|0.39485|0.00%|0.39484|0.00%|1.056|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d559cad69)|0.38506|0.38667|0.00034|0.09%|0.38560|-2.34%|0.38552|-2.36%|1.287|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/0fff3ccce2)|0.38867|0.39063|0.00042|0.11%|0.38923|-1.42%|0.38914|-1.44%|1.637|8.614|0.000|25.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0fff3ccce2)|0.36160|0.36314|0.00038|0.10%|0.36222|-8.27%|0.36220|-8.27%|0.424|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67231|0.67499|0.00054|0.08%|0.67301|0.00%|0.67290|0.00%|1.372|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d559cad69)|0.66362|0.67268|0.00135|0.20%|0.66465|-1.24%|0.66423|-1.29%|4.519|8.524|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/0fff3ccce2)|0.66472|0.66850|0.00071|0.11%|0.66541|-1.13%|0.66517|-1.15%|2.294|8.614|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0fff3ccce2)|0.63799|0.64157|0.00061|0.10%|0.63895|-5.06%|0.63887|-5.06%|1.839|8.614|0.000|26.28 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58864|0.59395|0.00103|0.17%|0.59026|0.00%|0.59018|0.00%|1.004|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d559cad69)|0.58440|0.58755|0.00069|0.12%|0.58538|-0.83%|0.58525|-0.84%|1.237|8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/0fff3ccce2)|0.58663|0.59399|0.00129|0.22%|0.58743|-0.48%|0.58705|-0.53%|3.383|7.759|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0fff3ccce2)|0.51671|0.52073|0.00088|0.17%|0.51761|-12.31%|0.51742|-12.33%|2.315|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44308|0.44663|0.00070|0.16%|0.44448|0.00%|0.44458|0.00%|0.310|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d559cad69)|0.44891|0.45190|0.00065|0.14%|0.45043|1.34%|0.45050|1.33%|-0.448|-8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/0fff3ccce2)|0.44948|0.45259|0.00061|0.14%|0.45061|1.38%|0.45055|1.34%|0.685|-8.614|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0fff3ccce2)|0.14399|0.14799|0.00053|0.36%|0.14463|-67.46%|0.14458|-67.48%|5.499|8.614|0.000|26.24 MB|
