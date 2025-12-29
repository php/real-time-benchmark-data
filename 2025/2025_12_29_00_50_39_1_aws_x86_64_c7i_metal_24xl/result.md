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
| Time          |2025-12-29 00:50:39 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47669|0.48341|0.00078|0.16%|0.47800|0.00%|0.47789|0.00%|3.501|0.999|180944822|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ecbdd2b580)|0.47142|0.47635|0.00082|0.17%|0.47266|-1.12%|0.47253|-1.12%|2.026|0.000|176330289|44.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/04bf2e5c4a)|0.47026|0.47694|0.00094|0.20%|0.47275|-1.10%|0.47263|-1.10%|1.740|0.000|176406109|44.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/04bf2e5c4a)|0.45151|0.45384|0.00042|0.09%|0.45252|-5.33%|0.45255|-5.30%|0.472|0.000|147898522|53.53 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74553|0.74956|0.00082|0.11%|0.74707|0.00%|0.74696|0.00%|0.562|0.999|291622017|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ecbdd2b580)|0.73952|0.75831|0.00156|0.21%|0.74891|0.25%|0.74883|0.25%|0.067|0.000|290414927|40.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/04bf2e5c4a)|0.74604|0.75622|0.00143|0.19%|0.74775|0.09%|0.74743|0.06%|2.919|0.000|290409554|40.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/04bf2e5c4a)|0.72113|0.72570|0.00092|0.13%|0.72240|-3.30%|0.72227|-3.31%|1.444|0.000|270766466|47.99 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57904|0.64841|0.02084|3.54%|0.58878|0.00%|0.58121|0.00%|2.374|0.999|1123344568|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ecbdd2b580)|0.58000|0.64760|0.02070|3.51%|0.58935|0.10%|0.58138|0.03%|2.279|0.158|1119533952|44.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/04bf2e5c4a)|0.57906|0.64759|0.02027|3.44%|0.58882|0.01%|0.58140|0.03%|2.363|0.671|1119536160|44.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/04bf2e5c4a)|0.51556|0.58717|0.02083|3.97%|0.52521|-10.80%|0.51782|-10.91%|2.388|0.000|865596388|61.63 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43097|0.44066|0.00216|0.50%|0.43469|0.00%|0.43450|0.00%|0.507|0.999|2020638153|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ecbdd2b580)|0.43503|0.44365|0.00169|0.39%|0.43939|1.08%|0.43940|1.13%|0.127|0.000|2020586615|27.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/04bf2e5c4a)|0.43383|0.44711|0.00190|0.43%|0.43919|1.04%|0.43891|1.02%|1.158|0.000|2020586639|27.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/04bf2e5c4a)|0.14151|0.15181|0.00141|0.96%|0.14685|-66.22%|0.14676|-66.22%|0.197|0.000|536605601|27.88 MB|
