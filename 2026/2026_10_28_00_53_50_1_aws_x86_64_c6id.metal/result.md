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
| Time          |2026-10-28 00:53:50 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/40611626275 ([Artifacts](https://github.com/php/php-src/actions/runs/40611626275/artifacts/12784818181))|
| Changeset  |https://github.com/php/php-src/compare/3b8e98882e..780f4e8217|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39908|0.40072|0.00027|0.07%|0.39938|0.00%|0.39933|0.00%|2.833|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3b8e98882e)|0.38294|0.38407|0.00026|0.07%|0.38333|-4.02%|0.38332|-4.01%|0.688|8.614|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/780f4e8217)|0.38224|0.38494|0.00053|0.14%|0.38277|-4.16%|0.38261|-4.19%|2.255|8.614|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/780f4e8217)|0.35829|0.35971|0.00035|0.10%|0.35882|-10.16%|0.35877|-10.16%|1.032|8.614|0.000|26.34 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67921|0.68626|0.00109|0.16%|0.68005|0.00%|0.67971|0.00%|4.093|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3b8e98882e)|0.68396|0.68672|0.00056|0.08%|0.68456|0.66%|0.68441|0.69%|2.150|-8.283|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/780f4e8217)|0.68690|0.68896|0.00042|0.06%|0.68757|1.11%|0.68750|1.15%|0.921|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/780f4e8217)|0.66500|0.66770|0.00051|0.08%|0.66584|-2.09%|0.66572|-2.06%|1.353|8.614|0.000|26.37 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59265|0.59658|0.00092|0.15%|0.59415|0.00%|0.59405|0.00%|0.618|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3b8e98882e)|0.59595|0.59940|0.00069|0.12%|0.59671|0.43%|0.59661|0.43%|2.349|-8.390|0.000|26.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/780f4e8217)|0.59679|0.60052|0.00072|0.12%|0.59755|0.57%|0.59735|0.56%|2.558|-8.614|0.000|26.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/780f4e8217)|0.52440|0.52776|0.00056|0.11%|0.52490|-11.66%|0.52478|-11.66%|3.579|8.614|0.000|26.46 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44324|0.44875|0.00084|0.19%|0.44495|0.00%|0.44490|0.00%|1.850|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3b8e98882e)|0.45214|0.45451|0.00053|0.12%|0.45352|1.93%|0.45348|1.93%|-0.134|-8.614|0.000|26.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/780f4e8217)|0.45173|0.45408|0.00058|0.13%|0.45317|1.85%|0.45325|1.87%|-0.505|-8.614|0.000|26.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/780f4e8217)|0.14392|0.14792|0.00065|0.45%|0.14459|-67.50%|0.14447|-67.53%|3.367|8.614|0.000|26.46 MB|
