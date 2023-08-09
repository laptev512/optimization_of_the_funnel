### Оптимизация воронки

Образовательная платформа предлагает пройти студентам курсы по модели trial: студент может решить бесплатно лишь 30 заданий в день. Для неограниченного количества заданий в определенной дисциплине студенту необходимо приобрести полный доступ. Команда провела эксперимент, где был протестирован новый экран оплаты.

Даны таблицы: default.peas, default.studs и default.final_project_check:

Необходимо в одном запросе выгрузить следующую информацию о группах пользователей:

**ARPU**\
**ARPAU**\
**CR** в покупку\
**СR** активного пользователя в покупку\
**CR** пользователя из активности по математике (subject = ’math’) в покупку курса по математике\
**ARPU** считается относительно всех пользователей, попавших в группы\

Активным считается пользователь, за все время решивший больше 10 задач правильно в любых дисциплинах.\
Активным по математике считается пользователь, за все время решивший 2 или больше задач правильно по математике.
