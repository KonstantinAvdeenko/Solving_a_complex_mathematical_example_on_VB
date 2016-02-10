Module Module1

    Sub Main()
        Dim b As Integer
        Dim z1, z2 As Double
        Console.WriteLine("Введите значение b")
        b = Convert.ToInt32(Console.ReadLine()) 'Ввод числа b с клавиатуры'
        'Решение примеров по математическим правилам'
        z1 = (Math.Sqrt(Math.Sqrt(Math.Sqrt(Math.Sqrt(Math.Sqrt(Math.Sqrt(2 * b ^ 2) + 1 ^ 2))))) - 64 * b) / ((Math.Sqrt(5) * b) + (2 * Math.Sqrt(b) / 2))
        z2 = Math.Sqrt(2) * b
        'Вывод результатов'
        Console.WriteLine(z1)
        Console.WriteLine(z2)
        Console.ReadLine()
    End Sub

End Module
