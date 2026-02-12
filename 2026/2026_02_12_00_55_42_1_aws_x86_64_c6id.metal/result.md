### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-02-12 00:55:42 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21929233747 ([Artifacts](https://github.com/php/php-src/actions/runs/21929233747/artifacts/5475860129))|
| Changeset  |https://github.com/php/php-src/compare/defc0bec2e..7134e69ab2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39790|0.39909|0.00022|0.05%|0.39827|0.00%|0.39824|0.00%|1.232|0.000|1.000|26.59 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/defc0bec2e)|0.39409|0.39582|0.00041|0.10%|0.39454|-0.93%|0.39444|-0.95%|1.401|8.614|0.000|25.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/7134e69ab2)|0.39177|0.39333|0.00032|0.08%|0.39215|-1.53%|0.39206|-1.55%|2.156|8.614|0.000|25.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7134e69ab2)|0.36380|0.36634|0.00041|0.11%|0.36420|-8.55%|0.36408|-8.58%|3.298|8.614|0.000|25.58 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68043|0.68347|0.00067|0.10%|0.68116|0.00%|0.68091|0.00%|1.441|0.000|1.000|26.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/defc0bec2e)|0.68007|0.68357|0.00061|0.09%|0.68065|-0.07%|0.68047|-0.06%|2.927|5.077|0.000|25.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/7134e69ab2)|0.68156|0.68321|0.00039|0.06%|0.68239|0.18%|0.68243|0.22%|0.063|-7.214|0.000|25.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7134e69ab2)|0.65079|0.65599|0.00085|0.13%|0.65177|-4.32%|0.65156|-4.31%|3.120|8.614|0.000|25.66 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58892|0.59383|0.00103|0.17%|0.59192|0.00%|0.59188|0.00%|-0.338|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/defc0bec2e)|0.59081|0.59499|0.00075|0.13%|0.59162|-0.05%|0.59146|-0.07%|3.524|2.633|0.008|25.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/7134e69ab2)|0.58921|0.59366|0.00063|0.11%|0.59005|-0.32%|0.58996|-0.32%|4.014|7.566|0.000|25.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7134e69ab2)|0.52018|0.52881|0.00115|0.22%|0.52133|-11.93%|0.52116|-11.95%|5.732|8.614|0.000|25.76 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44145|0.44693|0.00087|0.20%|0.44264|0.00%|0.44246|0.00%|2.543|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/defc0bec2e)|0.44318|0.44585|0.00056|0.13%|0.44471|0.47%|0.44476|0.52%|-0.571|-8.104|0.000|25.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/7134e69ab2)|0.44336|0.44575|0.00058|0.13%|0.44453|0.43%|0.44456|0.47%|-0.244|-8.042|0.000|25.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7134e69ab2)|0.14314|0.14416|0.00022|0.15%|0.14355|-67.57%|0.14353|-67.56%|0.936|8.614|0.000|25.76 MB|
