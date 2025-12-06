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
| Time          |2025-12-06 00:50:03 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47450|0.47713|0.00055|0.12%|0.47569|0.00%|0.47567|0.00%|0.372|0.999|180944746|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4cc5f02387)|0.46372|0.47358|0.00101|0.21%|0.47067|-1.05%|0.47057|-1.07%|-2.740|0.000|176337045|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/824c389128)|0.46945|0.47192|0.00054|0.11%|0.47068|-1.05%|0.47057|-1.07%|0.436|0.000|176405937|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/824c389128)|0.44973|0.45361|0.00056|0.12%|0.45066|-5.26%|0.45055|-5.28%|1.769|0.000|147903396|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74199|0.75468|0.00198|0.27%|0.74359|0.00%|0.74319|0.00%|4.565|0.999|291621245|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4cc5f02387)|0.74503|0.75622|0.00130|0.17%|0.74660|0.40%|0.74640|0.43%|4.325|0.000|290401497|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/824c389128)|0.74323|0.75290|0.00165|0.22%|0.74558|0.27%|0.74512|0.26%|1.755|0.000|290398716|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/824c389128)|0.71557|0.72051|0.00079|0.11%|0.71694|-3.58%|0.71687|-3.54%|1.157|0.000|270761199|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57603|0.58794|0.00222|0.38%|0.58028|0.00%|0.58090|0.00%|0.076|0.999|1123345412|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4cc5f02387)|0.57550|0.58320|0.00195|0.34%|0.57974|-0.09%|0.58061|-0.05%|-0.815|0.008|1119622585|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/824c389128)|0.57610|0.58336|0.00203|0.35%|0.57998|-0.05%|0.58072|-0.03%|-0.774|0.353|1119632624|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/824c389128)|0.51308|0.51898|0.00153|0.30%|0.51631|-11.02%|0.51687|-11.02%|-0.745|0.000|865683277|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43148|0.43925|0.00179|0.41%|0.43470|0.00%|0.43436|0.00%|0.435|0.999|2020638145|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4cc5f02387)|0.42528|0.48281|0.00786|1.83%|0.42988|-1.11%|0.42846|-1.36%|5.843|0.000|2020586684|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/824c389128)|0.42363|0.47962|0.00586|1.37%|0.42786|-1.57%|0.42655|-1.80%|7.279|0.000|2020586716|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/824c389128)|0.14641|0.15182|0.00109|0.73%|0.14882|-65.76%|0.14882|-65.74%|0.226|0.000|536605656|27.74 MB|
