Beautiful_Matrix

#include <bits/stdc++.h>
#include <ctime>
using namespace std;

int main()
{
    ios_base::sync_with_stdio(0);
    cin.tie(0);
    cout.tie(0);
    int matrix[5][5];
    int num1 = 0, num2 = 0;

    for (int i = 0; i< 5; i++)
    {
        for (int j = 0; j< 5; j++)
        {
            cin>>matrix[i][j];
            if(arr[i][j]==1)
            {
                num1=i;  num2 = j ;
            }
        }
    }
    int u = abs((num1 - 2)) + abs((num2 - 2));
cout<<u<<"\n";
    return 0;
}
