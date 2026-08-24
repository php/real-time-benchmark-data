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
| Time          |2026-08-24 00:48:48 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/32677807139 ([Artifacts](https://github.com/php/php-src/actions/runs/32677807139/artifacts/9503653266))|
| Changeset  |https://github.com/php/php-src/compare/d779512be4..c96900ee74|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39896|0.40004|0.00020|0.05%|0.39929|0.00%|0.39926|0.00%|1.407|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d779512be4)|0.37375|0.37579|0.00038|0.10%|0.37423|-6.28%|0.37415|-6.29%|2.261|8.614|0.000|25.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/c96900ee74)|0.37399|0.37533|0.00034|0.09%|0.37442|-6.23%|0.37434|-6.24%|1.326|8.614|0.000|25.69 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67972|0.68252|0.00065|0.10%|0.68103|0.00%|0.68097|0.00%|0.263|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d779512be4)|0.67174|0.67429|0.00043|0.06%|0.67248|-1.25%|0.67243|-1.25%|1.590|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/c96900ee74)|0.67191|0.67313|0.00032|0.05%|0.67244|-1.26%|0.67243|-1.25%|0.277|8.614|0.000|25.76 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59068|0.59649|0.00106|0.18%|0.59253|0.00%|0.59243|0.00%|1.171|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d779512be4)|0.59017|0.59799|0.00144|0.24%|0.59176|-0.13%|0.59155|-0.15%|3.259|4.667|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/c96900ee74)|0.59038|0.59371|0.00071|0.12%|0.59117|-0.23%|0.59102|-0.24%|1.716|6.659|0.000|25.87 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44367|0.44834|0.00074|0.17%|0.44482|0.00%|0.44468|0.00%|2.237|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d779512be4)|0.45089|0.45391|0.00064|0.14%|0.45216|1.65%|0.45212|1.67%|0.367|-8.614|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/c96900ee74)|0.45045|0.45497|0.00094|0.21%|0.45221|1.66%|0.45210|1.67%|0.623|-8.614|0.000|25.87 MB|
