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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-05-27 00:49:55 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43827|0.45222|0.00263|0.43990|0.00%|0.43928|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/04522cd1c4)|0.43951|0.44740|0.00136|0.44046|0.13%|0.44021|0.21%|42.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/de785f9127)|0.43836|0.44169|0.00061|0.43941|-0.11%|0.43934|0.01%|42.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de785f9127)|0.42528|0.42701|0.00039|0.42618|-3.12%|0.42613|-2.99%|51.29 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71330|0.71734|0.00113|0.71489|0.00%|0.71475|0.00%|37.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/04522cd1c4)|0.71105|0.72260|0.00199|0.71249|-0.34%|0.71224|-0.35%|38.09 MB|
|[PHP - master](https://github.com/php/php-src/commit/de785f9127)|0.70988|0.71250|0.00082|0.71107|-0.53%|0.71088|-0.54%|38.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de785f9127)|0.67761|0.68097|0.00073|0.67883|-5.04%|0.67870|-5.04%|45.04 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57731|0.58357|0.00226|0.58036|0.00%|0.58136|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/04522cd1c4)|0.58159|0.58522|0.00079|0.58255|0.38%|0.58244|0.19%|43.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/de785f9127)|0.58127|0.58592|0.00083|0.58257|0.38%|0.58247|0.19%|43.60 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de785f9127)|0.52535|0.52695|0.00039|0.52606|-9.36%|0.52604|-9.52%|61.01 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21528|0.22016|0.00099|0.21689|0.00%|0.21684|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/04522cd1c4)|0.21842|0.22166|0.00095|0.21964|1.27%|0.21962|1.28%|26.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/de785f9127)|0.21899|0.22247|0.00080|0.22023|1.54%|0.22018|1.54%|26.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de785f9127)|0.07656|0.07871|0.00055|0.07766|-64.19%|0.07773|-64.15%|27.79 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34332|1.36416|0.00483|1.35051|0.00%|1.34952|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/04522cd1c4)|1.29800|1.31942|0.00432|1.30599|-3.30%|1.30657|-3.18%|20.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/de785f9127)|1.29188|1.30720|0.00371|1.30050|-3.70%|1.30045|-3.64%|20.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de785f9127)|0.54304|0.55691|0.00338|0.55068|-59.22%|0.55104|-59.17%|22.21 MB|
