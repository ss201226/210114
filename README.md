# 210114
//incomplete

import java.util.Scanner;

public class CodeUp1571 {

public static void main(String[] args) {
		
		f();
	}
	static void f() {
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		int[] arr=new int[n];
		for (int i = 0; i < n; i++) {
			 arr[i]=sc.nextInt();
		}
		int k=sc.nextInt();
		int result=0;
		for (int i = 0; i < n; i++) {
			if(arr[i]>=k) {
				result= i+1;
				break;
			}else{
				result= n+1;
			}
		}
		System.out.println(result);
		
	}
 }
