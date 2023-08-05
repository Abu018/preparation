#include <bits/stdc++.h>
using namespace std;
long long subArray(int arr[], int n)
{
    long sum = 0;
    long maxi = INT_MIN;
    for (int i = 0; i < n; i++)
    {
        sum = sum + arr[i];
        maxi = max(maxi, sum);
        if (sum < 0)
            sum = 0;
    }
    return maxi;
}
int main()
{
    int n;
    cin >> n;
    int arr[n];
    for (int i = 0; i < n; i++)
    {
        cin >> arr[i];
    }
    long result = subArray(arr, n);
    cout << result;
    return 0;
}
