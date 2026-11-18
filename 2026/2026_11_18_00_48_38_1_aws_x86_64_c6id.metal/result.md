### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-11-18 00:48:38 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/44210722047 ([Artifacts](https://github.com/php/php-src/actions/runs/44210722047/artifacts/14387658819))|
| Changeset  |https://github.com/php/php-src/compare/4bc158b509..eb6f0ded68|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39471|0.39707|0.00068|0.17%|0.39541|0.00%|0.39513|0.00%|1.221|0.000|1.000|26.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4bc158b509)|0.37816|0.38046|0.00045|0.12%|0.37869|-4.23%|0.37858|-4.19%|2.655|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/eb6f0ded68)|0.37571|0.37697|0.00028|0.07%|0.37614|-4.87%|0.37607|-4.82%|1.290|8.614|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eb6f0ded68)|0.34889|0.34975|0.00020|0.06%|0.34925|-11.67%|0.34925|-11.61%|0.365|8.614|0.000|26.23 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67316|0.67855|0.00090|0.13%|0.67399|0.00%|0.67370|0.00%|3.109|0.000|1.000|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4bc158b509)|0.67696|0.67909|0.00044|0.07%|0.67754|0.53%|0.67740|0.55%|1.782|-8.283|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/eb6f0ded68)|0.67539|0.67860|0.00060|0.09%|0.67607|0.31%|0.67587|0.32%|2.380|-7.973|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eb6f0ded68)|0.64708|0.64876|0.00038|0.06%|0.64775|-3.89%|0.64773|-3.85%|0.302|8.614|0.000|26.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58815|0.59167|0.00078|0.13%|0.58958|0.00%|0.58957|0.00%|0.402|0.000|1.000|26.90 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4bc158b509)|0.58653|0.58943|0.00050|0.08%|0.58731|-0.39%|0.58721|-0.40%|2.382|8.386|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/eb6f0ded68)|0.58511|0.58912|0.00084|0.14%|0.58621|-0.57%|0.58599|-0.61%|1.689|8.517|0.000|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eb6f0ded68)|0.51204|0.51543|0.00087|0.17%|0.51329|-12.94%|0.51301|-12.99%|1.029|8.614|0.000|26.38 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44342|0.44673|0.00064|0.14%|0.44461|0.00%|0.44450|0.00%|1.035|0.000|1.000|26.90 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4bc158b509)|0.45250|0.45673|0.00070|0.15%|0.45414|2.14%|0.45400|2.14%|0.713|-8.614|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/eb6f0ded68)|0.45278|0.45549|0.00059|0.13%|0.45425|2.17%|0.45424|2.19%|-0.043|-8.614|0.000|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eb6f0ded68)|0.14505|0.14875|0.00064|0.44%|0.14564|-67.24%|0.14553|-67.26%|4.034|8.614|0.000|26.38 MB|
