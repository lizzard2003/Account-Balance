#include <iostream>

double starting_balance;
double deposit;
double withdrawal; 
double total;

int main() {
  std::cout << "What is the starting Balance?";
  std::cin>> starting_balance;
  std::cout << "What amount was deposited?";
  std::cin>> deposit;
  std::cout << "What is the amount withdrawn?";
  std::cin>> withdrawal;
  total= starting_balance+deposit-withdrawal;

  std::cout<< "The amount left is : " << total;
}# Account-Balance
