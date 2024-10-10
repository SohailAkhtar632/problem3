# problem3
class Solution {
  public:
    // Function to return sum of elements
    int sum(vector<int>& arr) {
        // code here
        int sum=0;
        for(int i=0;i<=arr.size()-1;i++){
            sum +=arr[i];
        }
        return sum;
    }
};
