# ГОНЕЦ (gonec)
## Интерпретатор 1С-подобного языка

![Gonec Logo](/logo.jpeg)

Gonec language interpreter
## Цели

Интерпретатор нужен программистам 1С для решения множества задач, связанных с высокопроизводительными многопоточными вычислениями или работой с высокоэффективными key-value базами данных.

Включив такой интерпретатор в свое решение на языке Go, Вы можете предоставить небывалый уровень сервиса для своих клиентов, который обгонит решения не только ваших конкурентов на рынке 1С, но и конкурентных платформ в enterprise (SAP HANA) и в web (node.js).

Интерпретатор разрабатывается “от простого к сложному”. На начальных этапах будет включена базовая функциональность многопоточных вычислений и сетевых сервисов. В перспективе планируется организация работы с различными базами данных и визуализация управляемых форм, созданных в конфигураторе.

Еще никогда не были так просто доступны программистам 1С возможности:
* Создать микросервис с произвольным сетевым протоколом
* Выполнить сложную многопоточную вычислительную задачу для десятков тысяч подключающихся пользователей за миллисекунды
* Взаимодействовать с пользователем через web-браузер с минимальным трафиком
* Сохранять и получать данные с максимально доступной скоростью в key-value базах данных

## Почему синтаксис 1С?

Синтаксис 1С знаком и удобен сотням тысяч программистов в России и СНГ, а в перспективе и зарубежом. Это позволяет создавать решения, которые могут поддерживаться любыми программистами 1С, и которые не будут требовать дополнительной квалификации.

Интерпретатор полностью поддерживает синтаксис языка платформы 1С:Предприятие 8.3, за исключением объектов метаданных и глобальных объектов - в интерпретаторе, по понятным причинам, используются свои объекты.
