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
| Time          |2025-10-15 00:50:08 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47566|0.47826|0.00053|0.11%|0.47668|0.00%|0.47662|0.00%|0.837|0.999|180945729|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6cb21229f8)|0.47075|0.47460|0.00076|0.16%|0.47191|-1.00%|0.47172|-1.03%|1.555|0.000|176328716|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/e2da92b15c)|0.46429|0.47382|0.00103|0.22%|0.47130|-1.13%|0.47117|-1.14%|-2.664|0.000|176404810|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e2da92b15c)|0.45033|0.45441|0.00071|0.16%|0.45164|-5.25%|0.45148|-5.27%|1.124|0.000|147870969|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74030|0.75273|0.00169|0.23%|0.74171|0.00%|0.74136|0.00%|5.261|0.999|291621380|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6cb21229f8)|0.73209|0.74071|0.00107|0.14%|0.73657|-0.69%|0.73650|-0.66%|0.236|0.000|287318615|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/e2da92b15c)|0.73625|0.74544|0.00169|0.23%|0.73843|-0.44%|0.73818|-0.43%|2.128|0.000|287318812|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e2da92b15c)|0.70981|0.71386|0.00072|0.10%|0.71110|-4.13%|0.71093|-4.10%|1.154|0.000|267681545|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58099|0.58508|0.00089|0.15%|0.58284|0.00%|0.58289|0.00%|0.311|0.999|1123343239|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6cb21229f8)|0.58302|0.58823|0.00104|0.18%|0.58528|0.42%|0.58514|0.39%|0.563|0.000|1120236530|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/e2da92b15c)|0.58347|0.58800|0.00088|0.15%|0.58561|0.48%|0.58555|0.46%|0.308|0.000|1120246302|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e2da92b15c)|0.51628|0.52103|0.00071|0.14%|0.51808|-11.11%|0.51808|-11.12%|0.214|0.000|866295691|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43019|0.44194|0.00223|0.51%|0.43382|0.00%|0.43345|0.00%|1.041|0.999|2020638146|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6cb21229f8)|0.43667|0.55536|0.02693|6.00%|0.44854|3.39%|0.44106|1.76%|3.414|0.000|2020595073|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/e2da92b15c)|0.43615|0.55004|0.02263|5.07%|0.44627|2.87%|0.44092|1.72%|4.158|0.000|2020595067|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e2da92b15c)|0.14734|0.15209|0.00101|0.67%|0.14943|-65.56%|0.14925|-65.57%|0.372|0.000|536613066|27.68 MB|
