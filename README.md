System.Console.Write ("Iltimos! Ismingizni yozing:");
string name = Console.ReadLine(); 
string greeting = $"Salom,{name}";
System.Console.WriteLine(greeting);

System.Console.Write ("Nechinchi yilda tug'ilgansiz: ");
string num = Console.ReadLine();
Console.WriteLine();
Console.WriteLine($"Siz {num}-yilda tug'ilgansiz");

System.Console.Write (" Sizning yoshingiz nechchida: ");
string ageAsString = Console.ReadLine();
int age = Convert.ToInt32(ageAsString);
System.Console.WriteLine($"Sizning yoshingiz {ageAsString} da");

int keschasAge = 5;
int ageDifference =  age - keschasAge;
System.Console.WriteLine($"Siz va kescha bilan yoshingiz o'rtasidagi farq {ageDifference}");
