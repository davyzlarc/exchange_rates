# Exchange rates
get exchange rates from API of central bank of Russia, process data and return some result values

Из API центробанка извлекаются данные по переводу различных валют в рубли за последние 90 дней.
Результатом обработки данных являются:
1) значение максимального курса валюты, название этой валюты и дату этого максимального значения.
2) зачение минимального курса валюты, название этой валюты и дату этого минимального значения.
3) среднее значение курса рубля за весь период по всем валютам.

TO LAUNCH program just type in shell (e.g. zsh) - './exchange_rates'
