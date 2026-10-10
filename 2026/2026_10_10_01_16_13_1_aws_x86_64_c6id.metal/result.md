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
| Time          |2026-10-10 01:16:13 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/38012485262 ([Artifacts](https://github.com/php/php-src/actions/runs/38012485262/artifacts/11655244551))|
| Changeset  |https://github.com/php/php-src/compare/c79284711b..4561d52aaf|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39620|0.39802|0.00029|0.07%|0.39669|0.00%|0.39664|0.00%|1.819|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c79284711b)|0.37654|0.37840|0.00032|0.09%|0.37701|-4.96%|0.37693|-4.97%|2.130|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/4561d52aaf)|0.37668|0.37831|0.00042|0.11%|0.37717|-4.92%|0.37705|-4.94%|1.628|8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4561d52aaf)|0.35215|0.35416|0.00033|0.09%|0.35291|-11.03%|0.35289|-11.03%|1.047|8.614|0.000|26.18 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67683|0.68059|0.00092|0.14%|0.67846|0.00%|0.67827|0.00%|0.577|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c79284711b)|0.67341|0.67811|0.00079|0.12%|0.67428|-0.62%|0.67406|-0.62%|2.758|8.462|0.000|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/4561d52aaf)|0.67290|0.68025|0.00110|0.16%|0.67399|-0.66%|0.67381|-0.66%|4.098|8.290|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4561d52aaf)|0.63808|0.64712|0.00138|0.22%|0.63919|-5.79%|0.63889|-5.81%|4.431|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58819|0.59162|0.00087|0.15%|0.58956|0.00%|0.58930|0.00%|0.550|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c79284711b)|0.59109|0.59919|0.00126|0.21%|0.59245|0.49%|0.59222|0.50%|3.485|-8.504|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/4561d52aaf)|0.59309|0.59811|0.00080|0.13%|0.59401|0.75%|0.59375|0.76%|3.068|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4561d52aaf)|0.51578|0.51873|0.00051|0.10%|0.51659|-12.38%|0.51655|-12.35%|1.583|8.614|0.000|26.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44355|0.44900|0.00079|0.18%|0.44479|0.00%|0.44471|0.00%|3.008|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c79284711b)|0.45077|0.45445|0.00081|0.18%|0.45261|1.76%|0.45268|1.79%|-0.204|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/4561d52aaf)|0.45244|0.45528|0.00060|0.13%|0.45367|2.00%|0.45365|2.01%|0.353|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4561d52aaf)|0.14373|0.14473|0.00023|0.16%|0.14422|-67.58%|0.14422|-67.57%|-0.274|8.614|0.000|26.21 MB|
