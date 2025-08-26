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
| GCC           |11.5.0|
| Time          |2025-08-26 00:50:01 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46835|0.47485|0.00079|0.17%|0.47190|0.00%|0.47177|0.00%|0.403|0.999|181824955|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.46615|0.46877|0.00047|0.10%|0.46740|-0.95%|0.46734|-0.94%|0.098|0.000|177210763|43.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/99068da2b1)|0.46703|0.47279|0.00066|0.14%|0.46787|-0.85%|0.46777|-0.85%|4.373|0.000|177215741|43.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/99068da2b1)|0.44283|0.45052|0.00074|0.17%|0.44947|-4.75%|0.44955|-4.71%|-7.278|0.000|149580728|53.79 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74106|0.74501|0.00083|0.11%|0.74295|0.00%|0.74295|0.00%|0.060|0.999|292381763|39.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.72523|0.74421|0.00201|0.27%|0.73445|-1.14%|0.73417|-1.18%|1.626|0.000|288310168|40.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/99068da2b1)|0.73283|0.74463|0.00234|0.32%|0.73505|-1.06%|0.73448|-1.14%|2.884|0.000|288324644|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/99068da2b1)|0.70199|0.70775|0.00106|0.15%|0.70350|-5.31%|0.70326|-5.34%|1.633|0.000|267489623|48.06 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58304|0.58628|0.00067|0.12%|0.58416|0.00%|0.58402|0.00%|0.982|0.999|1133181476|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.58352|0.59184|0.00099|0.17%|0.58470|0.09%|0.58452|0.09%|4.515|0.000|1129323571|43.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/99068da2b1)|0.58198|0.59324|0.00123|0.21%|0.58311|-0.18%|0.58290|-0.19%|5.967|0.000|1129267577|43.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/99068da2b1)|0.51341|0.51864|0.00062|0.12%|0.51740|-11.43%|0.51737|-11.41%|-2.376|0.000|867859217|61.46 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42649|0.43593|0.00182|0.42%|0.43141|0.00%|0.43111|0.00%|0.265|0.999|2031002343|26.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.42941|0.59144|0.02556|5.82%|0.43884|1.72%|0.43305|0.45%|4.484|0.000|2031543226|26.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/99068da2b1)|0.42790|0.56330|0.03475|7.88%|0.44102|2.23%|0.43021|-0.21%|2.926|0.000|2031543239|26.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/99068da2b1)|0.14637|0.15115|0.00103|0.70%|0.14814|-65.66%|0.14813|-65.64%|0.398|0.000|537062436|27.91 MB|
