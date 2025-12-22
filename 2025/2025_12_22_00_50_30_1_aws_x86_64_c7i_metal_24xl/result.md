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
| Time          |2025-12-22 00:50:30 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47454|0.48285|0.00089|0.19%|0.47545|0.00%|0.47525|0.00%|5.961|0.999|180942093|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5dd5a4267f)|0.46918|0.47307|0.00062|0.13%|0.46999|-1.15%|0.46987|-1.13%|2.428|0.000|176329700|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/1faf17b017)|0.46800|0.47219|0.00077|0.16%|0.46905|-1.35%|0.46888|-1.34%|2.111|0.000|176405025|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1faf17b017)|0.44781|0.45209|0.00055|0.12%|0.44886|-5.59%|0.44873|-5.58%|2.303|0.000|147890234|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74190|0.75261|0.00116|0.16%|0.74355|0.00%|0.74335|0.00%|4.904|0.999|291621925|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5dd5a4267f)|0.74122|0.75139|0.00178|0.24%|0.74302|-0.07%|0.74259|-0.10%|2.796|0.000|290411116|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/1faf17b017)|0.73883|0.75129|0.00154|0.21%|0.74063|-0.39%|0.74031|-0.41%|4.099|0.000|290409889|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1faf17b017)|0.71459|0.71797|0.00066|0.09%|0.71595|-3.71%|0.71591|-3.69%|0.396|0.000|270766434|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57856|0.58179|0.00060|0.10%|0.58032|0.00%|0.58017|0.00%|0.459|0.999|1123344685|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5dd5a4267f)|0.57980|0.59159|0.00120|0.21%|0.58190|0.27%|0.58176|0.27%|5.448|0.000|1119535237|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/1faf17b017)|0.57936|0.58438|0.00071|0.12%|0.58115|0.14%|0.58103|0.15%|1.439|0.000|1119534748|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1faf17b017)|0.51601|0.51918|0.00053|0.10%|0.51709|-10.90%|0.51704|-10.88%|1.030|0.000|865595587|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43017|0.44592|0.00256|0.59%|0.43469|0.00%|0.43461|0.00%|1.398|0.999|2020638211|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5dd5a4267f)|0.42364|0.43899|0.00285|0.67%|0.42777|-1.59%|0.42709|-1.73%|1.807|0.000|2020586636|27.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/1faf17b017)|0.42425|0.43734|0.00179|0.42%|0.42726|-1.71%|0.42702|-1.75%|2.122|0.000|2020586665|27.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1faf17b017)|0.14354|0.15000|0.00127|0.87%|0.14681|-66.23%|0.14688|-66.21%|-0.169|0.000|536605656|27.87 MB|
