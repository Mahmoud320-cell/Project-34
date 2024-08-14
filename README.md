# Project-34
More parameters

fun main (){

   // person("Safwat",19)
   
    person("Safwat",19,true)
    
    println("========================")
    
    person("Mahmoud",25,false)
}

//fun person(pop:String, age:Int){

  // println("$pop, and your age is $age")
  
//    }

fun person(name:String, age:Int, isHappy:Boolean){

    if (age < 21)
    
        println("your name is $name, and your age is $age")
        
    else
    
        println("Sorry")
       
    println("You are Happy? $isHappy")
    }
