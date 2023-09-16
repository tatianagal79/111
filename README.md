# 111
ДОКУМЕНТАЦИЯ К ЗАПУСКУ КОЛЛЕКЦИИ GitHub issues

<p>Для выполнения запросов была использована документация REST API для управления проблемами и извлечением запросов:<p>
 
<ol>
<li>https://docs.github.com/en/rest/issues/issues?apiVersion=2022-11-28#about-issues<li>
</ol>
 
<p>Для работы с методами мне потребовалось создать аккаунт на GitHub, создать репозиторий с произвольным содержимым и создать API-ключ на соответствующее приложение.
При выполнении работы были введены 3 переменные:<p> 
<ol>
<li>{{baseURL}} - https://api.github.com/<li>
<li>{{token}} - токен</li>
<li>{{idiss}} - номер проблемы</li>
</ol>
 
Запросы:
1.Создайте issue с названием Issue 1, описанием Something went wrong. Также у этой issue должен быть label — bug — и assignee — вы (текущий логин на GitHub).
 Для выполнения этого запроса был использован запрос POST  и получены ответ, который соответствует документации.
2. Получите список issues.
Для выполнения этого запроса был использован запрос GET и получены ответ, который соответствует документации.
3. Измените название задачи на Issue 2.
Для выполнения этого запроса был использован запрос PATCH  и получены ответ, который соответствует документации.
4. Удалите Issue 2.
Документацией к API не предусмотрено удаление  Issue, поэтому запрос не удалось воспроизвести.
