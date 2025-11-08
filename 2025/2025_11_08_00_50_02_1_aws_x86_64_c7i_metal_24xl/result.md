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
| Time          |2025-11-08 00:50:02 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47539|0.48137|0.00072|0.15%|0.47649|0.00%|0.47635|0.00%|3.524|0.999|180948147|43.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/297179dbcc)|0.46502|0.46978|0.00067|0.14%|0.46623|-2.15%|0.46611|-2.15%|2.173|0.000|176374225|44.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/5ab594cf01)|0.46547|0.46851|0.00056|0.12%|0.46651|-2.09%|0.46642|-2.09%|0.944|0.000|176448771|44.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5ab594cf01)|0.44642|0.44931|0.00047|0.11%|0.44723|-6.14%|0.44718|-6.13%|1.192|0.000|147929812|53.38 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73953|0.75216|0.00201|0.27%|0.74157|0.00%|0.74116|0.00%|4.067|0.999|291621220|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/297179dbcc)|0.73548|0.74829|0.00179|0.24%|0.73719|-0.59%|0.73696|-0.57%|4.766|0.000|290434040|40.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/5ab594cf01)|0.73562|0.74658|0.00143|0.19%|0.73739|-0.56%|0.73709|-0.55%|3.306|0.000|290430714|40.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5ab594cf01)|0.71226|0.71607|0.00074|0.10%|0.71372|-3.75%|0.71362|-3.72%|0.688|0.000|270793568|47.84 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58113|0.58608|0.00091|0.16%|0.58275|0.00%|0.58259|0.00%|1.433|0.999|1123345017|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/297179dbcc)|0.57946|0.58295|0.00068|0.12%|0.58094|-0.31%|0.58087|-0.29%|0.423|0.000|1119602183|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/5ab594cf01)|0.57533|0.58370|0.00112|0.19%|0.58076|-0.34%|0.58079|-0.31%|-0.989|0.000|1119609035|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5ab594cf01)|0.51631|0.52038|0.00071|0.14%|0.51776|-11.15%|0.51769|-11.14%|0.701|0.000|865659384|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42841|0.44292|0.00208|0.48%|0.43286|0.00%|0.43262|0.00%|1.278|0.999|2020638207|26.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/297179dbcc)|0.42128|0.43614|0.00198|0.46%|0.42682|-1.40%|0.42653|-1.41%|1.843|0.000|2020586573|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/5ab594cf01)|0.42342|0.43741|0.00302|0.71%|0.42641|-1.49%|0.42543|-1.66%|1.964|0.000|2020586588|26.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5ab594cf01)|0.14683|0.15258|0.00099|0.67%|0.14877|-65.63%|0.14869|-65.63%|0.824|0.000|536605513|27.73 MB|
