План автоматизации

1.Переход на страницу профессии с главной страницы
	1.1 Переход с главной страницы на страницу Программирования по клику на кнопку Программирование
	1.2 Переход со страницы Программирование на страницу профессии по клику на кнопку  Тестировщик ПО

2.Есть переход на страницу профессии в самом низу главной страницы, но я бы не стала это автоматизировать, тк
похоже на то, что там контент очень часто меняется. Если это так, то это будет очень дорого автоматизировать

3.Переход на страницу професси через каталог курсов
	3.1 Переход с главной страницы в каталог по клику на кнопку Кталог курсов
	3.2 Клик на строку поиска
	3.3 Ввод "Тестрировщик"
	3.4 Клика на Тестировщик ПО

4.Запись на курс
	4.1 Клик на кнопку Записать вверху экрана
	4.2 Клик по строке Имя
	4.3 Ввод валидного имени
	4.4 Клик по строке с телефоном
	4.5 Ввод валидного номера телефона
	4.6 Клик на клавишу Записаться
	4.7 Проверка на отправку данных в БД

5.Запись на курс с невалидными значениями
	5.1 Клик по строке Имя
	5.2 Ввод цифр
	5.3 Проверка на появление предупреждения о неправильном имени
	5.4 Клик по строке с телефоном
	5.5 Ввод букв
	5.6 Проверка на появление предупреждения о неправильном номере
	5.7 Клавиша записаться не активна

	Инструменты и доступы:
Доступ к базе данных на уровне селект, чтобы узнать успешно ли записались данные
Постман, для того чтобы получать ответ от сервиса об успешном получении данных(Нужны данные сервиса))

	Риски:
Если форма будет постоянно меняться, то автотесты будут быстро устаревать, тем самым
поддержка будет дорожать, а доверие к автотестам снижаться. Может привести к тому, что
автотесты пропустя какое-то изменение и на сервис будут поступать некорректные данные(например))

	Специалисты:
Инженер по тестированию
Заказчик, для уточнения как форма должна себя вести
Программист, для уточнения куда и каким путем данные должны отправляться

	Время:
На вышеперечеслиенные сценарии понадобится примерно 16 часов с учетом обсуждения и уточнения всех
интересующих моментов. Если учитывать время на предоставление всех необходимых доступов - 
интервальная оценка может увеличиться в зависимости от пайплайнов компании. В любом случае эти потраченные
часы сами себя окупят, так как время ручного тестирование должно сократиться, особенно если учитывать, что такие проверки
должны проходить в качестве смоук тестирования ежедневно по несколько раз в сутки.
