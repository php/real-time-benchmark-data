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
| Time          |2025-12-25 00:50:27 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47668|0.48435|0.00090|0.19%|0.47821|0.00%|0.47802|0.00%|3.327|0.999|180942813|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/341d2d1bdc)|0.46951|0.47613|0.00089|0.19%|0.47110|-1.49%|0.47094|-1.48%|3.154|0.000|176329095|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/e861608eee)|0.46971|0.47319|0.00074|0.16%|0.47096|-1.52%|0.47078|-1.51%|0.775|0.000|176404766|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e861608eee)|0.45006|0.45294|0.00053|0.12%|0.45135|-5.62%|0.45127|-5.60%|0.459|0.000|147897863|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74574|0.74932|0.00078|0.10%|0.74747|0.00%|0.74748|0.00%|0.328|0.999|291622023|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/341d2d1bdc)|0.74456|0.75629|0.00124|0.17%|0.74636|-0.15%|0.74623|-0.17%|5.289|0.000|290414856|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/e861608eee)|0.74280|0.75398|0.00141|0.19%|0.74472|-0.37%|0.74456|-0.39%|3.313|0.000|290409551|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e861608eee)|0.71217|0.72265|0.00105|0.15%|0.72047|-3.61%|0.72062|-3.59%|-5.010|0.000|270766469|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58032|0.58501|0.00085|0.15%|0.58174|0.00%|0.58167|0.00%|1.336|0.999|1123345305|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/341d2d1bdc)|0.57980|0.58306|0.00061|0.10%|0.58110|-0.11%|0.58104|-0.11%|0.781|0.000|1119533915|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/e861608eee)|0.57931|0.58966|0.00118|0.20%|0.58098|-0.13%|0.58080|-0.15%|4.305|0.000|1119536515|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e861608eee)|0.51575|0.51921|0.00051|0.10%|0.51753|-11.04%|0.51749|-11.03%|0.144|0.000|865596525|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42706|0.43908|0.00224|0.52%|0.43427|0.00%|0.43447|0.00%|-0.460|0.999|2020638146|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/341d2d1bdc)|0.42452|0.48018|0.00785|1.83%|0.42857|-1.31%|0.42692|-1.74%|5.873|0.000|2020586617|27.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/e861608eee)|0.42330|0.48454|0.00802|1.87%|0.42844|-1.34%|0.42686|-1.75%|6.238|0.000|2020586640|27.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e861608eee)|0.14412|0.15043|0.00129|0.88%|0.14698|-66.16%|0.14683|-66.20%|0.339|0.000|536605669|27.87 MB|
