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
| OS            |Amazon Linux 2023.8.20250715|
| GCC           |11.5.0|
| Time          |2025-07-22 00:49:54 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44030|0.45229|0.00207|0.44150|0.00%|0.44111|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e91d2c719f)|0.43814|0.44011|0.00052|0.43891|-0.59%|0.43885|-0.51%|42.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/113eb203b0)|0.43894|0.44178|0.00060|0.43986|-0.37%|0.43984|-0.29%|42.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/113eb203b0)|0.42401|0.42541|0.00033|0.42493|-3.75%|0.42493|-3.67%|51.46 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71292|0.71590|0.00077|0.71396|0.00%|0.71380|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e91d2c719f)|0.71038|0.71527|0.00117|0.71222|-0.24%|0.71204|-0.25%|38.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/113eb203b0)|0.71177|0.72463|0.00294|0.71392|-0.01%|0.71296|-0.12%|38.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/113eb203b0)|0.67870|0.68232|0.00081|0.68041|-4.70%|0.68031|-4.69%|45.07 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58207|0.58598|0.00086|0.58407|0.00%|0.58390|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e91d2c719f)|0.58275|0.58521|0.00052|0.58379|-0.05%|0.58387|-0.01%|43.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/113eb203b0)|0.58239|0.58393|0.00045|0.58305|-0.18%|0.58303|-0.15%|43.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/113eb203b0)|0.52436|0.52652|0.00050|0.52545|-10.04%|0.52548|-10.01%|62.18 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21461|0.21932|0.00119|0.21613|0.00%|0.21582|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e91d2c719f)|0.21684|0.21926|0.00059|0.21791|0.82%|0.21772|0.88%|26.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/113eb203b0)|0.21644|0.21865|0.00059|0.21753|0.65%|0.21752|0.79%|26.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/113eb203b0)|0.07563|0.07840|0.00084|0.07695|-64.40%|0.07701|-64.32%|27.92 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42062|1.43671|0.00452|1.42871|0.00%|1.42868|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e91d2c719f)|1.32320|1.33964|0.00386|1.33228|-6.75%|1.33195|-6.77%|21.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/113eb203b0)|1.30191|1.32426|0.00554|1.31347|-8.07%|1.31487|-7.97%|21.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/113eb203b0)|0.55246|0.56947|0.00444|0.56175|-60.68%|0.56220|-60.65%|22.36 MB|
