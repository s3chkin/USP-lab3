public class HelloWorld{
 public static void main (String [] args){
    //TODO Auto - generated method stub
    System.out.println("Hello World!");
    Greeting gr = new Greeting();
    gr.greetItalian();
   }
    public void greetEnglish(){
        System.out.print("Hello");
   }
   public void greetItalian(){
   System.out.print("Ciao");
   }
}