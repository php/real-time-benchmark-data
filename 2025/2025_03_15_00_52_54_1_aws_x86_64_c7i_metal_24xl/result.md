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
| Kernel        |6.1.129-138.220.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250303|
| GCC           |11.4.1|
| Time          |2025-03-15 00:52:54 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43897|0.45056|0.00200|0.44000|0.00%|0.43966|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fa1effdb3c)|0.43650|0.43895|0.00061|0.43739|-0.59%|0.43721|-0.56%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/e954bf6750)|0.43793|0.44053|0.00054|0.43889|-0.25%|0.43884|-0.18%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e954bf6750)|0.42631|0.42819|0.00043|0.42728|-2.89%|0.42722|-2.83%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71296|0.71574|0.00060|0.71421|0.00%|0.71403|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fa1effdb3c)|0.70384|0.70761|0.00081|0.70500|-1.29%|0.70484|-1.29%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/e954bf6750)|0.70568|0.70849|0.00071|0.70723|-0.98%|0.70723|-0.95%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e954bf6750)|0.67804|0.68207|0.00100|0.67922|-4.90%|0.67892|-4.92%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58097|0.58300|0.00051|0.58176|0.00%|0.58164|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fa1effdb3c)|0.58016|0.58228|0.00054|0.58087|-0.15%|0.58079|-0.15%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/e954bf6750)|0.58066|0.58328|0.00068|0.58213|0.06%|0.58222|0.10%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e954bf6750)|0.52144|0.52331|0.00038|0.52230|-10.22%|0.52232|-10.20%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21472|0.21983|0.00127|0.21648|0.00%|0.21612|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fa1effdb3c)|0.21431|0.21863|0.00099|0.21553|-0.44%|0.21534|-0.36%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/e954bf6750)|0.21272|0.21582|0.00092|0.21389|-1.20%|0.21358|-1.18%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e954bf6750)|0.07477|0.07746|0.00068|0.07620|-64.80%|0.07620|-64.74%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34063|1.35572|0.00413|1.34889|0.00%|1.34828|0.00%|20.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fa1effdb3c)|1.25492|1.26721|0.00345|1.26126|-6.50%|1.26101|-6.47%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/e954bf6750)|1.25594|1.27125|0.00381|1.26266|-6.39%|1.26348|-6.29%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e954bf6750)|0.53353|0.55441|0.00515|0.54403|-59.67%|0.54471|-59.60%|21.79 MB|
