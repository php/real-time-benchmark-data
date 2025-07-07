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
| Kernel        |6.1.141-155.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250623|
| GCC           |11.5.0|
| Time          |2025-07-07 00:49:58 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43539|0.44443|0.00138|0.44104|0.00%|0.44093|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/677a1f80c8)|0.43700|0.43843|0.00035|0.43761|-0.78%|0.43761|-0.75%|42.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1ed6088a6)|0.43895|0.44209|0.00065|0.43970|-0.30%|0.43954|-0.32%|42.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1ed6088a6)|0.42272|0.42435|0.00045|0.42343|-3.99%|0.42337|-3.98%|51.62 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71264|0.71572|0.00067|0.71372|0.00%|0.71367|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/677a1f80c8)|0.70539|0.71042|0.00092|0.70889|-0.68%|0.70890|-0.67%|38.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1ed6088a6)|0.70757|0.71068|0.00077|0.70891|-0.67%|0.70878|-0.68%|38.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1ed6088a6)|0.67897|0.68206|0.00081|0.68052|-4.65%|0.68043|-4.66%|45.23 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58249|0.58558|0.00061|0.58321|0.00%|0.58312|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/677a1f80c8)|0.58224|0.58548|0.00077|0.58319|-0.00%|0.58306|-0.01%|43.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1ed6088a6)|0.57783|0.58430|0.00129|0.57974|-0.60%|0.57948|-0.62%|43.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1ed6088a6)|0.52562|0.52731|0.00050|0.52649|-9.73%|0.52651|-9.71%|61.66 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.22186|0.22682|0.00112|0.22409|0.00%|0.22414|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/677a1f80c8)|0.21942|0.22364|0.00097|0.22098|-1.39%|0.22075|-1.51%|26.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1ed6088a6)|0.21645|0.21874|0.00061|0.21753|-2.93%|0.21745|-2.98%|26.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1ed6088a6)|0.07664|0.07897|0.00064|0.07768|-65.34%|0.07768|-65.34%|28.03 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.43005|1.44824|0.00437|1.43956|0.00%|1.44039|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/677a1f80c8)|1.28123|1.29444|0.00370|1.28930|-10.44%|1.28990|-10.45%|21.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1ed6088a6)|1.28686|1.30300|0.00364|1.29435|-10.09%|1.29459|-10.12%|21.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1ed6088a6)|0.54187|0.56205|0.00477|0.55227|-61.64%|0.55178|-61.69%|22.48 MB|
