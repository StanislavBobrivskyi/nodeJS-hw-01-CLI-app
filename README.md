# nodeJS-hw-01-CLI-app

# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action list https://monosnap.com/file/UoUYKd33itnda0KNU6QFHyKL3aV1OY

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6 https://monosnap.com/file/crBnCt2Q5QHTmAfimyiLtm26xcj0Lp

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22 https://monosnap.com/file/DYMgPyBTxlz3roVOIGeV7nMoObvGG6

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH https://monosnap.com/file/1palKZDFS0Ew6WuCMHlKeROfY6B9Ee

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту - null, якщо контакту з таким id не існує.

node index.js --action remove --id qdggE76Jtbfd9eWJHrss https://monosnap.com/file/deFrK7BZziszidhhMJcIsbho97ZHWh
