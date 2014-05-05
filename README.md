prime
=====
package com.sai.hellosai;

public class PrimeModify {
	
	public static void main(String args[]){
		int i;
		
		 
		for(  i =2;i<=20;i++){
			
			boolean prime = true;			
				
			if( i % 2  == 0  & i !=2){
					  prime = false;
			}
			else {
				for(int j = 2;j<i-1;j++){
					if(i%j == 0){
						  prime = false;
						break  ;
					}
				}
			}
			 	 
		if(prime == false){
			System.out.println("Not prime" + i);
		}
			else{
			System.out.println("prime" + i);
			}
		}
 
	}
		}
 
