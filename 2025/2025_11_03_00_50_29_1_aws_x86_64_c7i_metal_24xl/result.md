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
| Time          |2025-11-03 00:50:29 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47626|0.47953|0.00058|0.12%|0.47727|0.00%|0.47717|0.00%|1.161|0.999|180951404|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a979e9f897)|0.47143|0.47450|0.00060|0.13%|0.47235|-1.03%|0.47227|-1.03%|1.022|0.000|176336384|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/49c3ff6c89)|0.47103|0.47624|0.00079|0.17%|0.47223|-1.06%|0.47209|-1.06%|2.104|0.000|176408034|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/49c3ff6c89)|0.45065|0.45347|0.00045|0.10%|0.45166|-5.37%|0.45161|-5.36%|0.949|0.000|147881748|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74100|0.75372|0.00197|0.27%|0.74295|0.00%|0.74258|0.00%|4.257|0.999|291624361|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a979e9f897)|0.74000|0.75176|0.00183|0.25%|0.74203|-0.12%|0.74159|-0.13%|4.240|0.000|287334827|40.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/49c3ff6c89)|0.73943|0.75041|0.00202|0.27%|0.74119|-0.24%|0.74063|-0.26%|3.418|0.000|287331526|40.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/49c3ff6c89)|0.70964|0.71288|0.00063|0.09%|0.71111|-4.29%|0.71108|-4.24%|0.110|0.000|267693926|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58157|0.58621|0.00084|0.14%|0.58309|0.00%|0.58299|0.00%|1.121|0.999|1123337319|43.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a979e9f897)|0.58425|0.59455|0.00123|0.21%|0.58568|0.44%|0.58551|0.43%|4.154|0.000|1120319444|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/49c3ff6c89)|0.58410|0.58752|0.00060|0.10%|0.58538|0.39%|0.58529|0.39%|0.611|0.000|1120321463|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/49c3ff6c89)|0.51799|0.52117|0.00061|0.12%|0.51899|-10.99%|0.51894|-10.99%|0.736|0.000|866371925|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42930|0.44843|0.00249|0.57%|0.43362|0.00%|0.43333|0.00%|2.469|0.999|2020638189|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a979e9f897)|0.42438|0.47886|0.00593|1.39%|0.42839|-1.21%|0.42700|-1.46%|6.582|0.000|2020586546|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/49c3ff6c89)|0.42381|0.43685|0.00213|0.50%|0.42640|-1.66%|0.42574|-1.75%|2.428|0.000|2020586614|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/49c3ff6c89)|0.14427|0.15158|0.00136|0.93%|0.14699|-66.10%|0.14673|-66.14%|0.860|0.000|536605644|27.67 MB|
