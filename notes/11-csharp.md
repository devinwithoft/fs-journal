# MVC

dotnet new console

extensions VSC 
C#
C# EXTENSIONS 
.NET INSTALL TOOL EXTENSION AUTHORS 

dotnet run 

runs program in CMD 

everything in C# is a class

var x = 6;

not var 
USE INT its an integer

int x = 6;
string greeting = "hello";
char h = 'h'; 
bool cool = true;


difference how many bytes (how much data is stored)
decimal d = 6.8M;  goes out to 64 decimal  MOST DATA
double f = 5.5; 
float y = 5.7F; goes out to 16 decimal points  LEAST DATA 


Dictionary<int, string> weird = new Dictionary<int, string>();
weird.Add(0, "sup");
weird.Add(1,"hey");
 
 Dictionary<string, string> normal = new Dictionary<string, string>();
 normal.Add("greeting, "hello class");
 normal.Add("farewell, "Later Gators");


 Console.WriteLine(normal["greeting"]);
 Console.WriteLine(normal["farewell"]);


Array<int> array = new System.Array<int>();


int[] numbers = {2,3,5,6};
string[] strings = {"hellow", "arrays", "arenot"};

List<int> list = new List<int>() {12, 120};
list.Add(11)
Console.Writeline(list.Count)
list.Remove(11)

If Dictionary is too specific make a class

List<Cat> catHotel = new List<Cat>();
catHotel.Add(new Cat("Maxwell", 2, "yellow"));
catHotel.Add(new Cat("Abraham", 11, "black"));
catHotel.Add(new Cat("Peter", 11, "Grey"));


WriteLine = log


string choice = Console.ReadLine();
Cat picked = catHotel.Find(c => c.name == choice)
Console.WriteLine(picked.name + "" + picked.color + "" + picked.getGeneralAge());

class Cat   can have a public method constructor 
{
  public string name;                  is private
  private int age;
  public string color;


V have to declare return type
public  string getGeneralAge(){
  if(name > 6){
    return "old";
  } else
  {
    return "young";
  }
}

  public Cat(string name, int age, string color)
  {
    this.name = name;
  this.age = age;
  this.color = color;
  }
}



private class = only things within same name space can access cat (name space is kind of the whole class wrapping a page)
internal
and public
readonly



namespace takes over importing and exporting 




have to semicolon at the end of every line to show it is done


npm i becomes
nuget 
dotnet - auth  
dotnet restore = npm i 


startup cs