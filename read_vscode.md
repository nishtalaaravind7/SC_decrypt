# Monte Carlo Method for Breaking a Substitution Cipher


Using the Monte Carlo method of cipher breaking, this C++ application decrypts a given ciphertext. It makes 10,000 iterations to discover the optimal decryption key using bigram frequencies supplied in "bigram.txt" to assess the possibility of various keys.

Make sure the following files are in the same directory as the program as a prerequisite:
  Bigram frequencies based on English-language text are contained in the text file "bigram.txt."
  'testInput.txt' is the input ciphertext that you want to decipher.

Program Execution in Visual Studio Code:

Launch Visual Studio first.
You might need to install the "C++" extension for Visual Studio Code if you haven't previously. From the Extensions view, perform a search for "C++."
Open a new terminal in Visual Studio Code by clicking "Terminal" in the top menu and choosing "New Terminal." This will launch Visual Studio Code's terminal.
In the terminal, use the 'cd' command to go to the directory where your C++ program is placed. '/path/to/your/program/directory' should be replaced with the actual path.
   bash
     cd /path/to/your/program/directory
    Here we can use the 'g++' compiler to compile your C++ software. Change 'decryptsub.cpp' to the filename of the program that we have done.
    bash
     g++ decryptsub.cpp -o decryptsub
Now run the program.
     bash
     ./decryptsub 
Now we use this command for running THE 10000 iterations in the code.

After code executes corectly we get "testOutput.txt" file which is present in the same directory. We can find the decrypted text and key.
