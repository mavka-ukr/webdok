# Вебдок

Генератор HTML-документації Мавкою.

## Встановлення

todo

## Використання

todo

```мавка
взяти вебдок як вб

в = вб.Вебдок("Телеграм Бот + Мавка")

в.додати_секцію(
  вб.Секція(
    "Вступ",
    [
      "Офіційна документація телеграм-ботів знаходиться тут: core.telegram.org/bots/api",
      "Код самого паку знаходиться тут: github.com/mavka-ukr/tgbot-extension",
      "Щоб підключити пак Мавки:",
      вб.Код(
        "мавка",
        """
        взяти "телеграм_бот/0.0.1"
        """.обтяти()
      )
    ]
  )
)

вб.__вебдок_зберегти__("./index.html", в.хтмл())
```