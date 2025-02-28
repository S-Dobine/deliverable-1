/*
 
 //First, ask the user, “How many sodas have been sold today? 100 in stock” Expect the user to enter a number. 
 You’ll need to parse the input and store it in a number variable.
 
   You can now calculate the remaining stock of Soda.
   
    If the user enters a number higher than is in that item’s stock, tell the user that is “Too high” and don’t adjust the stock. 
    Print out the remaining stock. 
    
    Repeat these steps for each of the items in the store until you have gone through all items. 
   
   Now that all of the items have their remaining stock figured out, figure out whether each item needs a restock. 
    If the remaining stock is less than or equal to the restock value print out which item needs to be restocked.
    
     Repeat this process until all items have been checked.
   
   Build Specifications
 * Soda starts with 100 in stock and will need a restock at 40
   Chips starts with 40 in stock and will need a restock at 20
   Candy starts with 60 in stock and will need a restock at 40
   Each item should have a variable that holds its current stock value and a variable that holds the restock value.
    
 */

using System.Threading.Channels;

Console.WriteLine("How many sodas have been sold today? 100 in stock");
{
    int sodasSold = int.Parse(Console.ReadLine());
    int total = 100 - sodasSold;

    if (sodasSold >= 100)
    {
        Console.WriteLine("Too Many!");
        Console.WriteLine(total + sodasSold);
    }
    else if (sodasSold <= 59)
    {
        Console.WriteLine("Remaining Stock " + total);
    }
    else if (sodasSold >= 60)
    {
        Console.WriteLine("Restocking Time " + total);
    }
}

Console.WriteLine("How many chips have been sold today? 40 in stock");
{ int chipsSold = int.Parse(Console.ReadLine());
    int total = 40 - chipsSold;

    if (chipsSold >= 40)
    {
        Console.WriteLine("Too Many!");
        Console.WriteLine(total + chipsSold);
    } else if (chipsSold <= 19)
    {
        Console.WriteLine("Remaining Stock " + total);
    }
        else if (chipsSold >= 20)
        {
            Console.WriteLine("Restocking Time " + total);
        }
}

Console.WriteLine("How much candy has been sold today? 60 in stock");
{ int candySold = int.Parse(Console.ReadLine());
    int total = 60 - candySold;

    if (candySold >= 60)
    {
        Console.WriteLine("Too Many!");
        Console.WriteLine(total + candySold);
    } else if (candySold <= 39)
    {
        Console.WriteLine("Remaining Stock " + total);
    }
    else if (candySold >= 40)
    {
        Console.WriteLine("Restocking Time " + total);
    }
}

