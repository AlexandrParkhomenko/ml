Виталий Лялин. [Инструменты для участников соревнований по машинному обучению](https://habr.com/ru/post/542292/)

[Determined](https://github.com/determined-ai/determined)
**Платформа для тренировки моделей глубокого обучения.**

- Ускоренное обучение моделей, с помощью state-of-the-art распределенного обучения, без изменения кода модели
- Автоматический поиск высококачественных моделей, с расширенной настройкой гипер-параметров — от создателей Hyperband
- Умное планирование использования своих GPU и сокращение расходов на облачные GPU, за счет использования вытесняемых инстансов
- Отслеживание и воспроизводство экспериментов, включая версии кода, показатели, контрольные точки и гипер-параметры
- Легкость интеграции с популярными DL-фреймворками
- Позволяет больше времени тратить на создание моделей, чем на управление инфраструктурой

[Compose](http://compose.alteryx.com)
**Инструмент машинного обучения для автоматизированного прогнозирования.**

- Структурирование задач прогнозирования и создание меток для обучения с учителем
- Поиск обучающих примеров исходя из конечного желаемого результата, заданного функцией разметки
- Передача результата в Featurepools для автоматизированного проектирования признаков
- Передача результата в EvalML для автоматизированного машинного обучения

[Featuretools](http://featuretools.alteryx.com)
**Фреймворк для автоматизированного проектирования признаков.**

- Преобразование временных и реляционных наборов данных в матрицы признаков
- Возможность автоматически генерировать описания признаков на английском языке

[EvalML](http://evalml.alteryx.com)
**Библиотека AutoML для создания, оптимизации и оценивания пайплайнов машинного обучения с использованием целевых функций для конкретной предметной области.**

- В сочетании с Featuretools и Compose позволяет создавать end-to-end ML-решения для обучения с учителем

[Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling)
**Создает отчеты профиля из DataFrame Pandas.**

- Вместо df.describe() — функция df.profile_report()
- Быстрый анализ данных
- Интерактивный HTML-отчет со столбцами
- Вывод типа: определение типов
- Основы: тип, уникальные значения, отсутствующие значения
- Квантильные статистические данные: минимум, Q1, медиана, Q3, максимум, диапазон, межквартильный размах
- Описательная статистика: среднее, мода, стандартное отклонение, сумма, среднее абсолютное отклонение, коэффициент вариации, эксцесс, асимметрия
- Наиболее частые значения
- Гистограмма
- Корреляции сильно зависимых переменных: матрицы Спирмана, Пирсона и Кендалла
- Матрица пропущенных значений: количество, тепловая карта и дендрограмма
- Анализ текста: категории (прописные буквы, пробел), кодировка (латиница, кириллица) и блоки (ASCII) в текстовых данных
- Анализ файлов и изображений: размеры файлов, даты создания, усеченные изображения и изображения, содержащие EXIF

[Tpot](http://epistasislab.github.io/tpot)
**Инструмент машинного обучения, который оптимизирует пайплайны с использованием генетического программирования.**

- Автоматизирует самую утомительную часть машинного обучения, интеллектуально исследуя тысячи возможных пайплайнов, чтобы найти лучшие из ваших данных
- После завершения поиска предоставляет код Python для лучшего найденного пайплайна
- Сделан на основе Scikit-learn

[Shap](https://shap.readthedocs.io/en/latest/index.html)
**Теоретико-игровой подход к объяснению результатов любой ML-модели.**

- Имеет точный алгоритм для ансамбля деревьев
- Может использоваться в моделях глубокого обучения

[Feature-engine](https://feature-engine.readthedocs.io/en/latest)
**Библиотека с множественными трансформерами фичей для использования ML-моделях.**

- Позволяет выбирать переменные, которые вы хотите преобразовать
- Трансформеры для отсутствующих данных, категориальных переменных, дискретизации, преобразований переменных, выбросов, создания и выбора переменных

[Lale](https://github.com/IBM/lale)
**Библиотека для полуавтоматической обработки данных и выбора алгоритма настройки гипер-параметров.**

- Делает лучше автоматизацию, проверку правильности и совместимость
- Для автоматизации — высокоуровневый интерфейс инструментов поиска по пайплайну
- Для проверки корректности — использование схемы JSON для обнаружения ошибок несоответствий между гипер-параметрами и их типом или между данными и оператором
- Для совместимости — растущая библиотека преобразователей и оценок из других популярных библиотек

[Biome](https://www.recogn.ai/product.html)
**Инструмент для работы с неструктурированными данными.**

- Автоматическая классификация — короткие и шумные тексты, длинные тексты; инструменты мониторинга и анализа результатов классификации; простой в использовании пользовательский интерфейс аннотаций; предварительно сконфигурированные и расширяемые классификаторы
- Извлечение данных — табличные данные, длинные документы; встроенные готовые объекты (дата, время, количество, вес, размер, единицы измерения), поддержка нескольких форматов файлов (PDF, Word, Excel, HTML, E-mail или простой текст); настраиваемые объекты, атрибуты и отношения; реляционный вывод объектов, отношений, ролей и атрибутов на основе графов знаний
- Сравнение — настраиваемые сервисы семантического сходства для предложений, абзацев и текстового контента в базах данных; аналитические пользовательские интерфейсы для поиска наиболее похожих и непохожих элементов

[DataSketch](https://github.com/ekzhu/datasketch)
**Инструмент для вероятностных структур данных.**

- обработка и поиск больших объемов данных очень быстро
- очень маленькая потеря точности

[PyTextRank](https://github.com/DerwenAI/pytextrank)
**Инструмент для работы с текстом.**

- Извлечение самых популярных фраз из текстовых документов
- Выполнение незатратного извлекающего суммирования текстовых документов
- Вывод ссылок из неструктурированного текста в структурированные данные
- Поддержка связывания объектов
- Графовые алгоритмы (в частности, центральность собственных векторов)
- Построение графа лемм для представления ссылок между фразами и поддерживающим языком
- Включение глаголов в граф (но не в результирующие фразы)
- Использование предварительной обработки с помощью разделения существительных и распознавания именованных объектов
- Извлекающая суммаризация на основе ранжированных фраз

[Joblib](https://joblib.readthedocs.io/en/latest)
**Набор инструментов для легкого создания пайплайнов.**

- Простые параллельные вычисления
- Прозрачное кэширование функций и ленивая переоценка
- Оптимизирован для быстрой и надежной обработки больших данных и массивов
- Удобный повторный перезапуск экспериментов
- Отделение логики выполнения потока от логики предметной области и кода
- Параллельный помощник — упрощение написания читаемого параллельного кода и его отладки
- Замена Pickle для работы с объектами, содержащими большие данные

[Shampoo](https://arxiv.org/pdf/1802.09568.pdf)
**Алгоритм предварительной обработки с учетом структуры.**

- Более быстрая работа, чем у других оптимизаторов
- Поддерживает набор предварительно подготовленных матриц, которые действуют в одном измерении, сокращаясь в остальных
- Имеет гарантии сходимости в стохастической выпуклой ситуации

[Michelangelo](https://eng.uber.com/michelangelo-machine-learning-platform)
**Платформа машинного обучения от Uber.**

- Обеспечение непрерывного рабочего процесса
- Централизованное хранилище функций
- Распределенная инфраструктура обучения
- Оценка и визуализация моделей с деревьями решений
- Средства развертывания моделей
- Прогнозирование и маршрутизация
- API для подключения конвейеров

[Hasty.ai](https://hasty.ai)
**Инструмент для создания меток изображений.**

- Быстрая разметка данных
- Автоматизация процесса разметки
- Обучение помогающей модели прямо во время разметки
- Поиск вероятных ошибок

[Cortex](https://github.com/cortexlabs/cortex)
**Инструмент для крупномасштабных рабочих нагрузок.**

- Развертывание моделей в качестве API реального времени или пакетного
- Высокая доступность с зонами доступности и автоматическим перезапуском экземпляров
- Логический вывод экземпляров по запросу или спотовых экземпляров с резервными копиями по запросу
- Автомасштабирование для обработки производственных рабочих нагрузок с поддержкой избыточного выделения запросов

[Weights &amp; Biases](https://wandb.ai/site)
**Набор инструментов для машинного обучения.**

- Отслеживание экспериментов
- Оптимизация гипер-параметров
- Версионирование моделей и датасетов
- Панель инструментов — просмотр эксперимента в реальном времени
- Оптимизация моделей с помощью масштабируемого инструмента поиска гипер-параметров
- Отслеживание артефактов — сохранение всех деталей непрерывного пайплайна
- Совместные документы — исследование результатов и обмен выводами

[SpeedRun](https://github.com/inferno-pytorch/speedrun)
**Набор инструментов для развертывания и управления ML-экспериментами.**

- Чтение файлов конфигурации и управление каталогами экспериментов
- Логирование в Weights &amp; Biases
- Настройка и запуск гипер-параметров с помощью Weights &amp; Biases
- Запись текста или изображений в файл, индикаторы выполнения
- Преобразование фигур matplotlib в изображения
- Визуализация многомерных изображений
- Ожидание завершения запущенных процессов и освобождения ресурсов

[Great Expectations](https://greatexpectations.io)
**Работа с данными — тестирование, документирование и профилирование.**

- Автоматическое документирование данных
- Генерирование документации из тестов
- Автоматическое профилирование данных

[Keras Tuner](https://keras-team.github.io/keras-tuner)
**Платформа для для оптимизации гипер-параметров.**

- Определение пространства поиска
- Поиск наилучших значений
- Встроенные алгоритмы байесовской оптимизации

[NanoEdge AI Studio](https://cartesiam.ai)
**Десктопное приложение для AI-библиотек, предназначенное для разработчиков встроенных приложений и MCU C кода.**

- Поиск лучших библиотек для встроенных проектов
- Включение возможности машинного обучения в MCU C код
- Запуск библиотек на любых Arm Cortex-M микроконтроллерах и оптимизированных для них
- Очень маленький размер памяти модели (1-20kB RAM/Flash)
- Ультра быстрые модели (1-20ms вывод на M4 80MHz)
- Автоматическая проверка качества данных
- Автоматический поиск лучшей AI модели
- Сбор и импорт данных через последовательный порт в реальном времени
- Эмулятор для тестирования библиотеки перед встраиванием
- Простота развертывания C библиотек
- Модели могут обучены напрямую, без использования MCU
- Для создания и развертывания моделей не требуется опыт и экспертиза в ML

[LabelBox](https://labelbox.com)
**End-to-end платформа для создания и управления высококачественными данными.**

- Автоматизированная разметка
- Общее рабочее пространство для работы с данными и коллективного взаимодействия внутренних и внешних команд
- Отслеживание активности и прогресса работы
- Управление доступом и ролями
- API (Python, GraphQL) и SDK
- Работа с изображениями: классификация, распознавание и сегментация
- Работа с видео: производительный редактор видео, метки на видео до 30 FPS с уровнем кадра, аналитика признаков меток
- Работа с текстом: классификация, распознавание именованных сущностей, поддержка сложных онтологий с встроенными классификациями
- Предварительная маркировка на основе моделей и активного обучения
- Приоритизация очереди маркировки наиболее важных данных с помощью API

[LabelML](https://github.com/lab-ml/labml)
**Организация ML-экспериментов и мониторинг процесса обучения с мобильного.**

- Легкая интеграция (2 строчки кода)
- Хранение лога экспериментов, включая гит-коммитs, настройки и гипер-параметры
- Хранение лога Tensorboard
- Панель управления в локальном браузере
- Хранение контрольных точек
- API для настраиваемой визуализации

[PyCaret](https://pycaret.org)
**Low-code ML-библиотека.**

- Быстрый процесс — от подготовки данных до деплоинга модели
- Фокусировка на бизнес-задачах вместо кодинга
- Легкость использования и построения полного процесса эксперимента
- Анализ производительности модели (более 60 графиков)
- Подготовка данных (недостающие значения, трансформинг категориальных данных, создание признаков, настройка гипер-параметров модели)
- Поддержка алгоритма Боруты

[CometML](https://www.comet.ml)
**Инструмент для быстрого создания моделей**

- Отслеживание, сравнение, объяснение и оптимизация экспериментов и моделей
- Быстрая интеграция
- Сравнение экспериментов — код, гипер-параметры, метрики, предсказания, зависимости, системные метрики
- Отладка моделей — просмотр, анализ, получение информации и визуализация данных
- Рабочее пространство для взаимодействия команды

[ClearML](https://clear.ml)
**Решение для объединения ML-инструментов (MLOps).**

- Один набор инструментов для автоматизации подготовки, выполнения и анализа экспериментов
- Управление экспериментами — параметры, задания, артефакты, метрики, отладочные данные, метаданные и логи
- Управление и оркестровка GPU/CPU ресурсов, автоматическое масштабирование на облачных и локальных машинах
- Хранилище данных — версионирование анализа; создание и автоматизация пайплайнов данных; ребалансировка, смешивания и сочетания датасетов

