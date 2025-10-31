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
| Time          |2025-10-31 00:50:21 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47551|0.48210|0.00079|0.17%|0.47679|0.00%|0.47666|0.00%|3.265|0.999|180948020|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6cf45c4bd5)|0.46867|0.47611|0.00125|0.27%|0.47014|-1.39%|0.46988|-1.42%|2.743|0.000|176330612|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/425b97e0b6)|0.46875|0.47412|0.00099|0.21%|0.46990|-1.45%|0.46965|-1.47%|2.850|0.000|176401950|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/425b97e0b6)|0.44819|0.45269|0.00058|0.13%|0.44937|-5.75%|0.44934|-5.73%|2.082|0.000|147870585|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73142|0.74413|0.00130|0.18%|0.74146|0.00%|0.74150|0.00%|-4.757|0.999|291621382|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6cf45c4bd5)|0.73576|0.74622|0.00162|0.22%|0.73776|-0.50%|0.73729|-0.57%|2.266|0.000|287331486|40.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/425b97e0b6)|0.73591|0.74587|0.00138|0.19%|0.73765|-0.51%|0.73740|-0.55%|3.043|0.000|287331753|40.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/425b97e0b6)|0.70491|0.70884|0.00080|0.11%|0.70661|-4.70%|0.70647|-4.72%|0.546|0.000|267691127|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58080|0.59216|0.00124|0.21%|0.58238|0.00%|0.58211|0.00%|5.136|0.999|1123345827|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6cf45c4bd5)|0.58399|0.59048|0.00087|0.15%|0.58537|0.51%|0.58524|0.54%|2.413|0.000|1120308987|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/425b97e0b6)|0.58423|0.59438|0.00120|0.20%|0.58558|0.55%|0.58532|0.55%|4.299|0.000|1120317544|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/425b97e0b6)|0.51690|0.51991|0.00063|0.12%|0.51803|-11.05%|0.51802|-11.01%|0.444|0.000|866366426|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42590|0.44777|0.00277|0.64%|0.43365|0.00%|0.43334|0.00%|2.034|0.999|2020638149|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6cf45c4bd5)|0.42276|0.43851|0.00259|0.61%|0.42683|-1.57%|0.42618|-1.65%|2.172|0.000|2020586575|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/425b97e0b6)|0.42395|0.43770|0.00268|0.63%|0.42694|-1.55%|0.42616|-1.66%|2.221|0.000|2020586518|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/425b97e0b6)|0.14416|0.15045|0.00128|0.87%|0.14694|-66.12%|0.14676|-66.13%|0.456|0.000|536605672|27.67 MB|
