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
| Time          |2025-11-09 00:50:14 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47739|0.48400|0.00090|0.19%|0.47874|0.00%|0.47859|0.00%|2.258|0.999|180946912|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5ab594cf01)|0.46772|0.47396|0.00084|0.18%|0.46896|-2.04%|0.46880|-2.05%|2.855|0.000|176368732|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/7b4270adf0)|0.46868|0.47525|0.00082|0.17%|0.46983|-1.86%|0.46972|-1.85%|3.428|0.000|176405540|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7b4270adf0)|0.44533|0.45272|0.00075|0.17%|0.45139|-5.71%|0.45141|-5.68%|-5.286|0.000|147884467|53.38 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74294|0.75377|0.00127|0.17%|0.74455|0.00%|0.74432|0.00%|3.999|0.999|291621132|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5ab594cf01)|0.73857|0.75058|0.00176|0.24%|0.74077|-0.51%|0.74040|-0.53%|3.632|0.000|290430562|40.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/7b4270adf0)|0.73858|0.75087|0.00177|0.24%|0.74246|-0.28%|0.74202|-0.31%|1.902|0.000|290378714|40.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7b4270adf0)|0.70863|0.71886|0.00107|0.15%|0.71639|-3.78%|0.71638|-3.75%|-3.733|0.000|270740984|47.85 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58119|0.59226|0.00118|0.20%|0.58274|0.00%|0.58259|0.00%|5.485|0.999|1123344242|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5ab594cf01)|0.57977|0.58327|0.00062|0.11%|0.58114|-0.27%|0.58102|-0.27%|0.558|0.000|1119600311|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/7b4270adf0)|0.58087|0.58409|0.00065|0.11%|0.58204|-0.12%|0.58196|-0.11%|0.446|0.000|1119601673|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7b4270adf0)|0.51537|0.52092|0.00065|0.12%|0.51907|-10.93%|0.51907|-10.90%|-1.481|0.000|865651821|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42958|0.44199|0.00211|0.49%|0.43371|0.00%|0.43348|0.00%|1.125|0.999|2020638165|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5ab594cf01)|0.42168|0.43929|0.00299|0.70%|0.42624|-1.72%|0.42528|-1.89%|2.367|0.000|2020586647|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/7b4270adf0)|0.42270|0.43499|0.00195|0.46%|0.42551|-1.89%|0.42509|-1.93%|2.677|0.000|2020586656|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7b4270adf0)|0.14674|0.15059|0.00088|0.59%|0.14875|-65.70%|0.14870|-65.70%|0.091|0.000|536605644|27.73 MB|
