Задача состоит в том, чтобы для каждого action_id в action_test предсказать result как float от 0 до 1. Файл должен содержать заголовок «action_id, result». Метрика оценки ROC.

Файл person содержит всех уникальных людей (и соответствующие характеристики), которые выполняли действия с течением времени. Каждая строка в файле представляет уникального человека. У каждого человека есть уникальный person_id.

Файл action_train содержит все уникальные действия (и соответствующие характеристики действий), которые каждый человек выполнял в течение определенного времени. Каждая строка в файле действий представляет собой уникальное действие, выполненное человеком в определенный день. Каждое действие имеет уникальный идентификатор action_id. В файле содержится несколько различных категорий действий. Действия типа 1 отличаются от действий типа 2-7, поскольку известно больше характеристик, связанных с действиями типа 1 (всего девять), чем с действиями типа 2-7 (которые имеют только одну связанную характеристику).
