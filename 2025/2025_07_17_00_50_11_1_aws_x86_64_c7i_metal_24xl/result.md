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
| Kernel        |6.1.141-165.249.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250707|
| GCC           |11.5.0|
| Time          |2025-07-17 00:50:11 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43731|0.44224|0.00086|0.44139|0.00%|0.44145|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/02b94556cf)|0.43784|0.44636|0.00194|0.43941|-0.45%|0.43867|-0.63%|42.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e0c011fb8)|0.43830|0.44125|0.00089|0.43936|-0.46%|0.43910|-0.53%|42.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e0c011fb8)|0.42363|0.42477|0.00024|0.42436|-3.86%|0.42437|-3.87%|51.52 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71258|0.71556|0.00071|0.71392|0.00%|0.71385|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/02b94556cf)|0.71024|0.71433|0.00103|0.71162|-0.32%|0.71129|-0.36%|38.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e0c011fb8)|0.70828|0.71242|0.00094|0.70994|-0.56%|0.70979|-0.57%|38.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e0c011fb8)|0.67921|0.68220|0.00066|0.68026|-4.72%|0.68028|-4.70%|45.13 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58231|0.58448|0.00058|0.58315|0.00%|0.58308|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/02b94556cf)|0.57832|0.58522|0.00214|0.58120|-0.33%|0.58032|-0.47%|43.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e0c011fb8)|0.58065|0.58429|0.00072|0.58192|-0.21%|0.58181|-0.22%|43.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e0c011fb8)|0.52278|0.52467|0.00046|0.52360|-10.21%|0.52361|-10.20%|62.17 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21391|0.22109|0.00144|0.21568|0.00%|0.21515|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/02b94556cf)|0.21629|0.21897|0.00065|0.21768|0.93%|0.21752|1.10%|26.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e0c011fb8)|0.21206|0.21637|0.00105|0.21395|-0.80%|0.21371|-0.67%|26.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e0c011fb8)|0.07497|0.07731|0.00067|0.07630|-64.62%|0.07653|-64.43%|27.91 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41918|1.44570|0.00573|1.43013|0.00%|1.42917|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/02b94556cf)|1.27687|1.29334|0.00366|1.28382|-10.23%|1.28374|-10.18%|21.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e0c011fb8)|1.31652|1.33334|0.00484|1.32738|-7.18%|1.32955|-6.97%|20.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e0c011fb8)|0.55285|0.56485|0.00321|0.55868|-60.94%|0.55868|-60.91%|22.35 MB|
