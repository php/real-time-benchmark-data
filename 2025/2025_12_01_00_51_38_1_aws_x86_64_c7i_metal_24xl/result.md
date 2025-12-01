### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2025-12-01 00:51:38 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47497|0.47741|0.00056|0.12%|0.47592|0.00%|0.47585|0.00%|0.819|0.999|180943634|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/71d11bdb16)|0.46936|0.47554|0.00090|0.19%|0.47100|-1.03%|0.47079|-1.06%|2.073|0.000|176334977|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/1848bcddfd)|0.46901|0.47440|0.00104|0.22%|0.47033|-1.17%|0.47004|-1.22%|2.169|0.000|176406456|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1848bcddfd)|0.44934|0.45366|0.00053|0.12%|0.45257|-4.91%|0.45254|-4.90%|-2.117|0.000|147887265|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74205|0.74555|0.00069|0.09%|0.74333|0.00%|0.74328|0.00%|0.785|0.999|291621072|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/71d11bdb16)|0.74201|0.75078|0.00123|0.17%|0.74392|0.08%|0.74375|0.06%|2.281|0.000|290398152|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/1848bcddfd)|0.73925|0.74988|0.00161|0.22%|0.74147|-0.25%|0.74108|-0.30%|2.360|0.000|290398662|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1848bcddfd)|0.71446|0.72043|0.00081|0.11%|0.71623|-3.65%|0.71607|-3.66%|1.461|0.000|270760980|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57987|0.58760|0.00249|0.43%|0.58272|0.00%|0.58135|0.00%|0.581|0.999|1123348213|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/71d11bdb16)|0.57853|0.59333|0.00278|0.48%|0.58173|-0.17%|0.58024|-0.19%|1.236|0.000|1119625091|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/1848bcddfd)|0.58018|0.59583|0.00266|0.46%|0.58324|0.09%|0.58194|0.10%|1.379|0.011|1119634726|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1848bcddfd)|0.51669|0.52299|0.00223|0.43%|0.51910|-10.92%|0.51772|-10.94%|0.585|0.000|865685421|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42825|0.44109|0.00251|0.58%|0.43444|0.00%|0.43382|0.00%|0.355|0.999|2020638125|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/71d11bdb16)|0.42349|0.43586|0.00221|0.52%|0.42731|-1.64%|0.42686|-1.61%|1.736|0.000|2020586678|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/1848bcddfd)|0.42289|0.47795|0.00589|1.38%|0.42799|-1.49%|0.42642|-1.71%|6.464|0.000|2020586605|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1848bcddfd)|0.14642|0.15301|0.00105|0.71%|0.14864|-65.79%|0.14845|-65.78%|1.256|0.000|536605653|27.81 MB|
