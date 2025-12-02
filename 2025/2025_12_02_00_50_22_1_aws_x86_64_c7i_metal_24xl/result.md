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
| Time          |2025-12-02 00:50:22 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47691|0.48052|0.00068|0.14%|0.47837|0.00%|0.47830|0.00%|0.549|0.999|180943712|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1848bcddfd)|0.47118|0.47683|0.00105|0.22%|0.47273|-1.18%|0.47246|-1.22%|2.231|0.000|176335841|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9e044548b)|0.46900|0.47462|0.00090|0.19%|0.47043|-1.66%|0.47034|-1.67%|1.378|0.000|176406251|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9e044548b)|0.45219|0.45497|0.00045|0.10%|0.45318|-5.27%|0.45316|-5.26%|0.885|0.000|147898620|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74496|0.74879|0.00083|0.11%|0.74640|0.00%|0.74635|0.00%|0.484|0.999|291621072|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1848bcddfd)|0.74248|0.74769|0.00108|0.15%|0.74440|-0.27%|0.74411|-0.30%|1.006|0.000|290397810|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9e044548b)|0.74327|0.75276|0.00131|0.18%|0.74532|-0.14%|0.74521|-0.15%|2.554|0.000|290398891|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9e044548b)|0.71826|0.72605|0.00104|0.14%|0.72012|-3.52%|0.72003|-3.53%|2.021|0.000|270757682|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58041|0.59197|0.00159|0.27%|0.58203|0.00%|0.58169|0.00%|4.706|0.999|1123343487|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1848bcddfd)|0.58112|0.58432|0.00064|0.11%|0.58223|0.03%|0.58214|0.08%|0.920|0.000|1119621294|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9e044548b)|0.57946|0.58980|0.00108|0.19%|0.58067|-0.23%|0.58049|-0.21%|6.207|0.000|1119628589|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9e044548b)|0.51664|0.52091|0.00060|0.12%|0.51774|-11.05%|0.51765|-11.01%|1.573|0.000|865682551|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42997|0.43940|0.00198|0.46%|0.43443|0.00%|0.43436|0.00%|0.058|0.999|2020638180|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1848bcddfd)|0.42393|0.43603|0.00237|0.55%|0.42701|-1.71%|0.42651|-1.81%|1.846|0.000|2020586695|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9e044548b)|0.42339|0.43795|0.00254|0.59%|0.42700|-1.71%|0.42641|-1.83%|1.912|0.000|2020586682|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9e044548b)|0.14594|0.15116|0.00110|0.74%|0.14855|-65.81%|0.14840|-65.83%|0.193|0.000|536605646|27.81 MB|
