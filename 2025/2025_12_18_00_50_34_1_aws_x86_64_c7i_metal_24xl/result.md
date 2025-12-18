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
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2025-12-18 00:50:34 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47507|0.48202|0.00086|0.18%|0.47608|0.00%|0.47590|0.00%|3.585|0.999|180945370|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aee5fce6ff)|0.46857|0.47248|0.00071|0.15%|0.46961|-1.36%|0.46951|-1.34%|1.203|0.000|176329616|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/95abeba749)|0.46184|0.47251|0.00120|0.26%|0.46914|-1.46%|0.46909|-1.43%|-3.313|0.000|176398336|44.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95abeba749)|0.44752|0.45169|0.00054|0.12%|0.44850|-5.79%|0.44849|-5.76%|2.406|0.000|147877167|53.52 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74221|0.75282|0.00118|0.16%|0.74370|0.00%|0.74350|0.00%|4.814|0.999|291622032|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aee5fce6ff)|0.74231|0.75234|0.00154|0.21%|0.74451|0.11%|0.74416|0.09%|2.145|0.000|290419826|40.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/95abeba749)|0.74247|0.75275|0.00152|0.20%|0.74430|0.08%|0.74386|0.05%|2.833|0.000|290419900|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95abeba749)|0.70779|0.71850|0.00110|0.15%|0.71636|-3.68%|0.71635|-3.65%|-4.724|0.000|270764517|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57558|0.58135|0.00115|0.20%|0.57740|0.00%|0.57718|0.00%|1.629|0.999|1123346946|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aee5fce6ff)|0.57720|0.58864|0.00183|0.32%|0.57882|0.25%|0.57832|0.20%|3.734|0.000|1119537304|44.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/95abeba749)|0.57690|0.58824|0.00137|0.24%|0.57881|0.24%|0.57852|0.23%|4.106|0.000|1119540134|44.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95abeba749)|0.51231|0.51729|0.00075|0.15%|0.51399|-10.98%|0.51394|-10.96%|1.855|0.000|865603065|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42454|0.43863|0.00264|0.61%|0.43391|0.00%|0.43414|0.00%|-0.979|0.999|2020638188|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aee5fce6ff)|0.42144|0.43851|0.00293|0.69%|0.42727|-1.53%|0.42670|-1.71%|1.681|0.000|2020586470|27.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/95abeba749)|0.42327|0.47764|0.00796|1.86%|0.42869|-1.20%|0.42704|-1.64%|4.885|0.000|2020586661|27.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95abeba749)|0.13719|0.15104|0.00242|1.66%|0.14640|-66.26%|0.14660|-66.23%|-1.617|0.000|536605571|27.87 MB|
