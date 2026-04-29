// calculator-with---
#include <iostream>
#include <string>

int main() {
	std::cout << "___________KALKULATOR____________" << std::endl;
	std::cout << "VNESI PRVO STEVILO:" << std::endl;
	double PRVOSTEVILO;
	std::cin >> PRVOSTEVILO;
	if (PRVOSTEVILO > 0) {





	}
	else {

		std::cout << "stevilo ni pravilno" << std::endl;
		return 0;
	}
	std::string operacija;

	std::cout << "daj mi operacijo(+,-,/):" << std::endl;
	std::cin >> operacija;
	if (operacija == "+" || operacija == "/" || operacija == "-" || operacija == "%") {



		std::cout << "VNESI DRUGO STEVILO" << std::endl;
		


	}
	else {



		std::cout << "Nisi vnesel prave operacije!" << std::endl;
	}
	double rezultat;
	double drugost;
	std::cin >> drugost;

	if (operacija == "+") {
		rezultat = PRVOSTEVILO + drugost;

}
	else if (operacija == "-") {

		rezultat = PRVOSTEVILO + drugost;

	}
	else if (operacija == "/") {

		rezultat = PRVOSTEVILO / drugost;

	}

	std::cout << "REZULTAT JE:" << rezultat << std::endl;
		
	return 0;
}
