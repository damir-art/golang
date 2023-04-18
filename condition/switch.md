# switch
switch - проверка переменной на соответствие какому-либо значению.

## case

    name := "Ivan2"

    switch name {
    case "Ivan1":
      fmt.Println("Иван 1")
    case "Ivan2":
      fmt.Println("Иван 2")
    case "Ivan3":
      fmt.Println("Иван 3")
    }

## default

    name := "Ivan"

    switch name {
    case "Ivan1":
      fmt.Println("Иван 1")
    case "Ivan2":
      fmt.Println("Иван 2")
    case "Ivan3":
      fmt.Println("Иван 3")
    default:
      fmt.Println("Совпадений не найдено")
    }

## break
Оператор `break` внутри `case`, вставляется автоматически.

## fallthrough
Чтобы отменить `break`, нужно использовать оператор `fallthrough`.

    num := 1

    switch {
    case num > 0:
      fmt.Println("Число больше 0")
      fallthrough
    case num < 0:
      fmt.Println("Число меньше 0")
    default:
      fmt.Println("Число равно 0")
    }

## Операторы сравнения

    num := 0

    switch {
    case num > 0:
      fmt.Println("Число больше 0")
    case num < 0:
      fmt.Println("Число меньше 0")
    default:
      fmt.Println("Число равно 0")
    }
