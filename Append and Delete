#include<iostream>
#include<cstring>
using namespace std;
int main()
{
	string s,t;
	int k;
	
	cin>>s>>t;
	cin>>k;
	int count=0;
	for(int i=0;i<s.length();i++) 
	{
		if(s[i]==t[i]) count++;
		else break;
	}
	if(k<s.length()+t.length()-2*count) cout<<"No";
	else if(k>s.length()+t.length()) cout<<"Yes";
	else 
	{
		if((k-s.length()-t.length()+2*count)%2==0) cout<<"Yes";
		else cout<<"No";
	}
	
	return 0;
}
