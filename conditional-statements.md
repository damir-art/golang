# Условные операторы

## if

    num := 3
    if num > 0 {
      fmt.Println("Num больше 0")
    }

## if else

    num := 0
    if num > 0 {
      fmt.Println("Num больше 0")
    } else {
      fmt.Println("Num меньше или равно 0")
    }

## if else if

    func main() {
      num := 0
      if num > 0 {
        fmt.Println("Num больше 0")
      } else if num < 0 {
        fmt.Println("Num меньше 0")
      } else {
        fmt.Println("Num равно 0")
      }
    }
