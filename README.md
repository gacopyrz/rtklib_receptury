# rtklib_receptury

przykład użycia programu rnx2rtkp dla pliku obserwacyjnego Garmina i nawigacyjnego z u-bloxa9:

rnx2rtkp -k garmin.conf -ts 2024/06/26 15:06:00.0 -te 2024/06/26 15:23:00.0 garmin.obs u-blox9.nav > garmin.pos

przykład użycia programu rnx2rtkp dla plików obserwacyjnego  i nawigacyjnego z u-bloxa9

rnx2rtkp -k u-blox9.conf -ts 2024/06/26 15:06:00.0 -te 2024/06/26 15:23:00.0 u-blox9.obs u-blox9.nav > u-blox9.pos

Przykład uzycia polecenia convbin z wyłaczeniem Glonassa (-y R), BeiDou (-y C) i SBS (-y S)

convbin -d . -y R -y C -y S -od -os -oi -ot ../ubx/R9_2024-06-26_16_59.ubx
