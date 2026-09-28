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
| Time          |2026-09-28 01:16:58 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/36365369488 ([Artifacts](https://github.com/php/php-src/actions/runs/36365369488/artifacts/10947808431))|
| Changeset  |https://github.com/php/php-src/compare/c45a9f95f5..f5d89c8394|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39904|0.40017|0.00020|0.05%|0.39939|0.00%|0.39936|0.00%|1.420|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c45a9f95f5)|0.37733|0.37894|0.00037|0.10%|0.37780|-5.41%|0.37772|-5.42%|1.263|8.614|0.000|25.74 MB|
|[PHP - master](https://github.com/php/php-src/commit/f5d89c8394)|0.37868|0.38224|0.00068|0.18%|0.37932|-5.03%|0.37906|-5.08%|2.349|8.614|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f5d89c8394)|0.35633|0.35782|0.00030|0.09%|0.35689|-10.64%|0.35682|-10.65%|0.762|8.614|0.000|26.25 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67973|0.68309|0.00081|0.12%|0.68116|0.00%|0.68119|0.00%|0.153|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c45a9f95f5)|0.67613|0.67788|0.00030|0.04%|0.67658|-0.67%|0.67652|-0.69%|1.872|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/f5d89c8394)|0.67254|0.67450|0.00042|0.06%|0.67315|-1.18%|0.67302|-1.20%|1.183|8.614|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f5d89c8394)|0.63985|0.66076|0.00297|0.46%|0.64106|-5.89%|0.64052|-5.97%|6.259|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59093|0.59451|0.00086|0.14%|0.59246|0.00%|0.59223|0.00%|0.665|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c45a9f95f5)|0.59417|0.59689|0.00061|0.10%|0.59517|0.46%|0.59507|0.48%|0.809|-8.559|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/f5d89c8394)|0.59351|0.59786|0.00092|0.15%|0.59476|0.39%|0.59452|0.39%|1.907|-8.290|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f5d89c8394)|0.52286|0.52725|0.00086|0.16%|0.52396|-11.56%|0.52377|-11.56%|2.153|8.614|0.000|26.17 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44371|0.44580|0.00051|0.11%|0.44477|0.00%|0.44469|0.00%|0.021|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c45a9f95f5)|0.45184|0.45576|0.00079|0.17%|0.45343|1.95%|0.45338|1.95%|0.429|-8.614|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/f5d89c8394)|0.45155|0.45436|0.00061|0.13%|0.45284|1.81%|0.45294|1.85%|-0.097|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f5d89c8394)|0.14379|0.14498|0.00025|0.18%|0.14446|-67.52%|0.14447|-67.51%|0.047|8.614|0.000|26.17 MB|
