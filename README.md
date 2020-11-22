# Отчёт о тестировании приложения "Money Transfer"
## Краткое описание
После тестирования Money Transfer, обнаружилось что приложение неправильно считает сумму. 

## Описание тестов
Проводилось функциональное тестирование, а именно операция сложения текущего счета (current) и суммы перевода (remittance)

## Результаты
Проведен 1 тест;

Успешных тестов - 0%;

Неуспешных тестов - 100%;

["Неправильное значение в результате сложения в приложении"](https://github.com/evgen-911/Bank1/issues/1#issue-748224902)

## Общие рекомендации
Необходимо заменить операторы int на long
