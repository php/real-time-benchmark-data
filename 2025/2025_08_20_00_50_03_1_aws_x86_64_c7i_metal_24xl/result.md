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
| GCC           |11.5.0|
| Time          |2025-08-20 00:50:03 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46915|0.47481|0.00067|0.14%|0.47155|0.00%|0.47154|0.00%|1.000|181824512|43.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c98b173430)|0.46463|0.47102|0.00068|0.15%|0.46548|-1.29%|0.46538|-1.31%|0.001|177209625|43.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/1cff1815d0)|0.46659|0.46849|0.00037|0.08%|0.46740|-0.88%|0.46735|-0.89%|0.001|177213258|43.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1cff1815d0)|0.44966|0.45170|0.00038|0.09%|0.45038|-4.49%|0.45035|-4.49%|0.001|154365269|53.80 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73936|0.74557|0.00088|0.12%|0.74131|0.00%|0.74120|0.00%|1.000|292381798|39.97 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c98b173430)|0.73083|0.74239|0.00230|0.31%|0.73287|-1.14%|0.73231|-1.20%|0.001|288324477|40.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/1cff1815d0)|0.72953|0.74312|0.00237|0.32%|0.73219|-1.23%|0.73153|-1.30%|0.001|288323905|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1cff1815d0)|0.70021|0.70878|0.00137|0.20%|0.70186|-5.32%|0.70154|-5.35%|0.001|291588114|48.07 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58124|0.58797|0.00098|0.17%|0.58357|0.00%|0.58368|0.00%|1.000|1133180781|43.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c98b173430)|0.57809|0.58276|0.00100|0.17%|0.58011|-0.59%|0.58023|-0.59%|0.001|1129307194|43.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/1cff1815d0)|0.57723|0.58216|0.00092|0.16%|0.58012|-0.59%|0.58025|-0.59%|0.001|1129318949|43.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1cff1815d0)|0.51248|0.51756|0.00085|0.16%|0.51555|-11.66%|0.51570|-11.65%|0.001|870886151|61.48 MB|

### bench.php - 100 consecutive runs, 4 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.85780|0.89454|0.00426|0.49%|0.86302|0.00%|0.86245|0.00%|1.000|2031002318|26.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c98b173430)|0.86338|1.17301|0.05707|6.46%|0.88329|2.35%|0.86875|0.73%|0.001|2031543233|26.66 MB|
|[PHP - master](https://github.com/php/php-src/commit/1cff1815d0)|0.86997|1.17552|0.05881|6.61%|0.89013|3.14%|0.87505|1.46%|0.001|2031543252|26.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1cff1815d0)|0.29669|0.30265|0.00131|0.44%|0.29911|-65.34%|0.29895|-65.34%|0.001|538131915|27.94 MB|
