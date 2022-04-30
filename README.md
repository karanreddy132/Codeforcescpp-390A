# Codeforcescpp-390A
#include<bits/stdc++.h>
using namespace std;

int main(){
  int n,ele1,ele2;
  set<int> s,t;
  cin >> n;
  for(int i=0;i<n;i++){
    cin >> ele1 >> ele2;
    s.insert(ele1);
    t.insert(ele2);
  }
  cout << min(s.size(),t.size());
  return 0;
}
