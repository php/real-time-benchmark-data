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
| Time          |2026-11-27 00:48:13 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/45918810689 ([Artifacts](https://github.com/php/php-src/actions/runs/45918810689/artifacts/15165110686))|
| Changeset  |https://github.com/php/php-src/compare/7c1e712597..8ea2d41052|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39361|0.39585|0.00078|0.20%|0.39435|0.00%|0.39396|0.00%|0.969|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7c1e712597)|0.37338|0.37435|0.00019|0.05%|0.37372|-5.23%|0.37371|-5.14%|0.621|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/8ea2d41052)|0.37740|0.37892|0.00028|0.07%|0.37807|-4.13%|0.37803|-4.04%|0.553|8.614|0.000|25.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8ea2d41052)|0.34746|0.34850|0.00022|0.06%|0.34787|-11.79%|0.34784|-11.71%|0.836|8.614|0.000|26.37 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67158|0.68080|0.00131|0.20%|0.67239|0.00%|0.67210|0.00%|5.566|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7c1e712597)|0.68114|0.68603|0.00082|0.12%|0.68180|1.40%|0.68160|1.41%|3.695|-8.614|0.000|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/8ea2d41052)|0.67501|0.67755|0.00075|0.11%|0.67595|0.53%|0.67568|0.53%|1.005|-8.269|0.000|26.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8ea2d41052)|0.64411|0.64621|0.00036|0.06%|0.64458|-4.14%|0.64449|-4.11%|2.008|8.614|0.000|26.39 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58687|0.59078|0.00090|0.15%|0.58869|0.00%|0.58851|0.00%|0.576|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7c1e712597)|0.58245|0.58521|0.00063|0.11%|0.58321|-0.93%|0.58303|-0.93%|1.898|8.614|0.000|26.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/8ea2d41052)|0.58793|0.59554|0.00142|0.24%|0.58897|0.05%|0.58858|0.01%|3.768|-0.903|0.366|26.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8ea2d41052)|0.51415|0.52221|0.00117|0.23%|0.51485|-12.54%|0.51454|-12.57%|5.376|8.614|0.000|26.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44356|0.44614|0.00067|0.15%|0.44454|0.00%|0.44448|0.00%|0.516|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7c1e712597)|0.45526|0.45767|0.00056|0.12%|0.45670|2.74%|0.45677|2.76%|-0.576|-8.614|0.000|26.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/8ea2d41052)|0.45620|0.45860|0.00054|0.12%|0.45741|2.90%|0.45740|2.91%|0.043|-8.614|0.000|26.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8ea2d41052)|0.14831|0.15237|0.00097|0.65%|0.14886|-66.51%|0.14860|-66.57%|3.080|8.614|0.000|26.33 MB|
