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
| Time          |2025-10-02 00:50:03 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47531|0.47899|0.00065|0.14%|0.47722|0.00%|0.47720|0.00%|-0.149|0.999|180947354|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a3f0861f2e)|0.46443|0.47389|0.00098|0.21%|0.47113|-1.27%|0.47118|-1.26%|-2.895|0.000|176326908|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/3ac43296aa)|0.46807|0.47203|0.00072|0.15%|0.46987|-1.54%|0.46991|-1.53%|0.076|0.000|176399108|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3ac43296aa)|0.44983|0.45477|0.00074|0.16%|0.45160|-5.37%|0.45159|-5.37%|0.521|0.000|147886774|53.44 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73459|0.75219|0.00152|0.20%|0.74232|0.00%|0.74218|0.00%|1.541|0.999|291620859|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a3f0861f2e)|0.73620|0.74789|0.00144|0.19%|0.73826|-0.55%|0.73805|-0.56%|3.492|0.000|287342765|40.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/3ac43296aa)|0.73583|0.74737|0.00176|0.24%|0.73804|-0.58%|0.73754|-0.62%|2.773|0.000|287339145|40.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3ac43296aa)|0.70779|0.71238|0.00082|0.12%|0.70938|-4.44%|0.70930|-4.43%|0.770|0.000|267702131|47.84 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57648|0.58645|0.00115|0.20%|0.58281|0.00%|0.58281|0.00%|-2.198|0.999|1123401640|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a3f0861f2e)|0.58041|0.58428|0.00064|0.11%|0.58180|-0.17%|0.58167|-0.20%|1.066|0.000|1120303680|44.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/3ac43296aa)|0.58458|0.58855|0.00069|0.12%|0.58582|0.52%|0.58571|0.50%|1.423|0.000|1120313267|44.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3ac43296aa)|0.51884|0.52185|0.00055|0.11%|0.52013|-10.75%|0.52006|-10.77%|0.366|0.000|865491362|61.75 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43025|0.43821|0.00181|0.42%|0.43350|0.00%|0.43324|0.00%|0.192|0.999|2020638160|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a3f0861f2e)|0.43367|0.55719|0.02454|5.50%|0.44602|2.89%|0.43984|1.52%|3.780|0.000|2020595069|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/3ac43296aa)|0.43302|0.54015|0.02354|5.32%|0.44284|2.15%|0.43671|0.80%|3.749|0.000|2020595019|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3ac43296aa)|0.14697|0.15168|0.00104|0.69%|0.14930|-65.56%|0.14926|-65.55%|0.085|0.000|536613244|27.74 MB|
