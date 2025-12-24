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
| Time          |2025-12-24 00:50:33 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47703|0.48012|0.00071|0.15%|0.47825|0.00%|0.47812|0.00%|0.640|0.999|180944146|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ef87a146fb)|0.47044|0.47437|0.00076|0.16%|0.47186|-1.34%|0.47167|-1.35%|1.057|0.000|176333662|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/341d2d1bdc)|0.46968|0.47317|0.00066|0.14%|0.47102|-1.51%|0.47089|-1.51%|0.900|0.000|176406915|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/341d2d1bdc)|0.45051|0.45532|0.00057|0.13%|0.45133|-5.63%|0.45126|-5.62%|3.676|0.000|147890481|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74446|0.75705|0.00137|0.18%|0.74658|0.00%|0.74646|0.00%|4.610|0.999|291621922|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ef87a146fb)|0.74250|0.75292|0.00149|0.20%|0.74488|-0.23%|0.74460|-0.25%|2.155|0.000|290411145|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/341d2d1bdc)|0.74227|0.74876|0.00127|0.17%|0.74435|-0.30%|0.74404|-0.32%|1.362|0.000|290409782|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/341d2d1bdc)|0.71766|0.72119|0.00073|0.10%|0.71930|-3.65%|0.71929|-3.64%|0.127|0.000|270766390|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58008|0.58361|0.00072|0.12%|0.58134|0.00%|0.58124|0.00%|0.695|0.999|1123346653|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ef87a146fb)|0.57827|0.59124|0.00165|0.28%|0.58036|-0.17%|0.58012|-0.19%|4.938|0.000|1119533896|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/341d2d1bdc)|0.57965|0.58403|0.00078|0.13%|0.58089|-0.08%|0.58076|-0.08%|1.168|0.000|1119536297|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/341d2d1bdc)|0.51590|0.51889|0.00053|0.10%|0.51708|-11.05%|0.51702|-11.05%|0.732|0.000|865599603|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42940|0.44583|0.00245|0.56%|0.43459|0.00%|0.43445|0.00%|0.968|0.999|2020638197|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ef87a146fb)|0.42423|0.43767|0.00248|0.58%|0.42724|-1.69%|0.42662|-1.80%|2.046|0.000|2020586672|27.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/341d2d1bdc)|0.42453|0.43694|0.00237|0.55%|0.42751|-1.63%|0.42688|-1.74%|1.817|0.000|2020586644|27.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/341d2d1bdc)|0.14479|0.15105|0.00135|0.92%|0.14717|-66.14%|0.14690|-66.19%|0.729|0.000|536605631|27.87 MB|
