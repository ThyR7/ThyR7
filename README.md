# Setup VSCode for C++

- Remember to replace `C:\\Program Files\\CodeBlocks\\MinGW\\bin\\g++.exe` with your own compiler path in `settings.json`.

1. Just Navigate to settings.json file in `C:/Users/username/AppData/Roaming/Code/User/settings.json`
2. Replace that file with `settings.json` fromm this repo.
3. Then open VSCode and make a file named `first.cpp`
4. Write your cpp code here.
   ```cpp
	#include<iostream>
	#include<conio.h>
	using namespace std;

	int main(){
		int i,j;
		cout<<"Hello World!";
		getch();
		return 0;
	}
   ```
5. Goto Run and select `Run withour debugging` or `Ctrl + F5`
6. Select compiler from list.

7. If `.vscode/tasks.json` not made automatocally, you can copy paste it from here.

8. Consider adding `C:\Program Files\CodeBlocks\MinGW\bin` to path.


If any error persists, Consider consulting [ChatGPT](https://chat.openai.com)
