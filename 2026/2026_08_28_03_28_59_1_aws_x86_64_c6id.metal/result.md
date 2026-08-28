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
| Time          |2026-08-28 03:28:59 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33138995336 ([Artifacts](https://github.com/php/php-src/actions/runs/33138995336/artifacts/9673720664))|
| Changeset  |https://github.com/php/php-src/compare/53c3116c38..f16b1d5d25|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39529|0.39733|0.00031|0.08%|0.39568|0.00%|0.39564|0.00%|3.372|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/53c3116c38)|0.36866|0.37024|0.00032|0.09%|0.36908|-6.72%|0.36899|-6.74%|1.728|8.614|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/f16b1d5d25)|0.37062|0.37409|0.00066|0.18%|0.37134|-6.15%|0.37112|-6.20%|2.261|8.614|0.000|25.87 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67466|0.67808|0.00078|0.12%|0.67605|0.00%|0.67586|0.00%|0.716|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/53c3116c38)|0.66524|0.66983|0.00084|0.13%|0.66618|-1.46%|0.66596|-1.47%|2.536|8.614|0.000|25.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/f16b1d5d25)|0.66503|0.67627|0.00171|0.26%|0.66609|-1.47%|0.66565|-1.51%|4.874|8.379|0.000|25.89 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58692|0.59107|0.00099|0.17%|0.58843|0.00%|0.58828|0.00%|0.838|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/53c3116c38)|0.58577|0.58984|0.00080|0.14%|0.58652|-0.32%|0.58637|-0.32%|2.869|7.773|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/f16b1d5d25)|0.58730|0.59318|0.00132|0.23%|0.58852|0.02%|0.58822|-0.01%|2.285|0.252|0.801|26.25 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44302|0.44585|0.00058|0.13%|0.44456|0.00%|0.44460|0.00%|-0.238|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/53c3116c38)|0.44959|0.45283|0.00067|0.15%|0.45136|1.53%|0.45135|1.52%|-0.259|-8.614|0.000|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/f16b1d5d25)|0.45040|0.45403|0.00078|0.17%|0.45165|1.59%|0.45166|1.59%|0.941|-8.614|0.000|26.20 MB|
