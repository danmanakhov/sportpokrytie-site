# Спорт-Покрытие: концепт-макет сайта

**Концепт-макет.** Это статический сайт-заготовка ООО «Спорт-Покрытие» для обсуждения, а не опубликованный сайт компании. Форма заявки ничего не отправляет. Места с пометкой `[уточнить]` ждут подтверждённых данных (реквизиты, гарантия, допуски, объекты, госзаказ). В `<head>` стоит `noindex`.

Фотографии и логотип взяты с действующего сайта https://sportpokrytie.ru/. Данные по услугам, контактам и примеру расчёта взяты с сайта и из коммерческих предложений компании. Цены на макете не публикуются.

## Состав
- `index.html` — главная.
- `services/<slug>.html` — 14 страниц услуг (общие шапка с меню «Услуги» и подвал).
- `assets/` — `style.css`, логотип, фотографии.
- `.nojekyll` — для GitHub Pages.

Все пути относительные, сайт работает под `/sportpokrytie-site/`.

## Страницы услуг
Для улицы: rezinovye-pokrytiya, detskie-ploshchadki, iskusstvennaya-trava, hard-tennisnye-korty, obnovlenie-tsveta.
Закрытые помещения: zakrytye-pomeshcheniya, sportivnyj-linoleum, regupol, obnovlenie-zala.
Разметка и работы: razmetka, ustroystvo-sportivnykh-pokrytiy, podgotovka-osnovaniya.
Для заказчиков: goskontrakty, optovye-postavki.

Перечень услуг и источники: `floor/db/perechen_uslug.md` (вне архива).
