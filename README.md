# Search-Algorithms

public class linearSearch1 {
	linearSearch1(int numbers, int numbersSize, int key) {
		  int i = 0;

		   for (i = 0; i < numbersSize; ++i) {
		      if (numbers[i] == key) {
		        return i
		      }
		   }
		      
		   return -1 // not found
		}
		   
	

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		 numbers = {2, 4, 7, 10, 11, 32, 45, 87}
		   int NUMBERS_SIZE = 8;
		   int i = 0;
		  int key = 0;
		   int keyIndex = 0;
		      
		   print("NUMBERS: ");
		   for (i = 0; i < NUMBERS_SIZE; ++i) {
		      print(numbers[i] + " ");
		   }
		   printLine();
		      
		   print("Enter a value: ");
		   key = getIntFromUser();
		      
		   keyIndex = LinearSearch(numbers, NUMBERS_SIZE, key);
		      
		   if (keyIndex == -1) {
		      printLine(key + " was not found.");
		   } 
		   else {
		      printLine("Found " + key + " at index " + keyIndex + ".");
		   }
			   
	}


}
