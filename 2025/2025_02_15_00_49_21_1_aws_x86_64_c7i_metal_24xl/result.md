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
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250211|
| GCC           |11.4.1|
| Time          |2025-02-15 00:49:21 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43894|0.45345|0.00219|0.44051|0.00%|0.44011|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/78d934ad8e)|0.43532|0.44392|0.00116|0.43641|-0.93%|0.43623|-0.88%|41.84 MB|
|[PHP - master](https://github.com/php/php-src/commit/c696087e32)|0.43726|0.44472|0.00105|0.43841|-0.48%|0.43810|-0.46%|41.84 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c696087e32)|0.42526|0.42709|0.00042|0.42618|-3.25%|0.42616|-3.17%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71250|0.71629|0.00085|0.71415|0.00%|0.71403|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/78d934ad8e)|0.70764|0.71158|0.00076|0.70890|-0.74%|0.70878|-0.73%|37.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/c696087e32)|0.71044|0.71388|0.00078|0.71159|-0.36%|0.71141|-0.37%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c696087e32)|0.68347|0.68700|0.00075|0.68444|-4.16%|0.68425|-4.17%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58123|0.58327|0.00048|0.58203|0.00%|0.58194|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/78d934ad8e)|0.57506|0.58234|0.00108|0.57945|-0.44%|0.57947|-0.42%|42.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/c696087e32)|0.57622|0.57857|0.00057|0.57740|-0.79%|0.57745|-0.77%|42.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c696087e32)|0.52036|0.52266|0.00045|0.52130|-10.43%|0.52125|-10.43%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21475|0.21937|0.00103|0.21666|0.00%|0.21642|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/78d934ad8e)|0.21503|0.21943|0.00101|0.21678|0.05%|0.21655|0.06%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/c696087e32)|0.21556|0.21993|0.00100|0.21734|0.31%|0.21728|0.40%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c696087e32)|0.07325|0.07733|0.00081|0.07503|-65.37%|0.07489|-65.40%|27.34 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33657|1.36612|0.00585|1.34973|0.00%|1.34830|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/78d934ad8e)|1.35272|1.36990|0.00406|1.36195|0.91%|1.36239|1.05%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/c696087e32)|1.27568|1.30464|0.00680|1.28804|-4.57%|1.28804|-4.47%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c696087e32)|0.51987|0.54512|0.00619|0.53142|-60.63%|0.53066|-60.64%|21.76 MB|
