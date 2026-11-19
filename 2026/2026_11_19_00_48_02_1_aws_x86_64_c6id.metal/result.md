### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-11-19 00:48:02 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/44431786155 ([Artifacts](https://github.com/php/php-src/actions/runs/44431786155/artifacts/14488424127))|
| Changeset  |https://github.com/php/php-src/compare/eb6f0ded68..e709ba4099|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39755|0.39918|0.00025|0.06%|0.39788|0.00%|0.39783|0.00%|3.184|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eb6f0ded68)|0.37859|0.38040|0.00031|0.08%|0.37913|-4.71%|0.37906|-4.72%|2.164|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/e709ba4099)|0.37891|0.37999|0.00023|0.06%|0.37922|-4.69%|0.37916|-4.69%|1.295|8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e709ba4099)|0.35253|0.35471|0.00033|0.09%|0.35291|-11.30%|0.35284|-11.31%|3.575|8.614|0.000|26.28 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67772|0.70380|0.00366|0.54%|0.67903|0.00%|0.67840|0.00%|6.618|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eb6f0ded68)|0.67929|0.68323|0.00063|0.09%|0.68022|0.18%|0.68003|0.24%|2.759|-7.628|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/e709ba4099)|0.68312|0.68648|0.00072|0.11%|0.68405|0.74%|0.68384|0.80%|1.498|-8.269|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e709ba4099)|0.65536|0.66367|0.00117|0.18%|0.65624|-3.36%|0.65600|-3.30%|5.397|8.614|0.000|26.34 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59095|0.59455|0.00077|0.13%|0.59232|0.00%|0.59225|0.00%|0.305|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eb6f0ded68)|0.58813|0.59112|0.00061|0.10%|0.58888|-0.58%|0.58872|-0.60%|1.829|8.593|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/e709ba4099)|0.58747|0.59099|0.00073|0.12%|0.58854|-0.64%|0.58831|-0.66%|1.932|8.593|0.000|26.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e709ba4099)|0.51527|0.51827|0.00065|0.13%|0.51591|-12.90%|0.51573|-12.92%|2.513|8.614|0.000|26.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44265|0.44804|0.00094|0.21%|0.44479|0.00%|0.44469|0.00%|1.097|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eb6f0ded68)|0.45318|0.45618|0.00059|0.13%|0.45431|2.14%|0.45422|2.14%|0.471|-8.614|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/e709ba4099)|0.45235|0.45474|0.00056|0.12%|0.45381|2.03%|0.45380|2.05%|-0.170|-8.614|0.000|26.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e709ba4099)|0.14521|0.14887|0.00049|0.34%|0.14576|-67.23%|0.14572|-67.23%|5.325|8.614|0.000|26.35 MB|
