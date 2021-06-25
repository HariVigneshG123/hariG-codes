# hariG-codes
public class Recprac {
    static int i=0;
    public static String display(String str1,int count){
        System.out.println(str1+" "+i);
        i++;
        if(i>=count){
         return "Inside base case : "+i;
        }else{
            return display(str1,count);
//            display("Hari",count);
        }
    }

    public static void main(String[] args){
        System.out.println(display("vignesh",5));
    }
}
