Object Reference



package com.bini.babu;

public class ObjectReferenceDemo {
        int x;
	ObjectReferenceDemo(){
		
	}
	
	public static void main(String[] args) {
		ObjectReferenceDemo ord = new ObjectReferenceDemo();
                System.out.println(ord.x);
	}

}



Output

0


ord variable will hold the address of 'new ObjectReferenceDemo()' because the constructor does not return any value it will send the address location  ( i.e  new ObjectReferenceDemo();). Hence ord will point to the address location of 'ObjectReferenceDemo'.
 
