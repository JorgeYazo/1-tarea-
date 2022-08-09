# 1-tarea-
public class MyClass {
   
package com.mycompany.tarea__1;

import java.util.Scanner;

import java.util.Arrays;

public class Tarea__1 {

    public static void main(String[] args) {
        
        int c = 0;
       
        int[] listanumero = new int[5];

        Scanner digitos  = new Scanner(System.in);

        for(c=0; c<listanumero.length; c++)
        {
            System.out.println("anote un dato: ");
            
            listanumero[c] = digitos.nextInt();
        }

        for(c=0; c<listanumero.length; c++)
        {
            System.out.println("La lista ingresada fue : "+listanumero[c]);
        } 
    }
}
