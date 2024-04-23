1. Problem : Bottom overflowed by 104 pixels.
Solving: in main.dart changing **final bodyHeight = screenHeight / 1.5;** to **final bodyHeight = screenHeight / 1;**
2. Problem : Incorrect use of ParentDataWidget.
Solving: in main.dart from line 47 we delete child: Expanded(). Expanded can only be with Row(), Column and Flex().
3. Problem : Keyboard is overloading bottom.
Solving: in main.dart line 46: changing body to SingleChildScrollView.
4. Problem : ClientException with SocketException: Connection refused.
Solving: Changing localhost to 10.0.2.2
5. Problem : UI. Minimum loan credit period is 12 months. We have 6.
Solving: in loan_form.dart changing line 154: from 6 months to 12 months.
