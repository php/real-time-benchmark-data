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
| Time          |2025-10-03 00:50:09 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47576|0.48194|0.00080|0.17%|0.47705|0.00%|0.47693|0.00%|2.744|0.999|180950149|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3ac43296aa)|0.46791|0.47113|0.00061|0.13%|0.46941|-1.60%|0.46933|-1.59%|0.656|0.000|176331233|44.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/28fd7597ba)|0.46930|0.47270|0.00072|0.15%|0.47065|-1.34%|0.47059|-1.33%|0.840|0.000|176406363|44.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/28fd7597ba)|0.45043|0.45551|0.00076|0.17%|0.45170|-5.31%|0.45163|-5.30%|1.582|0.000|147890296|53.46 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74080|0.75328|0.00136|0.18%|0.74271|0.00%|0.74253|0.00%|4.825|0.999|291623937|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3ac43296aa)|0.73537|0.74905|0.00140|0.19%|0.73917|-0.48%|0.73896|-0.48%|3.593|0.000|287342804|40.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/28fd7597ba)|0.73662|0.74981|0.00247|0.33%|0.73892|-0.51%|0.73815|-0.59%|2.430|0.000|287356055|40.57 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/28fd7597ba)|0.70911|0.71256|0.00070|0.10%|0.71067|-4.31%|0.71065|-4.29%|0.087|0.000|267718709|47.85 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58101|0.59481|0.00214|0.37%|0.58338|0.00%|0.58268|0.00%|2.215|0.999|1123335823|43.58 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3ac43296aa)|0.58380|0.59239|0.00190|0.32%|0.58610|0.47%|0.58542|0.47%|1.475|0.000|1120241573|44.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/28fd7597ba)|0.58138|0.58898|0.00194|0.33%|0.58385|0.08%|0.58311|0.07%|1.320|0.000|1120242715|44.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/28fd7597ba)|0.51701|0.52315|0.00166|0.32%|0.51866|-11.10%|0.51812|-11.08%|1.514|0.000|866313309|61.56 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42902|0.43958|0.00206|0.48%|0.43361|0.00%|0.43342|0.00%|0.544|0.999|2020638218|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3ac43296aa)|0.43504|0.55417|0.01989|4.49%|0.44313|2.20%|0.43885|1.25%|4.736|0.000|2020595050|26.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/28fd7597ba)|0.43459|0.59689|0.02140|4.84%|0.44196|1.93%|0.43819|1.10%|5.956|0.000|2020595091|27.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/28fd7597ba)|0.14202|0.15145|0.00111|0.74%|0.14922|-65.59%|0.14920|-65.58%|-2.579|0.000|536613234|27.82 MB|
