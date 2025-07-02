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
| Kernel        |6.1.141-155.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250623|
| GCC           |11.5.0|
| Time          |2025-07-02 00:49:49 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43891|0.45520|0.00257|0.44191|0.00%|0.44136|0.00%|42.03 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a98b36416)|0.44204|0.44414|0.00049|0.44284|0.21%|0.44287|0.34%|42.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/8a75b3c50c)|0.43938|0.44306|0.00080|0.44044|-0.33%|0.44027|-0.25%|42.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8a75b3c50c)|0.42535|0.42693|0.00044|0.42622|-3.55%|0.42623|-3.43%|51.60 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71363|0.71678|0.00072|0.71481|0.00%|0.71476|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a98b36416)|0.70766|0.71147|0.00089|0.70912|-0.80%|0.70892|-0.82%|38.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/8a75b3c50c)|0.70936|0.71272|0.00076|0.71079|-0.56%|0.71062|-0.58%|38.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8a75b3c50c)|0.68000|0.68231|0.00062|0.68121|-4.70%|0.68121|-4.69%|45.22 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58230|0.58503|0.00058|0.58367|0.00%|0.58363|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a98b36416)|0.58287|0.58531|0.00055|0.58392|0.04%|0.58387|0.04%|43.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/8a75b3c50c)|0.58373|0.58610|0.00061|0.58492|0.21%|0.58491|0.22%|43.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8a75b3c50c)|0.52581|0.52985|0.00081|0.52704|-9.70%|0.52686|-9.73%|61.65 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21419|0.21991|0.00117|0.21572|0.00%|0.21551|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a98b36416)|0.21405|0.22042|0.00122|0.21636|0.30%|0.21610|0.28%|26.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/8a75b3c50c)|0.21711|0.22100|0.00092|0.21861|1.34%|0.21834|1.32%|26.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8a75b3c50c)|0.07581|0.07842|0.00066|0.07659|-64.49%|0.07645|-64.53%|28.02 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41807|1.43633|0.00423|1.42827|0.00%|1.42898|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a98b36416)|1.30912|1.32352|0.00365|1.31736|-7.77%|1.31769|-7.79%|21.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/8a75b3c50c)|1.29497|1.30663|0.00292|1.30230|-8.82%|1.30252|-8.85%|21.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8a75b3c50c)|0.54246|0.55290|0.00286|0.54829|-61.61%|0.54849|-61.62%|22.45 MB|
