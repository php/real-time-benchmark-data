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
| Kernel        |6.12.55-74.119.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251110|
| GCC           |14.2.1|
| Time          |2025-11-16 00:50:25 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47134|0.47550|0.00067|0.14%|0.47263|0.00%|0.47253|0.00%|1.285|0.999|180951324|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0375060d16)|0.46448|0.47142|0.00081|0.17%|0.46540|-1.53%|0.46528|-1.53%|4.375|0.000|176334318|43.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/0194b381d6)|0.46430|0.47243|0.00108|0.23%|0.46562|-1.48%|0.46541|-1.51%|4.256|0.000|176327124|43.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0194b381d6)|0.44631|0.44888|0.00052|0.12%|0.44729|-5.36%|0.44722|-5.36%|0.912|0.000|147880454|53.23 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70735|0.72432|0.00201|0.28%|0.70907|0.00%|0.70853|0.00%|4.884|0.999|291622070|40.13 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0375060d16)|0.70629|0.72385|0.00208|0.29%|0.70822|-0.12%|0.70771|-0.12%|4.918|0.000|290398746|40.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/0194b381d6)|0.70640|0.71328|0.00121|0.17%|0.70824|-0.12%|0.70812|-0.06%|1.904|0.000|290399555|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0194b381d6)|0.67997|0.68565|0.00111|0.16%|0.68151|-3.89%|0.68126|-3.85%|1.938|0.000|270758186|47.23 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57105|0.58697|0.00147|0.26%|0.57607|0.00%|0.57589|0.00%|4.427|0.999|1123344257|43.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0375060d16)|0.57247|0.58469|0.00125|0.22%|0.57362|-0.42%|0.57342|-0.43%|7.182|0.000|1119621979|43.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/0194b381d6)|0.57223|0.58426|0.00128|0.22%|0.57374|-0.40%|0.57359|-0.40%|5.736|0.000|1119628938|43.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0194b381d6)|0.50914|0.51378|0.00067|0.13%|0.51218|-11.09%|0.51219|-11.06%|-0.640|0.000|865685029|61.34 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42985|0.43657|0.00161|0.37%|0.43304|0.00%|0.43310|0.00%|0.012|0.999|2020638185|26.32 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0375060d16)|0.42549|0.43751|0.00229|0.53%|0.42852|-1.04%|0.42788|-1.21%|2.355|0.000|2020586622|26.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/0194b381d6)|0.42402|0.43996|0.00289|0.67%|0.42870|-1.00%|0.42774|-1.24%|1.748|0.000|2020586727|26.68 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0194b381d6)|0.14702|0.15060|0.00083|0.56%|0.14878|-65.64%|0.14868|-65.67%|0.295|0.000|536605611|27.56 MB|
