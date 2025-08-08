# Assignment-6


  // 1st 
  int limit = 10; 
  int a = 0; 
  int b = 1; 

  print("Fibonacci series up to $limit:");

  print(a);

  
  for (int i = 0; b <= limit; i++) {
  print(b);
  int next = a + b; 
  a = b;  
  b = next;
  
  }
      
   // 2nd
   
   
   List<int> numbers = [3, 9, 1, 6, 4, 2, 8, 5, 7];
   
   int largest = numbers[0];

   for (int i = 1; i < numbers.length; i++) {
     if (numbers[i] > largest) {
      largest = numbers[i]; 
    }
  }

   print("Largest element: $largest");
   
   
 
   // 3rd 
   
    int x = 5;
   
    for(int i = 1; i <=10; i++){
    int result = x * i;
     
    print("$x * $i = $result");
   }
   
   
   // 4th
   
   
  String x = "radar"; 
  String reversed = "";
   
  for(int i = x.length - 1; i >= 0; i--){
        reversed = reversed + x[i];
  }
    if (x == reversed) {
    print('"$x" is a palindrome.');
  } else {
    print('"$x" is not a palindrome.');
  }
   

   // 5th
   
   int rows = 4;

  for (int i = 1; i <= rows; i++) {
    for (int j = 1; j <= i; j++) {
      stdout.write(i);
    }
    print('');
  }
  
   
   // 6th 
   
   List<int> numbers = [2, 7, 4, 10, 1, 6, 3, 8];

  print('Numbers greater than 5:');

  for (int number in numbers) {
    if (number > 5) {
      print(number);
    } else {
   }
  }
   
   
   
   
   
   // 8th
   
  int number = 12345; // Input number
  int count = 0;

  while (number != 0) {
    number = number ~/ 10; // Remove last digit
    count++; // Increase count
  }

  print("Number of digits: $count");
}
     
 }

 



// 10th


 String myTexts = "";
   
   if(myTexts.isEmpty){
     print("My text is empty");
   } else {
     print("My text is Not Empty");
   }
