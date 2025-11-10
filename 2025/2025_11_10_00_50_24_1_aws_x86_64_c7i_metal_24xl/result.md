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
| Time          |2025-11-10 00:50:24 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47464|0.48008|0.00070|0.15%|0.47837|0.00%|0.47834|0.00%|-1.282|0.999|180947563|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7b4270adf0)|0.46841|0.47111|0.00057|0.12%|0.46941|-1.87%|0.46933|-1.88%|0.550|0.000|176335025|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/e97c0dc340)|0.46867|0.47170|0.00055|0.12%|0.46976|-1.80%|0.46969|-1.81%|1.002|0.000|176406440|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e97c0dc340)|0.45057|0.45542|0.00068|0.15%|0.45156|-5.60%|0.45142|-5.63%|3.541|0.000|147884659|53.38 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73265|0.74596|0.00137|0.18%|0.74349|0.00%|0.74355|0.00%|-4.902|0.999|291621984|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7b4270adf0)|0.73922|0.75112|0.00175|0.24%|0.74151|-0.27%|0.74110|-0.33%|2.442|0.000|290378710|40.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/e97c0dc340)|0.73819|0.75093|0.00186|0.25%|0.74079|-0.36%|0.74030|-0.44%|2.434|0.000|290379770|40.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e97c0dc340)|0.71447|0.72002|0.00083|0.12%|0.71609|-3.69%|0.71608|-3.69%|1.481|0.000|270741860|47.85 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58115|0.58476|0.00063|0.11%|0.58263|0.00%|0.58254|0.00%|0.861|0.999|1123345735|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7b4270adf0)|0.57611|0.58459|0.00103|0.18%|0.58180|-0.14%|0.58169|-0.15%|-0.955|0.000|1119591803|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/e97c0dc340)|0.58024|0.58454|0.00074|0.13%|0.58168|-0.16%|0.58155|-0.17%|1.078|0.000|1119599417|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e97c0dc340)|0.51801|0.52085|0.00054|0.10%|0.51929|-10.87%|0.51924|-10.87%|0.385|0.000|865650307|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42660|0.43928|0.00204|0.47%|0.43323|0.00%|0.43315|0.00%|0.130|0.999|2020638189|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7b4270adf0)|0.42292|0.43614|0.00228|0.54%|0.42589|-1.69%|0.42519|-1.84%|2.369|0.000|2020586583|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/e97c0dc340)|0.42324|0.43915|0.00265|0.62%|0.42568|-1.74%|0.42486|-1.91%|2.880|0.000|2020586629|26.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e97c0dc340)|0.14674|0.15124|0.00101|0.68%|0.14879|-65.66%|0.14862|-65.69%|0.464|0.000|536605680|27.73 MB|
