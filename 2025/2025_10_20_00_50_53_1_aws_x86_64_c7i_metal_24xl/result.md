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
| Time          |2025-10-20 00:50:53 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47560|0.47812|0.00054|0.11%|0.47668|0.00%|0.47656|0.00%|0.671|0.999|180947095|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/81fef09d01)|0.46776|0.47135|0.00065|0.14%|0.46903|-1.60%|0.46887|-1.61%|1.581|0.000|176333406|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6c52bc26a)|0.46744|0.47357|0.00074|0.16%|0.46859|-1.70%|0.46850|-1.69%|3.531|0.000|176406786|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6c52bc26a)|0.44890|0.45384|0.00067|0.15%|0.45000|-5.60%|0.44989|-5.60%|2.486|0.000|147870379|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74094|0.74480|0.00068|0.09%|0.74243|0.00%|0.74242|0.00%|0.540|0.999|291621396|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/81fef09d01)|0.72712|0.74654|0.00234|0.32%|0.73803|-0.59%|0.73753|-0.66%|0.687|0.000|287318844|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6c52bc26a)|0.73508|0.74732|0.00209|0.28%|0.73810|-0.58%|0.73759|-0.65%|2.840|0.000|287318845|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6c52bc26a)|0.70619|0.71040|0.00071|0.10%|0.70727|-4.74%|0.70714|-4.75%|1.400|0.000|267682111|47.79 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57991|0.59140|0.00158|0.27%|0.58202|0.00%|0.58173|0.00%|4.250|0.999|1123346751|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/81fef09d01)|0.58254|0.58639|0.00073|0.13%|0.58424|0.38%|0.58417|0.42%|0.643|0.000|1120067165|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6c52bc26a)|0.58181|0.58551|0.00069|0.12%|0.58374|0.30%|0.58367|0.33%|0.235|0.000|1120075036|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6c52bc26a)|0.51679|0.51993|0.00058|0.11%|0.51822|-10.96%|0.51815|-10.93%|0.271|0.000|866125132|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42945|0.44313|0.00231|0.53%|0.43401|0.00%|0.43392|0.00%|1.008|0.999|2020638193|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/81fef09d01)|0.42216|0.47797|0.00579|1.35%|0.42757|-1.48%|0.42630|-1.76%|6.922|0.000|2020586539|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6c52bc26a)|0.42348|0.43887|0.00277|0.65%|0.42686|-1.65%|0.42603|-1.82%|2.289|0.000|2020586536|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6c52bc26a)|0.14460|0.15168|0.00129|0.88%|0.14688|-66.16%|0.14680|-66.17%|0.698|0.000|536605640|27.68 MB|
