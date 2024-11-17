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
| Kernel        |6.1.115-126.197.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241111|
| GCC           |11.4.1|
| Time          |2024-11-17 00:49:52 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43900|0.44099|0.00050|0.43983|0.00%|0.43981|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0de8e401db)|0.43538|0.43846|0.00051|0.43650|-0.76%|0.43646|-0.76%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/27a1d69504)|0.43664|0.43933|0.00048|0.43744|-0.54%|0.43746|-0.53%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27a1d69504)|0.42613|0.42794|0.00044|0.42694|-2.93%|0.42684|-2.95%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71346|0.71647|0.00060|0.71472|0.00%|0.71465|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0de8e401db)|0.70772|0.71278|0.00106|0.70948|-0.73%|0.70928|-0.75%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/27a1d69504)|0.71246|0.71558|0.00061|0.71416|-0.08%|0.71423|-0.06%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27a1d69504)|0.68161|0.68507|0.00066|0.68299|-4.44%|0.68295|-4.44%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58113|0.58401|0.00064|0.58239|0.00%|0.58225|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0de8e401db)|0.57829|0.58144|0.00066|0.57983|-0.44%|0.57967|-0.44%|43.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/27a1d69504)|0.57959|0.58220|0.00057|0.58054|-0.32%|0.58036|-0.32%|43.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27a1d69504)|0.51992|0.52220|0.00048|0.52096|-10.55%|0.52086|-10.54%|61.62 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21412|0.21969|0.00080|0.21618|0.00%|0.21615|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0de8e401db)|0.21503|0.21884|0.00097|0.21658|0.19%|0.21656|0.19%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/27a1d69504)|0.21214|0.21692|0.00099|0.21342|-1.28%|0.21310|-1.41%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27a1d69504)|0.07350|0.07637|0.00075|0.07483|-65.38%|0.07469|-65.45%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33709|1.36920|0.00657|1.35021|0.00%|1.34889|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0de8e401db)|1.28246|1.30853|0.00611|1.29378|-4.18%|1.29349|-4.11%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/27a1d69504)|1.27069|1.29863|0.00638|1.28625|-4.74%|1.28653|-4.62%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27a1d69504)|0.53031|0.55577|0.00584|0.54148|-59.90%|0.54114|-59.88%|21.69 MB|
