# range
range - цикл для перебора массивов, срезов.

## Срез

    nums := []int{ 1, 2, 3, 4, 5 }
    for index, element := range nums {
      fmt.Printf("Индекс: %d, Элемент: %d\n", index, element)
    }

Не используем `index`:

    nums := []int{ 1, 2, 3, 4, 5 }
    for _, element := range nums {
      fmt.Printf("Элемент: %d\n", element)
    }

## Двумерный массив

    matrix := [][]int{ {1, 2, 3}, {4, 5, 6}, {7, 8, 9} }
    for _, element := range matrix {
      for _, element := range element {
        fmt.Printf("Ячейка: %d ", element)
      }
      fmt.Println() // переход на новую строку
    }
