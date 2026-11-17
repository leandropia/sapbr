# SAPBR Technologies: Brazil Tax Reform Calculator

Interactive calculator that simulates Brazil's Tax Reform (IBS, CBS and the Selective Tax, IS) side by side with today's ICMS, PIS and COFINS, product by product. Available in English (US) and Portuguese (BR); add `?lang=en` or `?lang=pt` to the URL to open it in a specific language.

Live: https://leandropia.github.io/sapbr/

## Model

- Current system: ICMS, PIS and COFINS calculated "por dentro" (included in the price).
- Reform: base = value − ICMS − PIS − COFINS; IBS and CBS = base × rate × regime factor (standard 1, 30% reduction 0.7, 60% reduction 0.4, zero rate 0); IS = base × rate on flagged items only.
- Credits on purchases: current = ICMS+PIS+COFINS, reform = IBS+CBS (IS is not creditable). Debits on sales: current = ICMS+PIS+COFINS, reform = IBS+CBS+IS.

Simplified and illustrative. It does not cover the 2026–2033 transition schedule or the Simples Nacional regime, and it is not tax advice.

Calculation logic adapted from [grupomg-tech/calculadora-reforma-tributaria](https://github.com/grupomg-tech/calculadora-reforma-tributaria) (MIT license). Example products are fictional.

Published by [SAPBR Technologies](https://sapbr.com).
