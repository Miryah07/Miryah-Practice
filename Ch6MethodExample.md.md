
public class Methods {

	public static void main(String[] args) {

		int integer = 5;
		double floatValue = 5.0;

		System.out.println("This is in the main mathod");
		RyahPrintStatemt();
		System.out.println("This is back inside the main method");
		RyahPrintStatemt();

	}


	private static void RyahPrintStatemt() {


		System.out.println("This is inside my method");
		System.out.println(integer);
	}

}


