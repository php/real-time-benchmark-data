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
| Time          |2025-10-24 00:50:06 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47752|0.48491|0.00090|0.19%|0.47866|0.00%|0.47850|0.00%|3.598|0.999|180949046|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f8656fae35)|0.47118|0.47441|0.00073|0.16%|0.47225|-1.34%|0.47209|-1.34%|1.122|0.000|176331693|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/27948dcee7)|0.46957|0.47531|0.00077|0.16%|0.47097|-1.61%|0.47082|-1.61%|2.138|0.000|176383835|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27948dcee7)|0.44717|0.45451|0.00076|0.17%|0.45321|-5.32%|0.45320|-5.29%|-5.040|0.000|147853007|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73233|0.74590|0.00131|0.18%|0.74346|0.00%|0.74353|0.00%|-6.155|0.999|291621381|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f8656fae35)|0.73694|0.74623|0.00168|0.23%|0.73905|-0.59%|0.73848|-0.68%|1.976|0.000|287318854|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/27948dcee7)|0.73600|0.75049|0.00245|0.33%|0.73897|-0.60%|0.73831|-0.70%|2.332|0.000|287324423|40.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27948dcee7)|0.70788|0.71303|0.00096|0.13%|0.70959|-4.56%|0.70945|-4.58%|1.202|0.000|267684128|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58126|0.64910|0.01525|2.60%|0.58679|0.00%|0.58303|0.00%|3.751|0.999|1123344663|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f8656fae35)|0.58170|0.64958|0.01509|2.57%|0.58676|-0.01%|0.58289|-0.02%|3.755|0.858|1120065999|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/27948dcee7)|0.58421|0.65169|0.01646|2.79%|0.59026|0.59%|0.58577|0.47%|3.419|0.000|1120082205|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27948dcee7)|0.51747|0.59064|0.01692|3.23%|0.52368|-10.76%|0.51900|-10.98%|3.401|0.000|866132305|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42998|0.43754|0.00181|0.42%|0.43332|0.00%|0.43316|0.00%|0.138|0.999|2020638211|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f8656fae35)|0.42351|0.43622|0.00235|0.55%|0.42679|-1.51%|0.42621|-1.61%|1.898|0.000|2020586555|26.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/27948dcee7)|0.42342|0.43837|0.00267|0.63%|0.42724|-1.40%|0.42658|-1.52%|1.903|0.000|2020586600|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27948dcee7)|0.14393|0.14980|0.00126|0.86%|0.14670|-66.15%|0.14667|-66.14%|0.229|0.000|536605557|27.67 MB|
