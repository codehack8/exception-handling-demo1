# exception-handling-demo1
package com.qis.corejava.exceptionhandling;

public class ExceptionDemo1 {
      String name=null;
	 public void mydata()
	 { System.out.println("One");
	       System.out.println(name.length());
		 
	 }	
	public static void main(String[] args) {
		ExceptionDemo1 ed1=new ExceptionDemo1();
		ed1.mydata();

	}

}
