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
| OS            |Amazon Linux 2023.9.20251110|
| GCC           |14.2.1|
| Time          |2025-11-18 00:50:21 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46874|0.47734|0.00089|0.19%|0.47547|0.00%|0.47544|0.00%|-4.100|0.999|180943096|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3977650820)|0.46619|0.47384|0.00078|0.17%|0.46871|-1.42%|0.46856|-1.45%|3.029|0.000|176334438|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/d750d30a62)|0.46680|0.47092|0.00080|0.17%|0.46788|-1.60%|0.46771|-1.63%|1.947|0.000|176405980|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d750d30a62)|0.44681|0.45115|0.00053|0.12%|0.44962|-5.44%|0.44956|-5.44%|-0.887|0.000|147882217|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74132|0.74502|0.00077|0.10%|0.74299|0.00%|0.74283|0.00%|0.653|0.999|291621920|40.09 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3977650820)|0.73903|0.74619|0.00128|0.17%|0.74078|-0.30%|0.74045|-0.32%|1.876|0.000|290398613|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/d750d30a62)|0.73959|0.74550|0.00124|0.17%|0.74115|-0.25%|0.74082|-0.27%|1.475|0.000|290399436|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d750d30a62)|0.71356|0.71736|0.00072|0.10%|0.71511|-3.75%|0.71500|-3.75%|0.470|0.000|270761693|47.87 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57998|0.58477|0.00076|0.13%|0.58126|0.00%|0.58111|0.00%|1.638|0.999|1123347458|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3977650820)|0.57894|0.58211|0.00059|0.10%|0.58004|-0.21%|0.58003|-0.19%|0.860|0.000|1119624933|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/d750d30a62)|0.57905|0.58249|0.00064|0.11%|0.58034|-0.16%|0.58030|-0.14%|0.652|0.000|1119633516|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d750d30a62)|0.51696|0.51921|0.00046|0.09%|0.51777|-10.92%|0.51777|-10.90%|0.609|0.000|865684818|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42880|0.44275|0.00228|0.53%|0.43489|0.00%|0.43461|0.00%|0.496|0.999|2020638212|26.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3977650820)|0.42417|0.43831|0.00281|0.66%|0.42771|-1.65%|0.42702|-1.75%|1.920|0.000|2020586687|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/d750d30a62)|0.42334|0.47907|0.00595|1.39%|0.42826|-1.52%|0.42677|-1.80%|6.534|0.000|2020586658|26.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d750d30a62)|0.14621|0.15165|0.00088|0.59%|0.14865|-65.82%|0.14866|-65.79%|-0.011|0.000|536605646|27.75 MB|
