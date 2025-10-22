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
| Time          |2025-10-22 00:50:10 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47566|0.47941|0.00069|0.15%|0.47669|0.00%|0.47651|0.00%|1.229|0.999|180946226|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17652409b8)|0.46592|0.47220|0.00068|0.14%|0.46919|-1.57%|0.46919|-1.54%|0.116|0.000|176331056|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/40a42cffd8)|0.46902|0.47246|0.00065|0.14%|0.46997|-1.41%|0.46982|-1.40%|1.190|0.000|176405041|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/40a42cffd8)|0.44931|0.45350|0.00053|0.12%|0.45008|-5.58%|0.44996|-5.57%|3.027|0.000|147869041|53.38 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74111|0.75366|0.00138|0.19%|0.74253|0.00%|0.74234|0.00%|5.474|0.999|291621386|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17652409b8)|0.73303|0.74395|0.00161|0.22%|0.73472|-1.05%|0.73423|-1.09%|2.600|0.000|287318814|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/40a42cffd8)|0.73557|0.74721|0.00199|0.27%|0.73786|-0.63%|0.73740|-0.66%|2.561|0.000|287318817|40.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/40a42cffd8)|0.70750|0.71386|0.00084|0.12%|0.70875|-4.55%|0.70862|-4.54%|2.542|0.000|267681944|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58028|0.59341|0.00139|0.24%|0.58245|0.00%|0.58223|0.00%|5.082|0.999|1123343625|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17652409b8)|0.58156|0.58556|0.00075|0.13%|0.58343|0.17%|0.58337|0.19%|0.450|0.000|1120065893|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/40a42cffd8)|0.58046|0.58545|0.00084|0.14%|0.58270|0.04%|0.58268|0.08%|0.297|0.003|1120074004|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/40a42cffd8)|0.51700|0.51927|0.00053|0.10%|0.51832|-11.01%|0.51831|-10.98%|-0.307|0.000|866126002|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42547|0.44203|0.00214|0.49%|0.43338|0.00%|0.43337|0.00%|0.284|0.999|2020638139|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17652409b8)|0.42204|0.43863|0.00258|0.60%|0.42679|-1.52%|0.42642|-1.60%|2.208|0.000|2020586550|26.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/40a42cffd8)|0.42353|0.43656|0.00291|0.68%|0.42710|-1.45%|0.42640|-1.61%|1.912|0.000|2020586650|26.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/40a42cffd8)|0.14464|0.15049|0.00121|0.82%|0.14698|-66.09%|0.14681|-66.12%|0.450|0.000|536605603|27.67 MB|
