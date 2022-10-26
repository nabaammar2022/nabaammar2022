public class Account
   {
      private String name; // instance variable
      private double balance; // instance variable
 
   public Account(String name, double balance)
    {
       this.name = name; 

         if (balance > 0.0) // if the balance is valid                       
            this.balance = balance; // assign it to instance variable balance
     }


      public void deposit(double depositAmount)                        
      {                                                                
         if (depositAmount > 0.0) // if the depositAmount is valid     
           balance = balance + depositAmount; // add it to the balance
     }                                                                

     
      public double getBalance()           
    {                                    
        return balance;                   
     }                                    

     
     public void setName(String name)
     {
        this.name = name;
     }

     
     public String getName()
    {     return name; 
44      } 
45   }
