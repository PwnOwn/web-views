# BinSeacrh

## BinSeacrh algorithm
code

```
int BinSearch(int r[],int n,int k) {
    int low =0;
    int high = n-1;
    int mid;
    while (low <= high) {
        mid = (low + high) / 2;a
        if (k < r[mid]) high = mid -1;
        else if (k > r[mid]) low = mid + 1;
        else return mid + 1; 
    }
    return 0;
}

```