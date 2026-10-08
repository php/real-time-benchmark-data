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
| Time          |2026-10-08 01:16:25 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/37712063755 ([Artifacts](https://github.com/php/php-src/actions/runs/37712063755/artifacts/11523083010))|
| Changeset  |https://github.com/php/php-src/compare/fb6435df56..60702faf6a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39903|0.40090|0.00032|0.08%|0.39947|0.00%|0.39936|0.00%|2.276|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fb6435df56)|0.37916|0.38103|0.00045|0.12%|0.37994|-4.89%|0.37983|-4.89%|0.579|8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/60702faf6a)|0.37938|0.38072|0.00035|0.09%|0.37976|-4.94%|0.37966|-4.93%|1.623|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60702faf6a)|0.35556|0.35660|0.00024|0.07%|0.35589|-10.91%|0.35586|-10.89%|1.259|8.614|0.000|26.23 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68018|0.68487|0.00080|0.12%|0.68187|0.00%|0.68166|0.00%|1.306|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fb6435df56)|0.67372|0.67748|0.00057|0.08%|0.67430|-1.11%|0.67419|-1.10%|3.842|8.614|0.000|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/60702faf6a)|0.67614|0.68262|0.00092|0.14%|0.67681|-0.74%|0.67661|-0.74%|5.441|8.324|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60702faf6a)|0.64447|0.65149|0.00098|0.15%|0.64529|-5.36%|0.64512|-5.36%|5.302|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59024|0.59723|0.00108|0.18%|0.59223|0.00%|0.59211|0.00%|1.962|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fb6435df56)|0.59266|0.59677|0.00078|0.13%|0.59356|0.22%|0.59332|0.20%|2.583|-7.059|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/60702faf6a)|0.59311|0.59797|0.00093|0.16%|0.59426|0.34%|0.59394|0.31%|2.179|-8.052|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60702faf6a)|0.52021|0.52507|0.00088|0.17%|0.52167|-11.91%|0.52139|-11.94%|2.427|8.614|0.000|26.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44360|0.45196|0.00128|0.29%|0.44508|0.00%|0.44479|0.00%|3.788|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fb6435df56)|0.45135|0.45481|0.00074|0.16%|0.45285|1.74%|0.45287|1.82%|0.397|-8.572|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/60702faf6a)|0.45344|0.45649|0.00069|0.15%|0.45465|2.15%|0.45462|2.21%|0.232|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60702faf6a)|0.14381|0.14492|0.00023|0.16%|0.14433|-67.57%|0.14434|-67.55%|-0.224|8.614|0.000|26.21 MB|
