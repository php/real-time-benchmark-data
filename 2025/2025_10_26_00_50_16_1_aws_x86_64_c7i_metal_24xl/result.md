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
| Time          |2025-10-26 00:50:16 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47595|0.47901|0.00063|0.13%|0.47680|0.00%|0.47669|0.00%|1.267|0.999|180948289|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7455f6a5b0)|0.46706|0.47160|0.00074|0.16%|0.46869|-1.70%|0.46855|-1.71%|1.646|0.000|176310086|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/275ec6f335)|0.46785|0.47095|0.00063|0.13%|0.46885|-1.67%|0.46876|-1.67%|0.895|0.000|176381944|44.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/275ec6f335)|0.44951|0.45328|0.00052|0.12%|0.45043|-5.53%|0.45038|-5.52%|2.034|0.000|147850617|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74006|0.75286|0.00137|0.19%|0.74165|0.00%|0.74145|0.00%|5.619|0.999|291621392|40.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7455f6a5b0)|0.73530|0.74607|0.00152|0.21%|0.73733|-0.58%|0.73691|-0.61%|2.401|0.000|287324449|40.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/275ec6f335)|0.73466|0.74801|0.00206|0.28%|0.73724|-0.60%|0.73668|-0.64%|2.856|0.000|287324504|40.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/275ec6f335)|0.70633|0.71143|0.00081|0.11%|0.70811|-4.52%|0.70793|-4.52%|0.963|0.000|267687366|47.80 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58053|0.58475|0.00089|0.15%|0.58245|0.00%|0.58237|0.00%|0.347|0.999|1123403853|43.81 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7455f6a5b0)|0.58331|0.58765|0.00096|0.16%|0.58526|0.48%|0.58525|0.49%|0.364|0.000|1120134497|44.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/275ec6f335)|0.58344|0.58822|0.00097|0.17%|0.58562|0.54%|0.58561|0.56%|0.207|0.000|1120142491|44.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/275ec6f335)|0.51816|0.52216|0.00076|0.15%|0.51973|-10.77%|0.51962|-10.77%|0.702|0.000|865313410|61.71 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42892|0.43872|0.00214|0.49%|0.43368|0.00%|0.43347|0.00%|0.226|0.999|2020638191|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7455f6a5b0)|0.42367|0.43661|0.00269|0.63%|0.42688|-1.57%|0.42612|-1.70%|1.843|0.000|2020586585|26.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/275ec6f335)|0.42381|0.43910|0.00280|0.65%|0.42691|-1.56%|0.42605|-1.71%|2.584|0.000|2020586613|26.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/275ec6f335)|0.14323|0.15039|0.00129|0.88%|0.14664|-66.19%|0.14658|-66.18%|0.453|0.000|536605616|27.69 MB|
