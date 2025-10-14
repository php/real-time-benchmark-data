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
| Time          |2025-10-14 00:50:09 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47560|0.47893|0.00061|0.13%|0.47672|0.00%|0.47666|0.00%|1.273|0.999|180948056|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ec9420db8)|0.46976|0.47344|0.00070|0.15%|0.47066|-1.27%|0.47047|-1.30%|1.909|0.000|176328659|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/6cb21229f8)|0.47085|0.47467|0.00072|0.15%|0.47197|-1.00%|0.47183|-1.01%|1.731|0.000|176406122|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6cb21229f8)|0.45008|0.45221|0.00042|0.09%|0.45096|-5.40%|0.45092|-5.40%|0.492|0.000|147865294|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74040|0.75277|0.00171|0.23%|0.74190|0.00%|0.74150|0.00%|4.919|0.999|291621402|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ec9420db8)|0.73520|0.74650|0.00156|0.21%|0.73722|-0.63%|0.73690|-0.62%|3.127|0.000|287318612|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/6cb21229f8)|0.73533|0.74078|0.00116|0.16%|0.73719|-0.64%|0.73692|-0.62%|0.938|0.000|287318812|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6cb21229f8)|0.70713|0.71163|0.00083|0.12%|0.70857|-4.49%|0.70849|-4.45%|0.919|0.000|267678519|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57790|0.58747|0.00150|0.26%|0.58463|0.00%|0.58491|0.00%|-1.056|0.999|1123344063|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ec9420db8)|0.58234|0.58931|0.00135|0.23%|0.58610|0.25%|0.58646|0.26%|-0.625|0.000|1120237134|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/6cb21229f8)|0.58332|0.59050|0.00140|0.24%|0.58708|0.42%|0.58730|0.41%|-0.378|0.000|1120246424|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6cb21229f8)|0.51757|0.52246|0.00114|0.22%|0.52047|-10.97%|0.52074|-10.97%|-0.616|0.000|866299596|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42919|0.43911|0.00187|0.43%|0.43354|0.00%|0.43361|0.00%|0.185|0.999|2020638192|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ec9420db8)|0.43794|0.54837|0.02263|5.06%|0.44731|3.18%|0.44178|1.88%|4.107|0.000|2020595033|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/6cb21229f8)|0.43799|0.59122|0.03482|7.69%|0.45283|4.45%|0.44145|1.81%|2.874|0.000|2020595094|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6cb21229f8)|0.14749|0.15258|0.00109|0.73%|0.14952|-65.51%|0.14930|-65.57%|0.646|0.000|536613110|27.68 MB|
