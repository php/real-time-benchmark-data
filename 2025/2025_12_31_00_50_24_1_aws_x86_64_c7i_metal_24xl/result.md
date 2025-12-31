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
| Time          |2025-12-31 00:50:24 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46838|0.47764|0.00098|0.21%|0.47564|0.00%|0.47560|0.00%|-4.120|0.999|180943889|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/434b14e4a3)|0.46502|0.47333|0.00097|0.21%|0.46954|-1.28%|0.46941|-1.30%|0.856|0.000|176408521|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/bc15a0dd4c)|0.47041|0.47344|0.00060|0.13%|0.47150|-0.87%|0.47142|-0.88%|0.831|0.000|176399229|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bc15a0dd4c)|0.44917|0.45438|0.00070|0.16%|0.45008|-5.37%|0.45002|-5.38%|3.558|0.000|147895907|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74302|0.75424|0.00138|0.19%|0.74523|0.00%|0.74499|0.00%|2.953|0.999|291625326|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/434b14e4a3)|0.74497|0.75529|0.00146|0.19%|0.74685|0.22%|0.74664|0.22%|2.645|0.000|290411358|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/bc15a0dd4c)|0.74401|0.75559|0.00193|0.26%|0.74663|0.19%|0.74621|0.16%|2.082|0.000|290409412|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bc15a0dd4c)|0.71076|0.72279|0.00149|0.21%|0.71925|-3.49%|0.71916|-3.47%|-1.463|0.000|270761816|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57592|0.58376|0.00212|0.37%|0.57974|0.00%|0.58061|0.00%|-0.361|0.999|1123343972|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/434b14e4a3)|0.57533|0.58729|0.00224|0.39%|0.57892|-0.14%|0.57940|-0.21%|0.698|0.000|1119536479|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/bc15a0dd4c)|0.57594|0.59067|0.00237|0.41%|0.57987|0.02%|0.58081|0.03%|0.568|0.383|1119535147|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bc15a0dd4c)|0.51382|0.51909|0.00145|0.28%|0.51700|-10.82%|0.51765|-10.84%|-0.463|0.000|865596163|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42423|0.44079|0.00430|1.00%|0.43152|0.00%|0.43178|0.00%|0.114|0.999|2020638088|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/434b14e4a3)|0.42186|0.43613|0.00281|0.66%|0.42636|-1.20%|0.42610|-1.31%|1.163|0.000|2020586707|27.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/bc15a0dd4c)|0.42208|0.47841|0.00604|1.41%|0.42722|-1.00%|0.42620|-1.29%|6.427|0.000|2020586654|27.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bc15a0dd4c)|0.13604|0.14914|0.00391|2.71%|0.14399|-66.63%|0.14573|-66.25%|-0.445|0.000|536605646|27.93 MB|
