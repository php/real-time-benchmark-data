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
| Time          |2026-01-02 00:50:22 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47497|0.48213|0.00099|0.21%|0.47680|0.00%|0.47660|0.00%|1.730|0.999|180942917|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/241e43f2d8)|0.46914|0.47558|0.00101|0.21%|0.47219|-0.97%|0.47215|-0.94%|0.683|0.000|176328792|44.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/8c4f806fe8)|0.47046|0.47476|0.00091|0.19%|0.47215|-0.97%|0.47207|-0.95%|0.507|0.000|176406211|44.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8c4f806fe8)|0.44905|0.45367|0.00096|0.21%|0.45101|-5.41%|0.45087|-5.40%|0.640|0.000|147889968|53.53 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73614|0.75536|0.00194|0.26%|0.74494|0.00%|0.74482|0.00%|1.853|0.999|291620645|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/241e43f2d8)|0.74370|0.75054|0.00113|0.15%|0.74541|0.06%|0.74515|0.05%|1.486|0.001|290408440|40.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/8c4f806fe8)|0.74255|0.75432|0.00185|0.25%|0.74534|0.05%|0.74503|0.03%|2.671|0.110|290408125|40.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8c4f806fe8)|0.71698|0.72268|0.00090|0.12%|0.71911|-3.47%|0.71911|-3.45%|0.734|0.000|270763820|48.00 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57586|0.58498|0.00226|0.39%|0.58045|0.00%|0.58148|0.00%|-0.307|0.999|1123345518|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/241e43f2d8)|0.57614|0.58376|0.00201|0.35%|0.58042|-0.00%|0.58123|-0.04%|-0.485|0.520|1119531328|44.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/8c4f806fe8)|0.57582|0.59215|0.00234|0.40%|0.58070|0.04%|0.58154|0.01%|0.853|0.430|1119536914|44.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8c4f806fe8)|0.51386|0.51957|0.00148|0.29%|0.51731|-10.88%|0.51801|-10.91%|-0.479|0.000|865595734|61.64 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42504|0.43856|0.00399|0.92%|0.43162|0.00%|0.43268|0.00%|-0.130|0.999|2020638097|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/241e43f2d8)|0.42274|0.43794|0.00323|0.76%|0.42700|-1.07%|0.42657|-1.41%|1.581|0.000|2020586661|27.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/8c4f806fe8)|0.42197|0.44009|0.00348|0.81%|0.42737|-0.98%|0.42668|-1.39%|1.658|0.000|2020586690|27.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8c4f806fe8)|0.13675|0.14937|0.00397|2.76%|0.14377|-66.69%|0.14564|-66.34%|-0.315|0.000|536605692|27.95 MB|
