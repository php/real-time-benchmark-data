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
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250818|
| GCC           |14.2.1|
| Time          |2025-10-01 00:50:42 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47641|0.48074|0.00065|0.14%|0.47835|0.00%|0.47829|0.00%|0.589|0.999|180947912|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96aa0e08a1)|0.47203|0.47603|0.00065|0.14%|0.47297|-1.13%|0.47288|-1.13%|1.671|0.000|176332556|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/a3f0861f2e)|0.47080|0.47418|0.00068|0.14%|0.47201|-1.33%|0.47191|-1.33%|0.941|0.000|176397556|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a3f0861f2e)|0.45110|0.45730|0.00075|0.17%|0.45280|-5.34%|0.45266|-5.36%|2.613|0.000|147886610|53.44 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73410|0.74754|0.00136|0.18%|0.74457|0.00%|0.74457|0.00%|-4.439|0.999|291620807|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96aa0e08a1)|0.73502|0.74765|0.00201|0.27%|0.73729|-0.98%|0.73679|-1.04%|2.702|0.000|287352080|40.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/a3f0861f2e)|0.72947|0.74825|0.00197|0.27%|0.73983|-0.64%|0.73957|-0.67%|-0.248|0.000|287339183|40.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a3f0861f2e)|0.70875|0.71228|0.00076|0.11%|0.71035|-4.60%|0.71029|-4.60%|0.266|0.000|267701996|47.84 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57794|0.58503|0.00094|0.16%|0.58215|0.00%|0.58196|0.00%|-0.026|0.999|1123343408|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96aa0e08a1)|0.57816|0.58422|0.00075|0.13%|0.58210|-0.01%|0.58198|0.00%|-0.786|0.813|1120247933|44.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/a3f0861f2e)|0.57962|0.58584|0.00091|0.16%|0.58101|-0.19%|0.58086|-0.19%|2.137|0.000|1120256295|44.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a3f0861f2e)|0.51621|0.51927|0.00054|0.10%|0.51726|-11.15%|0.51721|-11.13%|0.933|0.000|866314560|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43014|0.44247|0.00216|0.50%|0.43362|0.00%|0.43330|0.00%|1.086|0.999|2020638149|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96aa0e08a1)|0.42528|0.53392|0.02498|5.70%|0.43818|1.05%|0.43053|-0.64%|3.133|0.000|2020595030|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/a3f0861f2e)|0.43365|0.53955|0.01382|3.14%|0.43948|1.35%|0.43731|0.93%|6.773|0.000|2020595019|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a3f0861f2e)|0.14730|0.15316|0.00112|0.75%|0.14922|-65.59%|0.14905|-65.60%|1.236|0.000|536613131|27.74 MB|
