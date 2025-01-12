# leetcode---2894
class Solution {
    public int differenceOfSums(int n, int m) {
        int t=(n*(n+1))/2;
        int sum=0,d;
        for(int i=1;i<=n;i++){
            if(i%m==0){
                sum+=i;
            }
        }
        d = t-sum;
        return d-sum;
    }
}
