### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-10-02 01:13:10 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/36949843891 ([Artifacts](https://github.com/php/php-src/actions/runs/36949843891/artifacts/11204208455))|
| Changeset  |https://github.com/php/php-src/compare/940ff2098e..3254c4e36e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39891|0.40136|0.00045|0.11%|0.39944|0.00%|0.39937|0.00%|2.829|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/940ff2098e)|0.37909|0.38130|0.00038|0.10%|0.37962|-4.96%|0.37950|-4.98%|2.340|8.614|0.000|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/3254c4e36e)|0.37885|0.38010|0.00030|0.08%|0.37925|-5.06%|0.37917|-5.06%|1.578|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3254c4e36e)|0.35633|0.35798|0.00033|0.09%|0.35682|-10.67%|0.35675|-10.67%|1.500|8.614|0.000|26.12 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67979|0.68326|0.00092|0.14%|0.68107|0.00%|0.68088|0.00%|0.686|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/940ff2098e)|0.67660|0.67804|0.00041|0.06%|0.67723|-0.56%|0.67711|-0.55%|0.656|8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/3254c4e36e)|0.67614|0.67801|0.00039|0.06%|0.67677|-0.63%|0.67665|-0.62%|1.277|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3254c4e36e)|0.64593|0.65902|0.00205|0.32%|0.64703|-5.00%|0.64661|-5.03%|5.025|8.614|0.000|26.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59076|0.59620|0.00106|0.18%|0.59252|0.00%|0.59244|0.00%|1.083|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/940ff2098e)|0.59493|0.59833|0.00060|0.10%|0.59564|0.53%|0.59549|0.51%|2.268|-8.297|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/3254c4e36e)|0.59364|0.59727|0.00073|0.12%|0.59446|0.33%|0.59421|0.30%|2.409|-7.387|0.000|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3254c4e36e)|0.52141|0.53249|0.00160|0.31%|0.52258|-11.80%|0.52222|-11.85%|5.126|8.614|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44376|0.44621|0.00049|0.11%|0.44470|0.00%|0.44462|0.00%|0.866|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/940ff2098e)|0.45124|0.45746|0.00104|0.23%|0.45313|1.89%|0.45300|1.88%|1.651|-8.614|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/3254c4e36e)|0.45175|0.45551|0.00080|0.18%|0.45346|1.97%|0.45344|1.98%|0.401|-8.614|0.000|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3254c4e36e)|0.14375|0.14471|0.00026|0.18%|0.14423|-67.57%|0.14422|-67.56%|-0.017|8.614|0.000|26.23 MB|
