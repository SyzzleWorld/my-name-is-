package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner keyboard = new Scanner(System.in);
	// Write a Java program that assigns your name to a variable and prints the variable to the console.

        String name;
        String lname;
        int age;


        System.out.print( "What's your name? " );
        name = keyboard.next();


        System.out.print( "What's your last name? " );

        lname = keyboard.next();
        System.out.print( "How old are you " + name + " " + lname + "?");

        age = keyboard.nextInt();

        System.out.print("Your name is " + name + " " + lname + "." + "You are " + age + ".");



    }
}
