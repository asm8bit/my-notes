#. my-notes

Необходимо написать Web-приложение для контейнера сервлетов Tomcat. Проект пишем с использованием OpenJDK 11, Tomcat 9, NetBeans 11, maven.

Приложение должно быть доступно по адресу: http://hostname:8080/notes

Приложение представляет собой записную книжку чем на 100 записей (не более).

У пользователя должна быть возможность добавить заметку (сохраняется текст и время внесения, если нужно – дополнительная информация), обновить заметку (сохраняется новый текст и время обновления), удалить заметку, просмотреть список заметок (отображается текст, время добавления/последнего изменения, при необходимости – иная информация).

Должна быть возможность сортировки записей по времени изменения (убывание/возрастание) и по тексту заметок (прямой/обратный алфавитный порядок).

Длина заметки не более 100 символов.

Должна быть возможность импорта заметок из csv-файла с двумя столбцами внутри - заметка и время в формате гггг-мм-дд чч:мм:сс (например: "Текст заметки","2020-02-21 12:01:15").

Должна быть возможность экспорта списка заметок в JSON-файл (структуру придумать самому).

Способ хранения заметок в системе – файл или БД Postgres Professional 11 версии.

Помимо пользовательского интерфейса в браузере Web-приложение «Заметки» должно предоставлять программный REST-интерфейс для выполнения основных операций с заметками (получение списка заметок, добавление, изменение, удаление). Сконструировать самостоятельно и реализовать с помощью библиотеки Resteasy версии 3.6.3.
 
Нужно прислать успешно компилирущийся проект + инструкции по развертыванию приложения (конфигурировании файла с данными или БД, иные настройки, если нужны).
