# Отчёт о тестировании  Precision
## Краткое описание

17.01.2021 за 1 час на macOS Catalina v 10.15.7 + Java11 было проведено функциональное тестирование функции пополнения бонусного счета.
Функция не работает.

## Описание тестов
Запускаем наш код:
public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }
}
или запускаем его с остановами с помощью Debug.

## Результаты
 0.8999999999999999

В результате тестирования выявлены следующие дефекты:

 * https://github.com/tosolya/java2.1/issues/1

# Общие рекомендации
 Рекомендаций нет, т.к. не ясна причина.
 