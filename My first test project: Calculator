#include <iostream> 
float divide(int a, int b){ 
    return a/b; 
} 
int mul(int a, int b){ 
    return a*b; 
} 
int sum(int a, int b){ 
    return a+b; 
} 
int sub(int a, int b){ 
    return a-b; 
} 
int main() { 
    int x; 
    int y; 
    float ans; 
    char opp; 
    
    std::cout << "Enter a number:"; 
    std::cin >> x; 
    std::cout << "Enter another number:"; 
    std::cin >> y; 
    std::cout << "Enter an operator (+,-,/,*):"; 
    std::cin >> opp; 
    
    switch(opp) { 
        case '+': ans = sum(x, y); break; 
        case '-': ans = sub(x, y); break; 
        case '*': ans = mul(x, y); break; 
        case '/': ans = divide(x, y); break; 
        default: std::cout << "Invalid operator!" << std::endl; return 1; 
    } 
std::cout << "The answer is:" << ans << std::endl; 
return 0;
}