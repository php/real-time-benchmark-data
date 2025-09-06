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
| Time          |2025-09-06 00:50:03 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46651|0.47638|0.00098|0.21%|0.47344|0.00%|0.47345|0.00%|-3.097|0.999|181238072|43.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/01ae278c47)|0.50770|0.51444|0.00089|0.18%|0.50922|7.56%|0.50909|7.53%|2.230|0.000|187314743|44.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/366a5a2b37)|0.50811|0.51446|0.00077|0.15%|0.50985|7.69%|0.50986|7.69%|2.000|0.000|187312058|44.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/366a5a2b37)|0.48116|0.48431|0.00058|0.12%|0.48309|2.04%|0.48307|2.03%|-0.515|0.000|155994145|54.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74164|0.74663|0.00096|0.13%|0.74364|0.00%|0.74349|0.00%|0.570|0.999|291542832|39.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/01ae278c47)|0.73531|0.74863|0.00183|0.25%|0.74024|-0.46%|0.74003|-0.46%|2.221|0.000|287262465|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/366a5a2b37)|0.72748|0.75040|0.00271|0.37%|0.73699|-0.89%|0.73645|-0.95%|2.089|0.000|287263066|40.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/366a5a2b37)|0.70885|0.71366|0.00095|0.13%|0.71067|-4.43%|0.71052|-4.43%|1.004|0.000|267615965|47.55 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57537|0.58239|0.00081|0.14%|0.58062|0.00%|0.58062|0.00%|-2.770|0.999|1123004512|43.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/01ae278c47)|0.58361|0.58659|0.00059|0.10%|0.58498|0.75%|0.58489|0.74%|0.178|0.000|1120663229|43.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/366a5a2b37)|0.58231|0.58569|0.00056|0.10%|0.58391|0.57%|0.58387|0.56%|-0.020|0.000|1120666221|43.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/366a5a2b37)|0.51904|0.52198|0.00052|0.10%|0.52094|-10.28%|0.52095|-10.28%|-0.468|0.000|867025579|61.46 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42881|0.44343|0.00231|0.53%|0.43192|0.00%|0.43149|0.00%|2.503|0.999|2020733114|26.37 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/01ae278c47)|0.42360|0.55457|0.02826|6.48%|0.43612|0.97%|0.42862|-0.67%|3.686|0.000|2020744521|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/366a5a2b37)|0.42427|0.54910|0.02630|6.06%|0.43370|0.41%|0.42705|-1.03%|3.762|0.000|2020744564|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/366a5a2b37)|0.14760|0.15222|0.00084|0.56%|0.14960|-65.36%|0.14958|-65.33%|0.361|0.000|536712500|28.01 MB|
