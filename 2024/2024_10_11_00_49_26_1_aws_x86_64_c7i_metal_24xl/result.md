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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20241001|
| GCC           |11.4.1|
| Time          |2024-10-11 00:49:26 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43739|0.45157|0.00247|0.43866|0.00%|0.43809|0.00%|41.89 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/df8f298d8d)|0.43578|0.44414|0.00144|0.43682|-0.42%|0.43664|-0.33%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e172f0ac1)|0.43611|0.43866|0.00057|0.43687|-0.41%|0.43675|-0.31%|41.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e172f0ac1)|0.42380|0.42609|0.00040|0.42441|-3.25%|0.42439|-3.13%|50.83 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71400|0.72027|0.00111|0.71533|0.00%|0.71518|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/df8f298d8d)|0.71004|0.71551|0.00094|0.71131|-0.56%|0.71119|-0.56%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e172f0ac1)|0.70104|0.71214|0.00184|0.71046|-0.68%|0.71068|-0.63%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e172f0ac1)|0.68685|0.69070|0.00082|0.68798|-3.82%|0.68799|-3.80%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57958|0.58173|0.00060|0.58047|0.00%|0.58036|0.00%|43.03 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/df8f298d8d)|0.58035|0.58227|0.00048|0.58123|0.13%|0.58119|0.14%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e172f0ac1)|0.57539|0.58738|0.00197|0.57713|-0.58%|0.57688|-0.60%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e172f0ac1)|0.51882|0.52041|0.00041|0.51962|-10.48%|0.51962|-10.46%|61.96 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21481|0.21999|0.00121|0.21657|0.00%|0.21641|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/df8f298d8d)|0.21129|0.21365|0.00066|0.21264|-1.82%|0.21268|-1.73%|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e172f0ac1)|0.21594|0.21804|0.00066|0.21692|0.16%|0.21695|0.25%|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e172f0ac1)|0.07466|0.07671|0.00058|0.07539|-65.19%|0.07522|-65.24%|27.39 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34011|1.35901|0.00508|1.35088|0.00%|1.35143|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/df8f298d8d)|1.32045|1.34299|0.00489|1.32890|-1.63%|1.32857|-1.69%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e172f0ac1)|1.40829|1.43595|0.00785|1.42334|5.36%|1.42567|5.49%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e172f0ac1)|0.59930|0.61424|0.00446|0.60715|-55.06%|0.60630|-55.14%|21.80 MB|
