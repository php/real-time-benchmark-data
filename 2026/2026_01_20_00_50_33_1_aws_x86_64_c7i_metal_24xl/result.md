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
| Time          |2026-01-20 00:50:33 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21155695928 ([Artifacts](#ARTIFACT_URL#))|
| Changeset  |https://github.com/php/php-src/compare/7722a9a797..b17b699c69|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45107|0.45826|0.00071|0.16%|0.45166|0.00%|0.45155|0.00%|8.162|0.999|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7722a9a797)|0.44659|0.45284|0.00065|0.15%|0.44720|-0.99%|0.44714|-0.98%|6.661|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/b17b699c69)|0.44578|0.45317|0.00076|0.17%|0.44645|-1.15%|0.44630|-1.16%|7.123|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b17b699c69)|0.42844|0.42989|0.00028|0.07%|0.42904|-5.01%|0.42901|-4.99%|0.782|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.76810|0.77616|0.00084|0.11%|0.77394|0.00%|0.77388|0.00%|-2.748|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7722a9a797)|0.76753|0.77563|0.00086|0.11%|0.77293|-0.13%|0.77282|-0.14%|-1.361|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/b17b699c69)|0.76103|0.78367|0.00255|0.33%|0.76899|-0.64%|0.76926|-0.60%|2.203|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b17b699c69)|0.89468|1.19244|0.03795|3.24%|1.17219|51.46%|1.18241|52.79%|-5.282|0.000|27.00 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65910|0.66166|0.00044|0.07%|0.66013|0.00%|0.66013|0.00%|0.612|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7722a9a797)|0.66109|0.68165|0.00274|0.41%|0.66243|0.35%|0.66200|0.28%|6.769|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/b17b699c69)|0.66441|0.68486|0.00274|0.41%|0.66587|0.87%|0.66549|0.81%|6.742|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b17b699c69)|0.59157|0.59350|0.00036|0.06%|0.59248|-10.25%|0.59243|-10.25%|0.370|0.000|27.00 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42500|0.45082|0.00274|0.64%|0.42841|0.00%|0.42792|0.00%|5.815|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7722a9a797)|0.44053|0.44724|0.00139|0.31%|0.44402|3.64%|0.44405|3.77%|-0.069|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/b17b699c69)|0.42329|0.43142|0.00167|0.39%|0.42657|-0.43%|0.42624|-0.39%|0.500|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b17b699c69)|0.13829|0.14635|0.00147|1.04%|0.14106|-67.07%|0.14091|-67.07%|0.529|0.000|27.00 MB|
