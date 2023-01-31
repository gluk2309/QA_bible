# Особенности в тестировании мобильных приложений

Многие особенности очевидны из самого названия “мобильные” - смартфон имеет маленький дисплей, им пользуются на ходу и в условиях совместного использования с большим количеством других приложений и подключенных устройств, а высокий темп современной жизни заставит пользователя уйти к конкурентам, если экран приложения загружается дольше пары секунд, если с приложением сложно взаимодействовать или оно доставляет еще какие-либо неудобства.

**Отличия от веба и десктопа**:

* Постоянные прерывания в работе приложения: сворачивание, блокировка, входящий звонок или сообщение, уведомления, обновления приложений, выключение или перезагрузка, выгрузка системой из ОЗУ, разряд АКБ, подключение зарядки или других устройств, переход в энергосберегающий режим и режим ожидания, включение и отключение функций необходимых устройству (gps, bluetooth, связь), использование/отзыв разрешений, подключение/отключение карты памяти/симки/АКБ, платежи NFC, принудительная остановка);
* Работа в беспроводной сети с изменяющейся стабильностью и скоростью приема сигнала, переключение между сотовой связью и wi-fi;
* Уведомления;
* Взаимодействие с web view;
* Использование вертикальной и горизонтальной ориентации, повороты;
* Распространение приложений через маркеты;
* Необходимо соответствие гайдлайнам систем;
* Большое внимание уделяется UI и UX;
* В случае Android большая фрагментация устройств и прошивок со своими особенностями;
* Тач-интерфейс, мультитач, жесты;
* Множество каналов ввода: стоковая клавиатура, сторонние клавиатуры, хардовые клавиатуры, голос, жесты и т. д.;
* Биометрия;
* Повышенные требования к энергопотреблению и использованию аппаратных ресурсов;
* Ситуации установки и обновления при нехватке памяти, переноса приложения на карту памяти и обратно;
* Важность инсталляционного тестирования, особенно обновлений, т.к. в условиях высококонкурентного мобильного рынка приложения обновляются часто, чтобы предоставить пользователям новые функции как можно скорее и при этом должны проходить бесшовно;
* GPS и локализация;
* Размер дисплея, челка и вырез под фронтальную камеру;