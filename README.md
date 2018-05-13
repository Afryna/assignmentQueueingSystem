# assignmentQueueingSystem
'''
public class AssignmentQueueingSystem{
     public static void main (String[]args){
         Random rand = new Random ();
         int randN = rand.nextInt(50);
         int randV = rand.nextInt(25);
         
         System.out.println("Number of non-member customer: " + randN);
         System.out,println("Number of VIP-member customer: " + randV);
         
         for (int i=1; i < randN; i++)
         {
            //decide counter untukk customer
         }
         
         for (int o=1; o < randV; o++)
         { 
             // decide counter untuk customer
         }
         
         Tutorial tut = new Tutorial();
         tut.runTimer();
     }
     
     Timer timer = new Timwe();
     int i = 0;
     TimerTask task = new TimerTask()
     {
          public void run () 
          {
              System.out.println(i);
              i++;
          }
     };
     
     public void runTimer()
     {
         timer.schedule(task, 0, 1000);
     }
 }
'''
