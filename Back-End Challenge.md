Question 1

using System;
class Program{
  public static void Main (string[] args) {
  
    //console.ReadLine to get a users input and store it in a variable to use in the checkMultiple function
    
    string word = Console.ReadLine ("Enter word");
    Console.WriteLine (checkMultiple(word));
    }
    
  public static string checkMultiple(string word){
    int length = word.Length;
  
    if (length % 2 == 0 && % 4 == 0)
     return "stack overflow";
      if (length % 2 == 0)
        return "stack";
      if (length % 4 == 0)
        return "overflow";
        
  return "not stack or overflow";
 }
}
 
 
 
 Question 2
 
 
 using System;
 
 class Program {
    public static void Main (string[] args) {
        Horse horse = new Horse();
        Console.WriteLine (horse.Eat());
        Console.WriteLine (horse.MakeNoise());
        
        Console.WriteLine ("============================================");
        
        Sheep sheep = new Sheep();
        Console.WriteLine (sheep.Eat());
        Console.WriteLine (sheep.MakeNoise());
  }
}

public class Animal {
    public string Eat(){
      return "Yummy";
    }
    
    public virtual string MakeNoise(){
      return "Durr";
      }
    }
    public  class Horse : Animal {
     public override string MakeNoise(){
       return "Neigh";
     }
    }
    
    publc class sheep: Animal{
     public override string  MakeNoise(){
       return "Baah";
     }
    }
        
        
