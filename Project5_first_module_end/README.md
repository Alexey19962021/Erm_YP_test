В целом этот проект  был достатточно объемным и включал в себя разные хадачи из первого модуля. Нам было необходимо исследовать данные о продажах игр в нескольких регионах до 2017 года, проверить две статистические гипотезы и в итоге сделать выводы способствующие успешной кампании интернет-магазина, являющегося заказчиком. В ходе работы установлено:
- в каких годах был пик выпумка игр;
- какие платформы к 2016 году еще актуальны и в целом были стабильны в плане разработки и продаж игр в последние годы;
- какие жанры игр предпочитают полльзователи в разных регионах;
- средние пользовательские рейтинги XOne и PC одинаковые, а оценки критиков на игры умеренно коррелируют с продажами на конкретных платформах.

Также мы закрепили следующие навыки:
- выполнение предобработки данных (.fillna(), .drop_duplicates(), isna(), срезы в pandas);
- основные интсрументы и возможности matplotlib, seaborn, средств pandas для визуализации;
- проверку гипотез в scipy.stats.

  В общем можно сформулировать следующие основные выводы (подробнее см. в самом проекте):
- оказалось что топ-5 платформ за пследние 20 лет (от 2016 года) имеют существенное превосходство в сравнении с другими (это PS2, X360, PS3, Wii, DS), однако некоторые к данному моменту времени (DS, PS2) даже прекратили свое существование, у остальных (X360, PS3, Wii) продажи к 2016 только падают и очень низкие в сравнении с пиковыми;
- в то же время есть такие платформы как XOne, PS4, 3DS, продажи которых сохраняют достаточно высокие значения в определенный нами актуальный период (начиная с 2012 года). Сразу же отметим, что именно эти типы игровых брендов захватили лидерство по регионам - в Северной Америке, Европе и Японии соответственно. В 2017 году, скорее всего, смогут задавать/поддерживать тренды: PS4 и XOne (2 группы, смотрящиеся наиболее перспективно), 3DS и PC (стабильные с небольшими продажами), PSV и WiiU (стабильные с маленькими продажами);
- допущена нулевая гипотез о том, что средние пользовательские рейтинги платформ XOne и PC одинаковые;
- отвергнута нулевая гипотез о том, что средние пользовательские рейтинги жанров Sports и Action одинаковые.
