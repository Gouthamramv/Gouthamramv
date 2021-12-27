package week1.day1;

public class mobile1 {
	
public void makeCall() {
System.out.println("calls disconnecting");
}

public void sendMsg() {
System.out.println("calls answered");
}

public static void main(String[] args) {
	
	mobile1 myCalls = new mobile1();
	mobile1 otherCalls = new mobile1();
				
			myCalls.makeCall();
			otherCalls.sendMsg();
				
	
}
}
