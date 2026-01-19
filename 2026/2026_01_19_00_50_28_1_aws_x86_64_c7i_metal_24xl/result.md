### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-19 00:50:28 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21121660810 ([Artifacts](#ARTIFACT_URL#))|
| Changeset  |https://github.com/php/php-src/compare/03ca08..7722a9|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46114|0.46962|0.00112|0.24%|0.46194|0.00%|0.46178|0.00%|6.416|0.999|27.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/03ca08948d)|0.45805|0.46163|0.00074|0.16%|0.45875|-0.69%|0.45852|-0.71%|2.098|0.000|27.02 MB|
|[PHP - master](https://github.com/php/php-src/commit/7722a9a797)|0.45810|0.46293|0.00074|0.16%|0.45885|-0.67%|0.45860|-0.69%|2.887|0.000|27.02 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7722a9a797)|0.43876|0.44364|0.00064|0.14%|0.43951|-4.86%|0.43943|-4.84%|4.268|0.000|27.02 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.76265|0.78375|0.00257|0.33%|0.77084|0.00%|0.77057|0.00%|1.515|0.999|27.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/03ca08948d)|0.76083|0.77941|0.00324|0.42%|0.76747|-0.44%|0.76876|-0.23%|-0.252|0.000|27.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/7722a9a797)|0.76168|0.77944|0.00144|0.19%|0.76900|-0.24%|0.76885|-0.22%|2.731|0.000|27.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7722a9a797)|0.73930|0.98414|0.09439|11.47%|0.82309|6.78%|0.79137|2.70%|0.716|0.051|27.05 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.66002|0.68207|0.00351|0.53%|0.66169|0.00%|0.66110|0.00%|5.438|0.999|27.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/03ca08948d)|0.66252|0.68344|0.00345|0.52%|0.66426|0.39%|0.66357|0.37%|5.266|0.000|27.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/7722a9a797)|0.66266|0.68397|0.00342|0.52%|0.66455|0.43%|0.66361|0.38%|4.405|0.000|27.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7722a9a797)|0.59379|0.59937|0.00109|0.18%|0.59499|-10.08%|0.59463|-10.05%|2.740|0.000|27.05 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42561|0.43337|0.00140|0.33%|0.42825|0.00%|0.42797|0.00%|0.560|0.999|7.93 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/03ca08948d)|0.44085|0.44963|0.00166|0.37%|0.44399|3.67%|0.44407|3.76%|0.606|0.000|7.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/7722a9a797)|0.44068|0.44734|0.00166|0.37%|0.44389|3.65%|0.44372|3.68%|0.189|0.000|7.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7722a9a797)|0.13753|0.14442|0.00130|0.92%|0.14105|-67.06%|0.14104|-67.04%|0.027|0.000|7.93 MB|
