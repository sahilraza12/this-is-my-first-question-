 
 import java.util.*;

public class JavaBasics{
public static void main(String args[]){
    Scanner sc = new Scanner (System.in);
    int pen = sc.nextInt();
    int pencil = sc.nextInt();
    int eraser = sc.nextInt();

    float TotalCost = pen + pencil + eraser;

    System.out.println(TotalCost);

    float newTotalCost = TotalCost +(0.18f * TotalCost );
  
    System.out.println("Total Bill with GST" +newTotalCost);
}
}

