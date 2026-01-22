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
| Time          |2026-01-22 00:50:27 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21231601015 ([Artifacts](#ARTIFACT_URL#))|
| Changeset  |https://github.com/php/php-src/compare/aeb8524584..65b4073922|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45283|0.46149|0.00087|0.19%|0.45439|0.00%|0.45444|0.00%|5.370|0.999|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aeb8524584)|0.44751|0.45516|0.00104|0.23%|0.44890|-1.21%|0.44878|-1.25%|4.065|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b4073922)|0.44789|0.45601|0.00085|0.19%|0.44906|-1.17%|0.44901|-1.20%|5.578|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b4073922)|0.42755|0.43464|0.00090|0.21%|0.42982|-5.41%|0.42986|-5.41%|1.025|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.76840|0.77908|0.00108|0.14%|0.77649|0.00%|0.77646|0.00%|-3.799|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aeb8524584)|0.76678|0.78554|0.00216|0.28%|0.77357|-0.38%|0.77319|-0.42%|3.510|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b4073922)|0.76538|0.77278|0.00136|0.18%|0.76919|-0.94%|0.76918|-0.94%|0.053|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b4073922)|0.90205|1.18326|0.03657|3.15%|1.16252|49.71%|1.17259|51.02%|-5.078|0.000|27.01 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65977|0.68138|0.00352|0.53%|0.66140|0.00%|0.66077|0.00%|5.414|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aeb8524584)|0.66520|0.68640|0.00278|0.42%|0.66675|0.81%|0.66636|0.84%|6.540|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b4073922)|0.66558|0.68669|0.00210|0.32%|0.66685|0.82%|0.66660|0.88%|8.671|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b4073922)|0.59294|0.59566|0.00056|0.09%|0.59386|-10.21%|0.59378|-10.14%|0.722|0.000|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42536|0.43451|0.00152|0.35%|0.42814|0.00%|0.42795|0.00%|1.238|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aeb8524584)|0.42336|0.42955|0.00123|0.29%|0.42617|-0.46%|0.42606|-0.44%|0.310|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b4073922)|0.42396|0.42962|0.00125|0.29%|0.42631|-0.43%|0.42610|-0.43%|0.521|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b4073922)|0.13826|0.14513|0.00124|0.88%|0.14050|-67.18%|0.14031|-67.21%|0.850|0.000|27.01 MB|
