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
| Kernel        |6.12.55-74.119.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251110|
| GCC           |14.2.1|
| Time          |2025-11-14 00:50:12 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47209|0.47714|0.00082|0.17%|0.47337|0.00%|0.47320|0.00%|1.741|0.999|180950452|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4227106f37)|0.46503|0.46883|0.00073|0.16%|0.46609|-1.54%|0.46596|-1.53%|1.440|0.000|176331765|43.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/9cd367362d)|0.46371|0.46814|0.00083|0.18%|0.46491|-1.79%|0.46481|-1.77%|1.958|0.000|176323219|43.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9cd367362d)|0.44455|0.44747|0.00048|0.11%|0.44552|-5.88%|0.44547|-5.86%|0.972|0.000|147888198|53.21 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70066|0.72780|0.00228|0.32%|0.71142|0.00%|0.71114|0.00%|2.973|0.999|291622169|40.13 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4227106f37)|0.69994|0.72744|0.00287|0.40%|0.71110|-0.05%|0.71053|-0.09%|3.154|0.000|290393772|40.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/9cd367362d)|0.70759|0.73216|0.00251|0.35%|0.70994|-0.21%|0.70954|-0.23%|7.226|0.000|290399541|40.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9cd367362d)|0.68194|0.68801|0.00122|0.18%|0.68336|-3.94%|0.68307|-3.95%|2.024|0.000|270764890|47.21 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57481|0.57992|0.00088|0.15%|0.57617|0.00%|0.57602|0.00%|1.450|0.999|1123346600|43.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4227106f37)|0.57382|0.57703|0.00057|0.10%|0.57508|-0.19%|0.57499|-0.18%|0.687|0.000|1119580330|43.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/9cd367362d)|0.57161|0.57507|0.00072|0.13%|0.57286|-0.58%|0.57281|-0.56%|0.781|0.000|1119629620|43.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9cd367362d)|0.51136|0.51470|0.00069|0.13%|0.51281|-11.00%|0.51273|-10.99%|0.439|0.000|865686835|61.33 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43049|0.43940|0.00178|0.41%|0.43334|0.00%|0.43320|0.00%|0.734|0.999|2020638196|26.32 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4227106f37)|0.42583|0.48057|0.00600|1.39%|0.43053|-0.65%|0.42916|-0.93%|6.212|0.000|2020586620|26.66 MB|
|[PHP - master](https://github.com/php/php-src/commit/9cd367362d)|0.42509|0.47976|0.00574|1.34%|0.42916|-0.97%|0.42792|-1.22%|7.159|0.000|2020586648|26.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9cd367362d)|0.14695|0.15202|0.00091|0.61%|0.14882|-65.66%|0.14878|-65.66%|0.680|0.000|536605666|27.55 MB|
