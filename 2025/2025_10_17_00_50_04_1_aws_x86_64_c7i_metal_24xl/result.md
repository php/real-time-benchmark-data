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
| Time          |2025-10-17 00:50:04 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46941|0.47790|0.00088|0.19%|0.47607|0.00%|0.47603|0.00%|-4.107|0.999|180944211|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/264d650117)|0.47023|0.47577|0.00078|0.17%|0.47129|-1.00%|0.47112|-1.03%|2.665|0.000|176332425|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/009cf303f9)|0.46673|0.47325|0.00077|0.16%|0.46772|-1.75%|0.46754|-1.78%|3.965|0.000|176405211|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/009cf303f9)|0.44979|0.45352|0.00057|0.13%|0.45084|-5.30%|0.45080|-5.30%|1.421|0.000|147869509|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73982|0.75107|0.00157|0.21%|0.74159|0.00%|0.74129|0.00%|4.413|0.999|291621384|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/264d650117)|0.73703|0.74819|0.00198|0.27%|0.73951|-0.28%|0.73897|-0.31%|2.248|0.000|287318724|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/009cf303f9)|0.72481|0.74699|0.00233|0.32%|0.73568|-0.80%|0.73514|-0.83%|1.000|0.000|287318816|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/009cf303f9)|0.70688|0.71007|0.00065|0.09%|0.70853|-4.46%|0.70845|-4.43%|0.300|0.000|267681724|47.79 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57710|0.64999|0.02386|4.03%|0.59187|0.00%|0.58177|0.00%|1.883|0.999|1123343805|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/264d650117)|0.58223|0.65018|0.02269|3.82%|0.59465|0.47%|0.58503|0.56%|1.894|0.000|1120238326|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/009cf303f9)|0.58071|0.65001|0.02319|3.90%|0.59504|0.53%|0.58506|0.57%|1.875|0.000|1120245355|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/009cf303f9)|0.51582|0.58793|0.02462|4.66%|0.52867|-10.68%|0.51785|-10.99%|1.797|0.000|866295411|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42907|0.44360|0.00226|0.52%|0.43319|0.00%|0.43301|0.00%|1.367|0.999|2020638214|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/264d650117)|0.43651|0.60011|0.02761|6.18%|0.44663|3.10%|0.43982|1.57%|4.068|0.000|2020595086|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/009cf303f9)|0.42482|0.53667|0.02715|6.23%|0.43617|0.69%|0.42803|-1.15%|3.125|0.000|2020595015|26.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/009cf303f9)|0.14489|0.15095|0.00124|0.84%|0.14749|-65.95%|0.14735|-65.97%|0.364|0.000|536613136|27.68 MB|
