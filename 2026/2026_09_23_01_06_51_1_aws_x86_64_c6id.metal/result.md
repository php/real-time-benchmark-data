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
| Time          |2026-09-23 01:06:51 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/35804923766 ([Artifacts](https://github.com/php/php-src/actions/runs/35804923766/artifacts/10728127971))|
| Changeset  |https://github.com/php/php-src/compare/934d4ff95f..10a2b0dae0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39504|0.39612|0.00018|0.04%|0.39536|0.00%|0.39533|0.00%|1.690|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/934d4ff95f)|0.37483|0.37814|0.00071|0.19%|0.37537|-5.05%|0.37513|-5.11%|2.469|8.614|0.000|25.68 MB|
|[PHP - master](https://github.com/php/php-src/commit/10a2b0dae0)|0.37387|0.37610|0.00036|0.10%|0.37425|-5.34%|0.37415|-5.36%|3.149|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10a2b0dae0)|0.35131|0.35300|0.00037|0.10%|0.35177|-11.02%|0.35170|-11.04%|1.560|8.614|0.000|26.22 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67464|0.67986|0.00082|0.12%|0.67644|0.00%|0.67639|0.00%|1.280|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/934d4ff95f)|0.66800|0.67036|0.00050|0.07%|0.66856|-1.16%|0.66842|-1.18%|1.557|8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/10a2b0dae0)|0.66914|0.67025|0.00026|0.04%|0.66962|-1.01%|0.66963|-1.00%|0.335|8.614|0.000|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10a2b0dae0)|0.63607|0.65487|0.00350|0.55%|0.63762|-5.74%|0.63677|-5.86%|4.021|8.614|0.000|26.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58625|0.58953|0.00073|0.12%|0.58797|0.00%|0.58805|0.00%|-0.171|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/934d4ff95f)|0.58925|0.59324|0.00079|0.13%|0.59054|0.44%|0.59043|0.40%|0.954|-8.579|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/10a2b0dae0)|0.58797|0.59372|0.00111|0.19%|0.58909|0.19%|0.58874|0.12%|2.457|-5.808|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10a2b0dae0)|0.51902|0.52274|0.00062|0.12%|0.51978|-11.60%|0.51964|-11.63%|2.923|8.614|0.000|26.27 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44386|0.44922|0.00081|0.18%|0.44469|0.00%|0.44455|0.00%|3.690|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/934d4ff95f)|0.45157|0.45504|0.00070|0.16%|0.45295|1.86%|0.45297|1.89%|0.391|-8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/10a2b0dae0)|0.45092|0.45497|0.00084|0.18%|0.45273|1.81%|0.45264|1.82%|0.375|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10a2b0dae0)|0.14456|0.14527|0.00016|0.11%|0.14488|-67.42%|0.14489|-67.41%|0.165|8.614|0.000|26.27 MB|
