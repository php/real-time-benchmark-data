### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-26 00:50:36 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21342662716 ([Artifacts](https://github.com/php/php-src/actions/runs/21342662716/artifacts/5251830497))|
| Changeset  |https://github.com/php/php-src/compare/5f367b8a01..9f774e3a85|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45353|0.46169|0.00105|0.23%|0.45450|0.00%|0.45437|0.00%|5.821|0.001|0.999|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5f367b8a01)|0.44878|0.45079|0.00036|0.08%|0.44953|-1.09%|0.44947|-1.08%|0.897|12.216|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/9f774e3a85)|0.44887|0.45633|0.00101|0.22%|0.44969|-1.06%|0.44951|-1.07%|5.353|11.737|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9f774e3a85)|0.42895|0.43295|0.00043|0.10%|0.43170|-5.02%|0.43165|-5.00%|-2.058|12.216|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.77410|0.78947|0.00196|0.25%|0.77593|0.00%|0.77558|0.00%|5.874|0.001|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5f367b8a01)|0.77278|0.78540|0.00137|0.18%|0.77474|-0.15%|0.77456|-0.13%|4.894|8.383|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/9f774e3a85)|0.76246|0.78141|0.00232|0.30%|0.77004|-0.76%|0.76993|-0.73%|1.374|11.656|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9f774e3a85)|1.10024|1.17462|0.01361|1.17%|1.15998|49.50%|1.16406|50.09%|-2.000|-12.216|0.000|27.01 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65875|0.67950|0.00202|0.31%|0.65998|0.00%|0.65979|0.00%|9.330|0.001|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5f367b8a01)|0.66517|0.68496|0.00264|0.40%|0.66662|1.01%|0.66623|0.98%|6.694|-11.976|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/9f774e3a85)|0.66564|0.68588|0.00271|0.41%|0.66691|1.05%|0.66646|1.01%|6.669|-11.976|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9f774e3a85)|0.59231|0.59415|0.00036|0.06%|0.59325|-10.11%|0.59324|-10.09%|0.304|12.216|0.000|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42456|0.43660|0.00163|0.38%|0.42837|0.00%|0.42837|0.00%|1.496|0.001|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5f367b8a01)|0.42281|0.44396|0.00220|0.52%|0.42662|-0.41%|0.42639|-0.46%|5.016|7.996|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/9f774e3a85)|0.42415|0.43062|0.00128|0.30%|0.42655|-0.42%|0.42644|-0.45%|0.538|7.985|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9f774e3a85)|0.13785|0.14509|0.00147|1.05%|0.14067|-67.16%|0.14040|-67.22%|0.563|12.216|0.000|27.01 MB|
