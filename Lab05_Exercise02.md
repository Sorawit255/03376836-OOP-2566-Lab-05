# Lab 5 Exercise 2

## การประกาศสมาชิกในคลาส (fields)


1. สร้าง console application project

```
dotnet new console --name Lab05_Ex02
```
2. เปลี่ยน code ให้เป็นดังต่อไปนี้

```cs
Person p = new Person();
p.name = "Rambo";
p.id = "1987";
p.income = 2500;
System.Console.WriteLine($"Type of p is {p.GetType()}");
System.Console.WriteLine($"p.name = {p.name}\ttype = {p.name.GetType()}");
System.Console.WriteLine($"p.id = {p.id}\ttype = {p.id.GetType()}");
System.Console.WriteLine($"p.income = {p.income}\ttype = {p.income.GetType()}");

class Person
{
    string name;
    string id;
    int income;
}
```

3. Build project โดยการใช้คำสั่ง

```
dotnet build  Lab05_Ex02
```

4. บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3

5. Run project โดยการใช้คำสั่ง

```
dotnet run --project Lab05_Ex02
```

6. บันทึกผลที่ได้จากการรันคำสั่งในข้อ 4


7. อธิบายสิ่งที่พบในการทดลอง


