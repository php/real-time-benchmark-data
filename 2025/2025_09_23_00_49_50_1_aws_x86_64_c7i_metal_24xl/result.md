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
| Time          |2025-09-23 00:49:50 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46859|0.48049|0.00102|0.21%|0.47572|0.00%|0.47568|0.00%|-2.227|0.999|180946218|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4bc060c0f3)|0.46739|0.47014|0.00058|0.12%|0.46820|-1.58%|0.46809|-1.60%|1.337|0.000|176266846|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e1b1900f0)|0.46327|0.46577|0.00053|0.11%|0.46409|-2.45%|0.46403|-2.45%|0.759|0.000|176354326|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e1b1900f0)|0.44599|0.44778|0.00041|0.09%|0.44664|-6.11%|0.44653|-6.13%|0.843|0.000|147823484|53.45 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73216|0.74239|0.00112|0.15%|0.74020|0.00%|0.74004|0.00%|-3.496|0.999|291622853|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4bc060c0f3)|0.73376|0.74486|0.00201|0.27%|0.73547|-0.64%|0.73482|-0.71%|2.925|0.000|287317471|40.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e1b1900f0)|0.73199|0.74311|0.00149|0.20%|0.73379|-0.87%|0.73347|-0.89%|3.342|0.000|287319490|40.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e1b1900f0)|0.70642|0.71034|0.00067|0.10%|0.70779|-4.38%|0.70766|-4.38%|0.963|0.000|267631574|47.59 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57971|0.64612|0.01257|2.15%|0.58442|0.00%|0.58174|0.00%|4.687|0.999|1123344053|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4bc060c0f3)|0.57903|0.64483|0.01055|1.81%|0.58213|-0.39%|0.58012|-0.28%|5.563|0.000|1119772069|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e1b1900f0)|0.57631|0.64533|0.01080|1.86%|0.58195|-0.42%|0.58000|-0.30%|5.553|0.000|1119780611|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e1b1900f0)|0.51545|0.58609|0.01205|2.32%|0.51968|-11.08%|0.51731|-11.08%|4.974|0.000|865938623|61.57 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42461|0.44664|0.00249|0.57%|0.43365|0.00%|0.43365|0.00%|0.985|0.999|2020638136|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4bc060c0f3)|0.42562|0.55210|0.02595|5.98%|0.43409|0.10%|0.42830|-1.23%|4.176|0.000|2020645056|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e1b1900f0)|0.42451|0.55334|0.02486|5.74%|0.43279|-0.20%|0.42696|-1.54%|4.202|0.000|2020644790|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e1b1900f0)|0.14719|0.15152|0.00088|0.59%|0.14936|-65.56%|0.14920|-65.59%|0.384|0.000|536613102|27.81 MB|
