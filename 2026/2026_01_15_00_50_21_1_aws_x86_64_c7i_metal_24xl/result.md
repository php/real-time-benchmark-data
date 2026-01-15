### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-15 00:50:21 UTC|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46055|0.46480|0.00084|0.18%|0.46134|0.00%|0.46113|0.00%|2.759|0.999|185279511|27.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/858d34fd32)|0.46022|0.46668|0.00082|0.18%|0.46093|-0.09%|0.46075|-0.08%|4.699|0.000|180329548|26.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1d2875a82)|0.46111|0.46303|0.00037|0.08%|0.46162|0.06%|0.46154|0.09%|1.473|0.000|180327838|26.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1d2875a82)|0.43875|0.44121|0.00045|0.10%|0.43931|-4.78%|0.43922|-4.75%|2.199|0.000|152475338|26.95 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.77808|0.78645|0.00172|0.22%|0.78223|0.00%|0.78271|0.00%|-0.344|0.999|296625145|27.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/858d34fd32)|0.77274|0.79004|0.00264|0.34%|0.77732|-0.63%|0.77829|-0.56%|0.607|0.000|295198485|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1d2875a82)|0.77480|0.79364|0.00222|0.28%|0.78083|-0.18%|0.78082|-0.24%|3.300|0.000|295204759|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1d2875a82)|0.75154|0.98135|0.08041|9.90%|0.81196|3.80%|0.75405|-3.66%|0.714|0.001|277787102|26.99 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.65952|0.66673|0.00121|0.18%|0.66073|0.00%|0.66050|0.00%|4.022|0.999|1409593191|27.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/858d34fd32)|0.66177|0.66473|0.00055|0.08%|0.66285|0.32%|0.66280|0.35%|0.855|0.000|1415753838|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1d2875a82)|0.66284|0.68198|0.00190|0.29%|0.66383|0.47%|0.66365|0.48%|9.051|0.000|1415752276|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1d2875a82)|0.59344|0.59608|0.00046|0.08%|0.59446|-10.03%|0.59440|-10.01%|0.781|0.000|1155145318|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42552|0.43068|0.00121|0.28%|0.42770|0.00%|0.42759|0.00%|0.540|0.999|2020733513|7.97 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/858d34fd32)|0.43325|0.44040|0.00130|0.30%|0.43581|1.90%|0.43582|1.93%|0.494|0.000|2020687269|7.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1d2875a82)|0.43157|0.43884|0.00157|0.36%|0.43481|1.66%|0.43477|1.68%|0.427|0.000|2020687376|7.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1d2875a82)|0.14109|0.14601|0.00095|0.66%|0.14351|-66.45%|0.14359|-66.42%|-0.030|0.000|539477072|7.97 MB|
