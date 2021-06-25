class Solution {
public:
    vector<int> plusOne(vector<int>& digits) {
        vector<int> res;
        short int c=1;
        for(int i=digits.size()-1; i>=0;i--){
            c+=digits[i];
            if(c>9) {
                res.insert(res.begin(),0);
                c=1;
            }
            else{
                res.insert(res.begin(),c);
                c=0;
            }
        }
        if(c) res.insert(res.begin(),c);
        return res;
    }
};

class Solution {
public:
    vector<int> plusOne(vector<int>& digits) {
         for(int i=digits.size()-1;i>=0;i--)
         {
            if(digits[i]!=9)
            {
                digits[i]++;
                break;
            }
            else if(digits[i]==9 && i!=0)
            {
                digits[i]=0;
            }
            else
            {
                digits[i]=0;
                digits.insert(digits.begin(),1);
            }
        }
        return digits;
    }
};
