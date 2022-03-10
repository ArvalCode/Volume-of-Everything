#include <iostream>
#include <string>
#include <math.h>
#include <cmath>
#include <Windows.h>

// Function Prism/Cylinder

void PrismCylinder() {

	std::string input;
	float volume;
	float height;
	float radius;
	const float pie = 3.14;
	
	std::string input;

	if (input == "Prism/Cylinder") {
		system("cls");
		std::cout << "Prism/Cylinder (Type: Radius/Volume/Height)\n";
		std::cin >> input;

		if (input == "Radius") {
			system("cls");
			std::cout << "Volume: ";
			std::cin >> volume;

			std::cout << "\nHeight: ";
			std::cin >> height;

			std::cout << "\n\n\n Radius = " << sqrt(volume / (height * pie));
		}

		else if (input == "Volume") {
			system("cls");
			std::cout << "Radius: ";
			std::cin >> radius;

			std::cout << "\Height: ";
			std::cin >> height;

			std::cout << "Volume: " << pie * pow(radius, 2) * height;
		}
		else if (input == "Height") {
			system("cls");
			std::cout << "Radius: ";
			std::cin >> radius;

			std::cout << "\nVolume: ";
			std::cin >> volume;

			std::cout << "Height: " << volume / (pie * pow(radius, 2));
		}
	}
}


void cone() {

	std::string input;
	float volume;
	float height;
	float radius;
	const float pie = 3.14;
	
	std::string input;

	if (input == "Cone") {
		system("cls");
		std::cout << "Cone (Base/Height/Volume)\n";
		std::cin >> input;

		if (input == "Base") {
			system("cls");
			std::cout << "Radius: ";
			std::cin >> radius;

			std::cout << "Base: " << pie * pow(radius, 2);
		}
		if (input == "Height") {
			system("cls");
			std::cout << "Volume: ";
			std::cin >> volume;

			std::cout << "\nRadius: ";
			std::cin >> radius;

			std::cout << "Height: " << 3 * (volume / (pie * pow(radius, 2)));
		}
		if (input == "Volume") {
			system("cls");
			std::cout << "\nHeight: ";
			std::cin >> height;

			std::cout << "\nRadius: ";
			std::cin >> radius;

			std::cout << "\nVolume: " << pie * pow(radius, 2) * (height / 3);
		}
	}
}

	int main() {

		std::cout << "Volume (Type Prism/Cylinder, *Pyramid, Cone, *Sphere)\n";
		std::cin >> input;

		// Prism/Cylinder
		PrismCylinder();
		// Cone
		cone();
		return 0;
	}
