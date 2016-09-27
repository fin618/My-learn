# My-learn

#include <string>
#include <iostream>

int main()
{
	std::string str1 ("This is a C++ string!");
	
	std::cout << "str1 = " << str1 << std::endl;

	std::string str2;

	str2 = str1;

	std::cout << "Result of assignment, str2 = " << str2 << std::endl;

	str2 = "Hello string!";
	
	std::cout << "After over-writing contnets, str2 = " << str2;
	std::cout << std::endl << std::endl;

	std::string strAddResult;

	strAddResult = str1 + str2;

	std::cout << "The result of str1 + str2 is = " << strAddResult;

	return 0;
}
