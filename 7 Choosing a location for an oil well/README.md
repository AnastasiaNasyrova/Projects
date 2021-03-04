# Выбор локации для скважины 
**Цель проекта:** На основании имеющихся характеристик скважин из разных регионов, необходимо предсказать объемы добычи (задача регрессии), рассчитать прибыль и риски убытков и дать рекомендации, какой регион принесет максимальную прибыль, не превышая при этом приемлемый для бизнеса уровень риска убытков.

**Инструменты:** pandas, sklearn

**Описание работы надо проектом:**
- Первый этап - знакомство с данными, подготовка данных
- Второй этап - обучение и проверка моделей для каждого региона. Использовалась модель LinearRegression.  
- Третий этап - расчет точки безубыточности, расчет прибыли (применяя технику Bootstrap, чтобы найти распределение прибыли и среднее значение) и риска убытков.