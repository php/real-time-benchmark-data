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
| Time          |2025-12-13 00:50:13 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47505|0.47931|0.00080|0.17%|0.47670|0.00%|0.47662|0.00%|0.545|0.999|180943131|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/19deb91002)|0.46891|0.47330|0.00080|0.17%|0.47035|-1.33%|0.47035|-1.32%|0.689|0.000|176404392|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/2ee5e6b432)|0.46943|0.47325|0.00085|0.18%|0.47105|-1.18%|0.47092|-1.19%|0.497|0.000|176403775|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2ee5e6b432)|0.45143|0.45617|0.00088|0.19%|0.45279|-5.02%|0.45269|-5.02%|0.898|0.000|147911736|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74447|0.75749|0.00196|0.26%|0.74688|0.00%|0.74654|0.00%|3.818|0.999|291625346|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/19deb91002)|0.74493|0.75192|0.00146|0.19%|0.74787|0.13%|0.74749|0.13%|0.974|0.000|290398747|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/2ee5e6b432)|0.74381|0.75854|0.00228|0.30%|0.74638|-0.07%|0.74581|-0.10%|2.904|0.000|290413317|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2ee5e6b432)|0.70928|0.72094|0.00150|0.21%|0.71674|-4.04%|0.71647|-4.03%|-0.563|0.000|270746210|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58035|0.59151|0.00125|0.21%|0.58171|0.00%|0.58149|0.00%|5.084|0.999|1123343670|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/19deb91002)|0.58109|0.58508|0.00063|0.11%|0.58219|0.08%|0.58208|0.10%|1.615|0.000|1119622299|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/2ee5e6b432)|0.58041|0.58434|0.00069|0.12%|0.58176|0.01%|0.58159|0.02%|1.422|0.089|1119630041|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2ee5e6b432)|0.51583|0.51937|0.00053|0.10%|0.51822|-10.91%|0.51818|-10.89%|-0.648|0.000|865683102|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42914|0.44096|0.00228|0.52%|0.43440|0.00%|0.43433|0.00%|0.229|0.999|2020638182|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/19deb91002)|0.42272|0.43924|0.00296|0.69%|0.42691|-1.72%|0.42607|-1.90%|2.252|0.000|2020586702|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/2ee5e6b432)|0.42410|0.43857|0.00267|0.62%|0.42826|-1.41%|0.42787|-1.49%|1.520|0.000|2020586698|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2ee5e6b432)|0.14673|0.15307|0.00115|0.78%|0.14878|-65.75%|0.14861|-65.78%|0.747|0.000|536605689|27.74 MB|
