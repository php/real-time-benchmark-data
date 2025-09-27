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
| Time          |2025-09-27 00:49:55 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46974|0.47860|0.00088|0.18%|0.47640|0.00%|0.47639|0.00%|-4.100|0.999|180946338|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b930654b)|0.46885|0.47312|0.00065|0.14%|0.46971|-1.40%|0.46957|-1.43%|2.230|0.000|176329776|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b930654b)|0.46325|0.47221|0.00088|0.19%|0.46968|-1.41%|0.46964|-1.42%|-3.521|0.000|176402894|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b930654b)|0.44753|0.44983|0.00047|0.10%|0.44858|-5.84%|0.44850|-5.85%|0.506|0.000|147882692|53.44 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74052|0.75332|0.00181|0.24%|0.74195|0.00%|0.74153|0.00%|4.752|0.999|291622930|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b930654b)|0.73738|0.74203|0.00104|0.14%|0.73893|-0.41%|0.73872|-0.38%|0.821|0.000|287354427|40.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b930654b)|0.73699|0.75055|0.00191|0.26%|0.73919|-0.37%|0.73864|-0.39%|2.734|0.000|287354519|40.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b930654b)|0.70932|0.71291|0.00077|0.11%|0.71116|-4.15%|0.71110|-4.10%|0.054|0.000|267691058|47.58 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58059|0.59272|0.00131|0.22%|0.58248|0.00%|0.58227|0.00%|5.070|0.999|1123345516|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b930654b)|0.57872|0.58283|0.00083|0.14%|0.58074|-0.30%|0.58068|-0.27%|0.127|0.000|1120251960|44.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b930654b)|0.57862|0.58266|0.00077|0.13%|0.58051|-0.34%|0.58050|-0.30%|0.597|0.000|1120260856|44.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b930654b)|0.51555|0.52046|0.00071|0.14%|0.51813|-11.05%|0.51821|-11.00%|-0.191|0.000|866320755|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42978|0.44173|0.00202|0.47%|0.43352|0.00%|0.43326|0.00%|0.961|0.999|2020638221|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b930654b)|0.42759|0.54180|0.01918|4.41%|0.43521|0.39%|0.43108|-0.50%|4.748|0.000|2020595097|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/65b930654b)|0.42667|0.53666|0.01916|4.42%|0.43319|-0.08%|0.42900|-0.98%|4.769|0.000|2020595096|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65b930654b)|0.14773|0.15158|0.00087|0.58%|0.14921|-65.58%|0.14906|-65.60%|0.596|0.000|536613171|27.73 MB|
