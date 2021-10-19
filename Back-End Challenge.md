Question 1


public static string checkMultiple(string word){
  int length = 8;
  
  if (length % 2 == 0 && % 4 == 0)
    return "stack overflow";
      if (lenght % 2 == 0)
        return "stack";
      if (lenght % 4 == 0)
        return "overflow";
        
  return "not stack or overflow";
 }
 
 
 
 Question 2
 
 
 using System;
 
 class Program {
    public static void Main (string[] args) {
        Horse horse = new Horse();
        console.WriteLine (horse.Eat());
        console.WriteLine (horse.MakeNoise());
        
        console.WriteLine ("============================================");
        
        Sheep sheep = new Sheep();
        console.WriteLine (sheep.Eat());
        console.WriteLine (sheep.MakeNoise());
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
       return "Neigh"
     }
    }
    
    publc class sheep:Sheep:Animal{
     public override string  MakeNoise(){
       return "Baah"
     }
    }
        
        
