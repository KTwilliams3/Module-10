# Module-10
The Name Game

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
  
  Scanner sc = new Scanner(System.in);

  String name, piece;
  char initial;

  System.out.println("What is your name?");
  name = sc.nextLine();
  piece = name.substring(1);
  initial = name.toUpperCase().charAt(0);

  if(initial =='B')
    System.out.println(name + ", " + name + ", Bo-" + piece);
  else
    System.out.println(name + ", " + name + ", Bo-B" + piece);

  if(initial == 'F')
    System.out.println("Bo-na-na fanna fo-" + piece);
  else
    System.out.println("Bo-na-na fanna fo-f" + piece);

  if(initial == 'M')
    System.out.println("Fee fi mo-" + piece + ", " + name + "!");
  else
    System.out.print("Fee fi mo-m" + piece + ", " + name + "!");
  
  }
} 
