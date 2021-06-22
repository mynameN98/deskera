# deskera
int x=arr[n-1], i; for(i=n-1; i>0; i--) arr[i]=arr[i-1]; arr[0]=x; } int main() { int arr[]={1, 2, 3, 4, 5}, i; int n=sizeof(arr)/sizeof(arr[0]); cout&lt;&lt;"Given Array is"; for (i=0; i&lt;n; i++) cout &lt;&lt; arr[i] &lt;&lt; ' '; rotate(arr, n); cout &lt;&lt; "\nRotated array is\n"; for (i=0; i&lt;n; i++) cout &lt;&lt; arr[i] &lt;&lt; ' '; return 0;
