#include  <iostream>

using namespace  std;

int main(){
  int a,b,c;
  cin>>a,b;
  while (b){
  c=a%b;
  a=b;
  b=c;
  }
  cout<<  "Otvet:  "<<endl;
  cout<<a<<endl;
  return 0;
 }
