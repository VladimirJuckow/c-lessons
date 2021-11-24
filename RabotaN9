#include <iostream>
#include <string>

#define in std::cin
#define out std::cout
#define clear system("cls")
#define use_color system("color 0E")

void fillIntArray(int arr[10]) {
    for (int i = 0; i < 10; i++) {
        arr[i] = i;
    }
}

void fillShortArray(short arr[10], int multuiplier) {
    for (int i = 0; i < 10; i++) {
        arr[i] = i * multuiplier;
    }
}

void fillFloatArray(float arr[10]) {
    for (int i = 0; i < 10; i++) {
        arr[i] = i % 4;
    }
}

void fillDoubleArray(double arr[10]) {
    for (int i = 0; i < 10; i++) {
        arr[i] = i * 100;
    }
}

void fillCharArray(char arr[10], int startSymbol) {
    for (int i = 0; i < 10; i++) {
        arr[i] = startSymbol;
        startSymbol++;
    }
}

void fillStringArray(std::string arr[10]) {
    for (int i = 0; i < 10; i++) {
        arr[i] = "Это " + std::to_string(i + 1) + " итерация заполнения массива";
    }
}

void fillBoolArray(bool arr[10]) {
    for (int i = 0; i < 10; i++) {
        if (i % 2 == 0) {
            arr[i] = 0;
        }
        else {
            arr[i] = 1;
        }
    }
}

void drawSeparator(int length) {
    out << "\n";
    for (int i = 0; i < length; i++) {
        out << "-";
    }
    out << "\n";
}

void displayArray(int arr[10] = NULL, short arr1[10] = NULL, float arr2[10] = NULL, double arr3[10] = NULL, char arr4[10] = NULL, std::string arr5[10] = NULL, bool arr6[10] = NULL) {
    if (arr != NULL) {
        out << "Целочисленынй массив:\n\n";
        for (int i = 0; i < 10; i++) { 
            out << arr[i] << "\n";
        }
        drawSeparator(30);
    }

    if (arr1 != NULL) {
        out << "Short массив:\n\n";
        for (int i = 0; i < 10; i++) {
            out << arr1[i] << "\n";
        }
        drawSeparator(30);
    }

    if (arr2 != NULL) {
        out << "Float массив:\n\n";
        for (int i = 0; i < 10; i++) {
            out << arr2[i] << "\n";
        }
        drawSeparator(30);
    }

    if (arr3 != NULL) {
        out << "Вещественный массив:\n\n";
        for (int i = 0; i < 10; i++) {
            out << arr3[i] << "\n";
        }
        drawSeparator(30);
    }

    if (arr4 != NULL) {
        out << "Символьный массив:\n\n";
        for (int i = 0; i < 10; i++) {
            out << arr4[i] << "\n";
        }
        drawSeparator(30);
    }

    if (arr5 != NULL) {
        out << "Строковый массив:\n\n";
        for (int i = 0; i < 10; i++) {
            out << arr5[i] << "\n";
        }
        drawSeparator(30);
    }

    if (arr6 != NULL) {
        out << "Строковый массив:\n\n";
        for (int i = 0; i < 10; i++) {
            out << arr6[i] << "\n";
        }
        drawSeparator(30);
    }
}

int main()
{
    setlocale(0, "");

    use_color;

    int arr[10];
    short arr1[10], arr7[10];
    float arr2[10];
    double arr3[10];
    char arr4[10];
    std::string arr5[10];
    bool arr6[10];

    fillIntArray(arr);
    fillShortArray(arr1, 5);
    fillShortArray(arr7, -7);
    fillFloatArray(arr2);
    fillDoubleArray(arr3);
    fillCharArray(arr4, 200);
    fillStringArray(arr5);
    fillBoolArray(arr6);

    displayArray(arr, arr1, arr2, arr3, arr4, arr5, arr6);
    displayArray(NULL, arr7, NULL, NULL, NULL, NULL, NULL);

    return 0;
}