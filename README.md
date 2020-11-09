# -Surface-area
/* 

* To change this license header, choose License Headers in Project Properties. 

* To change this template file, choose Tools | Templates 

* and open the template in the editor. 

*/ 

  

package javaapplication7; 

  

/** 

* 

* @author Emona TEELIYING 

*/ 

import java.util.Scanner;//import the Scanner class 

public class JavaApplication7 { 

  

    /** 

     * @param args the command line arguments 

     */ 

    public static void main(String[] args) {  

        // TODO code application logic here 

    int edge; 

    Scanner input = new Scanner (System.in); 

    System.out.println("please enter the edge og the cube;"); 

    // ask user to input number  

      edge = input.nextInt(); 

  

    int surfaceArea = edge*edge; 

    int totalSurfaceArea = 6*surfaceArea; 

    int volume = surfaceArea*edge; 

  

    System.out.println("The surface area of the cube is:" +surfaceArea ); 

    System.out.println("THe total SurfaceArea of the cube is:"+totalSurfaceArea); 

    System.out.println("The volume of the cubeis:"+volume); 

  

  

    }  

} 

 
