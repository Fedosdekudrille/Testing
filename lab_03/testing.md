# **Тестирование** интернет-ресурса ["Telegram"](https://web.telegram.org)
![Иконка](https://www.google.com/search?sca_esv=e1f0b68dea977417&sxsrf=ACQVn08pJwZUXfLNlwIKXykC747KupqRxw:1710227119517&q=Telegram+icon+png&uds=AMwkrPvigZSiVdgZkiEdhZpbeGWwMuTXcXOPTtUuNCnH1hvXYhj6mxBNh9ksJVT3R8FSKndxAOzCru6jHNc9_WxhuUyaaAwRpUAL7PJ1Y2RAZjm_DakFJwPvlFqcO_Y3SDD6gDrf1Arwzl4UJ-azbPTcm6-y1TMGV5HxQFqwsVd5pgxz9p-lL4pTE5h7iJw3JR2s1rfW8lT1fxe8vjLsrEaGgFGRznQfRAONf50DmXEb-iTLHg3r1nOh7HUIGvjbtklFSXW5l1qAEJR4PU4fMxlVOVKtY6vf5dg4jC60IDvUQ-oPpwywuG-nCe8bpKgWQQX65yROmZm7fOBhgsS66Y0Pp3SyrXDw3JrzP2T65QbrsrUKb834-Ko&sa=X&ved=2ahUKEwjsoca_lO6EAxU2h_0HHQTxD3IQxKsJegQIDxAB&ictx=0&biw=1920&bih=919&dpr=1)
> Документ составлен для выполнения лабораторных работ по предмету "Тестирование програмного обеспечения"
#### Тестирование отправки сообщений:
<table>
    <tr>
        <th>Тест кейсы</th>
        <th>Ожидание</th>
        <th>Реальность</th>
    </tr>
    <tr>
        <td>Отправлено сообщение</td>
        <td>Сообщение доступно к прочтению отправителю и получателю</td>
        <td>Сообщение доступно к прочтению отправителю и получателю</td>
    </tr>
    <tr>
        <td>Отправлен большой объём текста(>4000 символов)</td>
        <td>Предупреждение о невозможности отправки</td>
        <td>Отправка текста в нескольких сообщениях</td>
    </tr>
        <td>Скопирован текст с нескольких сообщений</td>
        <td>Ожидание: подсказка о возможности копирования</td>
        <td>Подсказки или кнопки для копирования нет, по команде(ctrl+C) копируется успешно</td>
    </tr>
</table>
