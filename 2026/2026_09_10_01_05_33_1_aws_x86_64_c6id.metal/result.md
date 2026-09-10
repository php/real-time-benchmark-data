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
| Binary layout strategy |none|
| Time          |2026-09-10 01:05:33 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/34424030918 ([Artifacts](https://github.com/php/php-src/actions/runs/34424030918/artifacts/10132681058))|
| Changeset  |https://github.com/php/php-src/compare/82a15338e2..89687719b4|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39565|0.39687|0.00019|0.05%|0.39596|0.00%|0.39596|0.00%|2.112|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/82a15338e2)|0.36964|0.37050|0.00021|0.06%|0.37001|-6.55%|0.36998|-6.56%|0.561|8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/89687719b4)|0.37144|0.37452|0.00046|0.12%|0.37192|-6.07%|0.37183|-6.09%|4.154|8.614|0.000|25.87 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67526|0.67912|0.00088|0.13%|0.67666|0.00%|0.67639|0.00%|0.746|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/82a15338e2)|0.66378|0.66980|0.00103|0.15%|0.66465|-1.77%|0.66440|-1.77%|3.957|8.614|0.000|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/89687719b4)|0.66525|0.66726|0.00042|0.06%|0.66599|-1.58%|0.66586|-1.56%|1.388|8.614|0.000|26.19 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58728|0.59120|0.00081|0.14%|0.58872|0.00%|0.58876|0.00%|0.616|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/82a15338e2)|0.58790|0.59180|0.00088|0.15%|0.58919|0.08%|0.58894|0.03%|1.249|-2.454|0.014|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/89687719b4)|0.58934|0.59300|0.00073|0.12%|0.59021|0.25%|0.58999|0.21%|2.152|-7.418|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44353|0.44577|0.00054|0.12%|0.44453|0.00%|0.44450|0.00%|0.380|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/82a15338e2)|0.45063|0.45316|0.00049|0.11%|0.45157|1.58%|0.45152|1.58%|0.438|-8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/89687719b4)|0.44986|0.45415|0.00076|0.17%|0.45117|1.49%|0.45103|1.47%|1.549|-8.614|0.000|26.23 MB|
