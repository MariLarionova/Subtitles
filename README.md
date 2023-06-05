Проект:

Запрос сформирован тем, что просмотр фильмов на оригинальном языке - это популярный и действенный метод упражнений по изучению иностранных языков. Важно выбрать фильм, который подходит студенту по уровню сложности, т.е. студент понимал 50-70 % диалогов. Чтобы выполнить это условие, преподаватель должен посмотреть фильм и решить, какому уровню он соответствует. Однако это требует больших временных затрат.

Заказчику необходимо:

Разработать ML решение для автоматического определения уровня сложности англоязычных фильмов. За время работы над проектом вы обучите языковую модель, разработаете для неё веб-интерфейс и создадите микросервис.

Исходные данные:

размеченный датасет с названиями фильмов в формате excel, c субтитрами и меткой уровня сложности языка (A2/B1/B2/C1/C2);

файлы субтитров в формате .srt, отсортированные по каталогам в соответствии с уровнем сложности. Предварительно все субтитры были перенесены в общую папку для 'D:/English_films_level/Datasets/Subtitles загрузки';

словари Oxford (на 3000 и 5000 тыс.слов), в которых слова на английском сгруппированны по уровню сложности.

План работы:

загрузка необходимых библиотек;

загрузка и ознакомление с данными;

предобработка данных (очистка от дубликатов, проверка наличия разметки для обучающих данных, определение исходного количества представленных данных, очитска текста субтитров, разбивка на обучающую и тестовую выборки);

препроцессинг данных (преобразование данных для обучения модели);

определение метрики качества;

обучение модели с побором гиперпараметров;

оценка модели на тестовой выборке;

развертывание модели для демонтрации работы с использованием библиотеки Streamlit;

рекомендации к улучшению проекта.
