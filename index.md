---
layout: page
title: Пропущений семестр вашої комп'ютерної освіти
description: >
  Опануйте потужні інструменти, що зроблять вашу роботу в галузі комп'ютерних наук та програмування продуктивнішою.
subtitle: 2026
nositetitle: true
---

На заняттях вивчають просунуті теми з комп'ютерних наук — від операційних систем до машинного навчання. Проте є один критично важливий аспект, який рідко висвітлюють, залишаючи студентам на самостійне опрацювання: майстерне володіння інструментами. Ми навчимо вас опановувати командний рядок, використовувати потужні текстові редактори, розширені можливості систем контролю версій та багато іншого!

Студенти витрачають сотні годин на ці інструменти під час навчання (і тисячі протягом кар'єри), тому є сенс зробити цей досвід максимально природним та комфортним. Майстерне володіння ними не лише дозволить витрачати менше часу на те, щоб підлаштувати інструментарій під свої потреби, а й дасть змогу розв'язувати задачі, які раніше здавалися б надзвичайно складними.

Сьогодні багато аспектів програмної розробки також змінюються через впровадження ШІ-інструментів та ШІ-процесів. За умови належного використання та розуміння їхніх недосконалостей, вони можуть принести значну користь фахівцям у галузі комп'ютерних наук, а отже, варті того, щоб опанувати їх на практиці. Оскільки ШІ є наскрізною технологією, окремої лекції про нього немає; натомість ми інтегрували використання найсучасніших інструментів та методів ШІ безпосередньо у кожен урок.

Дізнайтеся більше про [мотивацію створення цього курсу](/about/).

{% comment %}
# Registration

Sign up for the IAP 2026 class by filling out this [registration form](https://forms.gle/j2wMzi7qeiZmzEWy9).
{% endcomment %}

# Розклад

{% comment %}
**Lecture**: [35-225](https://whereis.mit.edu/?go=35), 1:30--2:30pm (_exception_: 3--4pm on Friday 1/16)<br>
**Discussion**: [OSSU Discord](https://ossu.dev/#community) (use `#missing-semester-forum` like you would use Piazza, and `#missing-semester` to chat with the class/instructors)
{% endcomment %}

<ul>
{% assign lectures = site['2026'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d/%y' }}</strong>:
        {% if lecture.ready %}
            <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

{% comment %}
Lecture videos will be made available to MIT students immediately after lecture (via Panopto). The system has a limitation that only those with an MIT Kerberos can access the raw lecture videos. We are working on editing lecture videos and uploading them to YouTube. A couple have been uploaded already; we expect the rest to be uploaded by mid-February.

If you can't wait until January 2026, you can also take a look at the lectures
from the [previous offering of the course](/2020/), which covers many of the
same topics.
{% endcomment %}

Переглянути відео лекцій можна на [YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQunmnnTXrNbZnBaCA-ieK4L).

Обговорити курс можна в [OSSU Discord](https://ossu.dev/#community) (використовуйте канал `#missing-semester-forum` як офіційний форум курсу (аналог Piazza) та `#missing-semester` для спілкування з групою/викладачами).

# Про курс

**Викладачі**: Цей курс спільно викладають [Anish](https://anish.io/), [Jon](https://thesquareplanet.com/) та [Jose](https://josejg.com/).<br>
**Питання**: Пишіть нам на [missing-semester@mit.edu](mailto:missing-semester@mit.edu).

# Поза межами MIT

Ми також поширюємо цей курс поза межами MIT, сподіваючись, що ці ресурси стануть корисними й іншим. Ви можете знайти публікації та обговорення на:

 - Hacker News ([2026](https://news.ycombinator.com/item?id=47124171), [2020](https://news.ycombinator.com/item?id=22226380), [2019](https://news.ycombinator.com/item?id=19078281))
 - Lobsters ([2026](https://lobste.rs/s/q4ykw7/missing_semester_your_cs_education_2026), [2020](https://lobste.rs/s/ti1k98/missing_semester_your_cs_education_mit), [2019](https://lobste.rs/s/h6157x/mit_hacker_tools_lecture_series_on))
 - r/learnprogramming ([2026](https://www.reddit.com/r/learnprogramming/comments/1r93yk6/the_missing_semester_of_your_cs_education_2026/), [2020](https://www.reddit.com/r/learnprogramming/comments/eyagda/the_missing_semester_of_your_cs_education_mit/), [2019](https://www.reddit.com/r/learnprogramming/comments/an42uu/mit_hacker_tools_a_lecture_series_on_programmer/))
 - r/programming ([2020](https://www.reddit.com/r/programming/comments/eyagcd/the_missing_semester_of_your_cs_education_mit/), [2019](https://www.reddit.com/r/programming/comments/an3xki/mit_hacker_tools_a_lecture_series_on_programmer/))
 - X ([2026](https://x.com/anishathalye/status/2024521145777848588), [2020](https://twitter.com/jonhoo/status/1224383452591509507), [2019](https://x.com/jonhoo/status/1090323977766137858))
 - Bluesky ([2026](https://bsky.app/profile/jonhoo.eu/post/3mfa2bhyuj22i))
 - Mastodon ([2026](https://fosstodon.org/@jonhoo/116098318361854057))
 - LinkedIn ([2026](https://www.linkedin.com/posts/anishathalye_i-returned-to-mit-during-iap-january-term-activity-7430285026933522433-Ehr9))
 - YouTube ([2026](https://www.youtube.com/playlist?list=PLyzOVJj3bHQunmnnTXrNbZnBaCA-ieK4L), [2020](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J), [2019](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuiujH1lpn8cA9dsyulbYRv))

# Переклади

{% comment %} keep these in alphabetical order {% endcomment %}

- [Arabic](https://missing-semester-ar.github.io/)
- [Bengali](https://missing-semester-bn.github.io/)
- [Chinese (Simplified)](https://missing-semester-cn.github.io/)
- [English](https://missing.csail.mit.edu/)
- [German](https://missing-semester-de.github.io/)
- [Italian](https://missing-semester-it.github.io/)
- [Japanese](https://missing-semester-jp.github.io/)
- [Kannada](https://missing-semester-kn.github.io/)
- [Korean](https://missing-semester-kr.github.io/)
- [Persian](https://missing-semester-fa.github.io/)
- [Portuguese](https://missing-semester-pt.github.io/)
- [Russian](https://missing-semester-rus.github.io/)
- [Serbian](https://netboxify.com/missing-semester/)
- [Spanish](https://missing-semester-esp.github.io/)
- [Thai](https://missing-semester-th.github.io/)
- [Turkish](https://missing-semester-tr.github.io/)
- [Vietnamese](https://missing-semester-vn.github.io/)

Примітка: це зовнішні посилання на переклади від спільноти. Ми їх не перевіряли.

Ви створили переклад конспектів цього курсу? Відправте
[pull request](https://github.com/missing-semester/missing-semester/pulls) щоб ми могли додати його до списку!

Бачите неточність? Запропонуйте правки до перекладу в [GitHub репозиторії української версії курсу](https://github.com/missing-semester-ua/missing-semester-ua.github.io/pulls). Дякуємо за внесок!



## Подяки

{% comment %}
2026 acks; previous years' acks are on their respective pages
{% endcomment %}

Ми дякуємо Elaine Mello та [MIT Open Learning](https://openlearning.mit.edu/) за можливість записати відео лекцій. Ми також вдячні Luis Turino / [SIPB](https://sipb.mit.edu/) за підтримку цього курсу в межах [SIPB IAP 2026](https://sipb.mit.edu/iap/).

---

<div class="small center">
<p><a href="https://github.com/missing-semester-ua/missing-semester-ua.github.io.git" target="_blank">Вихідний код україномовної версії</a>.</p>
<p>Ліцензовано на умовах CC BY-NC-SA.</p>
<p>Правила щодо внесення правок та перекладу можна знайти <a href="/license/">тут</a>.</p>
</div>
