# may11_2025
The problem that i solved today in leetcode

1.Given an integer array arr, return true if there are three consecutive odd numbers in the array. Otherwise, return false.

Code:
class Solution {
    public boolean threeConsecutiveOdds(int[] arr) {
        for(int i=0;i<arr.length-2;i++)
        {
            if(arr[i]%2==1 && arr[i+1]%2==1 && arr[i+2]%2==1)
                return true;
        }
        return false;
    }
}
