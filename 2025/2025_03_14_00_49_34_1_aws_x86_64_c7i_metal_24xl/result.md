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
| Time          |2025-03-14 00:49:34 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43880|0.44289|0.00076|0.43969|0.00%|0.43953|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7faa3decd9)|0.43574|0.43735|0.00041|0.43637|-0.76%|0.43632|-0.73%|41.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa1effdb3c)|0.43708|0.43896|0.00050|0.43782|-0.43%|0.43775|-0.40%|41.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa1effdb3c)|0.42664|0.42856|0.00049|0.42731|-2.82%|0.42729|-2.79%|50.81 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71364|0.71702|0.00076|0.71493|0.00%|0.71489|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7faa3decd9)|0.70467|0.71856|0.00239|0.70613|-1.23%|0.70576|-1.28%|37.56 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa1effdb3c)|0.70425|0.70669|0.00056|0.70522|-1.36%|0.70518|-1.36%|37.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa1effdb3c)|0.67991|0.68349|0.00079|0.68113|-4.73%|0.68097|-4.74%|44.57 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58029|0.58325|0.00080|0.58173|0.00%|0.58159|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7faa3decd9)|0.57855|0.58222|0.00080|0.57952|-0.38%|0.57926|-0.40%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa1effdb3c)|0.57986|0.58228|0.00059|0.58139|-0.06%|0.58133|-0.04%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa1effdb3c)|0.52060|0.52272|0.00053|0.52164|-10.33%|0.52164|-10.31%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21455|0.21939|0.00095|0.21592|0.00%|0.21585|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7faa3decd9)|0.21815|0.22113|0.00066|0.21918|1.51%|0.21903|1.47%|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa1effdb3c)|0.21301|0.21488|0.00040|0.21382|-0.97%|0.21377|-0.96%|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa1effdb3c)|0.07482|0.07729|0.00060|0.07616|-64.73%|0.07631|-64.64%|27.39 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33845|1.36407|0.00629|1.35133|0.00%|1.35064|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7faa3decd9)|1.28301|1.30944|0.00585|1.29268|-4.34%|1.29239|-4.31%|20.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa1effdb3c)|1.25702|1.27506|0.00474|1.26405|-6.46%|1.26332|-6.47%|20.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa1effdb3c)|0.52849|0.54373|0.00407|0.53754|-60.22%|0.53783|-60.18%|21.81 MB|
