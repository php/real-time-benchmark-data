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
| GCC           |11.5.0|
| Time          |2025-08-22 00:50:06 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46816|0.47684|0.00091|0.19%|0.47380|0.00%|0.47370|0.00%|-1.579|0.999|181823376|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0bf295944d)|0.46798|0.47017|0.00049|0.10%|0.46904|-1.01%|0.46906|-0.98%|0.041|0.000|177210426|43.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a1789cc34)|0.46916|0.47168|0.00051|0.11%|0.47021|-0.76%|0.47012|-0.76%|0.480|0.000|177210430|43.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a1789cc34)|0.45261|0.45479|0.00049|0.11%|0.45362|-4.26%|0.45363|-4.24%|0.202|0.000|149593188|53.79 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74333|0.74915|0.00100|0.13%|0.74511|0.00%|0.74501|0.00%|1.037|0.999|292381767|39.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0bf295944d)|0.72821|0.74973|0.00205|0.28%|0.73796|-0.96%|0.73773|-0.98%|1.449|0.000|288310081|40.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a1789cc34)|0.72838|0.74921|0.00276|0.37%|0.74074|-0.59%|0.74019|-0.65%|0.790|0.000|288310227|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a1789cc34)|0.70484|0.71094|0.00125|0.18%|0.70659|-5.17%|0.70630|-5.20%|2.141|0.000|267474929|48.06 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58272|0.59395|0.00115|0.20%|0.58420|0.00%|0.58404|0.00%|6.252|0.999|1133180536|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0bf295944d)|0.57648|0.58297|0.00080|0.14%|0.58144|-0.47%|0.58140|-0.45%|-2.258|0.000|1129323802|43.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a1789cc34)|0.58341|0.58597|0.00063|0.11%|0.58452|0.06%|0.58440|0.06%|0.315|0.000|1129325713|43.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a1789cc34)|0.51741|0.52154|0.00063|0.12%|0.51894|-11.17%|0.51888|-11.16%|0.782|0.000|867868028|61.47 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42658|0.44709|0.00251|0.58%|0.43181|0.00%|0.43168|0.00%|2.307|0.999|2031002274|26.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0bf295944d)|0.43434|0.55849|0.02714|6.11%|0.44385|2.79%|0.43677|1.18%|3.752|0.000|2031543276|26.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a1789cc34)|0.42730|0.55613|0.02925|6.69%|0.43743|1.30%|0.42993|-0.41%|3.748|0.000|2031543279|26.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a1789cc34)|0.14604|0.15132|0.00118|0.80%|0.14788|-65.75%|0.14777|-65.77%|0.961|0.000|537062411|27.91 MB|
