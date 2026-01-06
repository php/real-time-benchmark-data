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
| Time          |2026-01-06 00:50:27 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47697|0.48044|0.00066|0.14%|0.47837|0.00%|0.47831|0.00%|0.710|0.999|180946028|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb63e4f998)|0.46410|0.47402|0.00091|0.19%|0.47048|-1.65%|0.47050|-1.63%|-2.752|0.000|176329404|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/e4098da58a)|0.46931|0.47635|0.00082|0.17%|0.47077|-1.59%|0.47069|-1.59%|3.452|0.000|176406481|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e4098da58a)|0.45196|0.45408|0.00044|0.10%|0.45296|-5.31%|0.45291|-5.31%|0.184|0.000|147896597|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74234|0.75753|0.00165|0.22%|0.74769|0.00%|0.74746|0.00%|3.660|0.999|291620720|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb63e4f998)|0.74532|0.75696|0.00214|0.29%|0.74786|0.02%|0.74722|-0.03%|2.198|0.159|290408640|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/e4098da58a)|0.74019|0.75502|0.00183|0.24%|0.74710|-0.08%|0.74667|-0.11%|1.432|0.000|290408440|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e4098da58a)|0.71896|0.72376|0.00094|0.13%|0.72078|-3.60%|0.72065|-3.59%|0.715|0.000|270763763|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58077|0.58514|0.00074|0.13%|0.58215|0.00%|0.58203|0.00%|0.937|0.999|1123345632|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb63e4f998)|0.58005|0.59062|0.00112|0.19%|0.58202|-0.02%|0.58190|-0.02%|4.701|0.071|1125632534|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/e4098da58a)|0.58047|0.58382|0.00065|0.11%|0.58181|-0.06%|0.58179|-0.04%|0.710|0.001|1125636846|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e4098da58a)|0.51878|0.52191|0.00056|0.11%|0.51959|-10.75%|0.51952|-10.74%|1.748|0.000|871695599|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42950|0.44516|0.00240|0.55%|0.43405|0.00%|0.43384|0.00%|1.170|0.999|2020638155|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb63e4f998)|0.42418|0.44164|0.00271|0.63%|0.42814|-1.36%|0.42755|-1.45%|2.565|0.000|2020586642|27.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/e4098da58a)|0.42504|0.43981|0.00311|0.73%|0.42837|-1.31%|0.42728|-1.51%|1.948|0.000|2020586804|27.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e4098da58a)|0.13840|0.14990|0.00146|0.99%|0.14684|-66.17%|0.14673|-66.18%|-1.688|0.000|536605627|27.93 MB|
