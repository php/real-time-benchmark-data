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
| Time          |2026-09-22 01:07:04 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/35674554548 ([Artifacts](https://github.com/php/php-src/actions/runs/35674554548/artifacts/10672937457))|
| Changeset  |https://github.com/php/php-src/compare/1f1d223bc0..934d4ff95f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39904|0.40113|0.00039|0.10%|0.39949|0.00%|0.39935|0.00%|2.433|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1f1d223bc0)|0.37569|0.37769|0.00039|0.10%|0.37630|-5.80%|0.37622|-5.79%|1.532|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/934d4ff95f)|0.37884|0.38260|0.00061|0.16%|0.37944|-5.02%|0.37925|-5.03%|3.221|8.614|0.000|25.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/934d4ff95f)|0.35703|0.35846|0.00027|0.08%|0.35753|-10.50%|0.35751|-10.48%|0.993|8.614|0.000|26.22 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68018|0.68611|0.00108|0.16%|0.68173|0.00%|0.68161|0.00%|1.698|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1f1d223bc0)|0.66929|0.67305|0.00065|0.10%|0.67002|-1.72%|0.66984|-1.73%|2.925|8.614|0.000|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/934d4ff95f)|0.67348|0.67585|0.00052|0.08%|0.67436|-1.08%|0.67426|-1.08%|1.332|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/934d4ff95f)|0.64048|0.65979|0.00349|0.54%|0.64189|-5.84%|0.64112|-5.94%|4.690|8.614|0.000|26.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59073|0.59515|0.00088|0.15%|0.59250|0.00%|0.59249|0.00%|0.403|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1f1d223bc0)|0.58862|0.59668|0.00130|0.22%|0.59000|-0.42%|0.58963|-0.48%|3.232|7.711|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/934d4ff95f)|0.59281|0.59748|0.00097|0.16%|0.59428|0.30%|0.59415|0.28%|1.296|-7.487|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/934d4ff95f)|0.52279|0.52695|0.00095|0.18%|0.52394|-11.57%|0.52376|-11.60%|1.929|8.614|0.000|26.26 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44331|0.44632|0.00059|0.13%|0.44460|0.00%|0.44449|0.00%|0.701|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1f1d223bc0)|0.45088|0.45375|0.00058|0.13%|0.45217|1.70%|0.45217|1.73%|0.376|-8.614|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/934d4ff95f)|0.45114|0.45432|0.00068|0.15%|0.45300|1.89%|0.45295|1.90%|-0.023|-8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/934d4ff95f)|0.14454|0.14537|0.00021|0.14%|0.14497|-67.39%|0.14496|-67.39%|0.023|8.614|0.000|26.26 MB|
