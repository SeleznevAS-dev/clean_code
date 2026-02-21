# Урок 5 - Имена классов

## 3.1

ProxyManager - ProxyProvider

DatabaseManager - DatabaseContoller

PoolManager - PoolController

SessionManager - SessionController

PrometheusManager - PrometheusController

## 3.2

_fetch_proxies_from_api - _get_proxies_from_api

RiscZeroLending - RiscZeroLanding // по сути грамматическая ошибка, но из-за этого файл с кодом класса оказался в другой папке проекта

mint_badge - mint // только один основной метод, поэтому достаточно mint

claim_curtis_bridge - claim // аналогично в классе только один метод, можно не пояснять

bridge_arbitrum_to_curtis - bridge

bridge_curtis_to_arbitrum - bridge // этот метод и метод выше находятся в разных класса, в которых и так отражены различия

give_permit_and_claim - give_permit - claim // слово and явно указывает, что метод выполняет два действия, которые нужно разделить