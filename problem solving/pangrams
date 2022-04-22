# HackerRank-solutions-
here i am uploading all solutions for hackerrank problems.
import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;
import java.util.HashMap;

class Result {

    /*
     * Complete the 'pangrams' function below.
     *
     * The function is expected to return a STRING.
     * The function accepts STRING s as parameter.
     */

    public static String pangrams(String s) {
    // Write your code here
    int n=s.length();
    String ss=s.toLowerCase();
    HashSet<Integer> h=new HashSet<>();
    for(int i=0;i<n;i++){
        if(ss.charAt(i)!=' '){
            int pt=(int) ss.charAt(i);
            h.add(pt);
            
        }
    }
    if(h.size()==26){
        return "pangram";
    }
    else{
        return "not pangram";
    }
    
    

    }

}

public class Solution {
    public static void main(String[] args) throws IOException {
        BufferedReader bufferedReader = new BufferedReader(new InputStreamReader(System.in));
        BufferedWriter bufferedWriter = new BufferedWriter(new FileWriter(System.getenv("OUTPUT_PATH")));

        String s = bufferedReader.readLine();

        String result = Result.pangrams(s);

        bufferedWriter.write(result);
        bufferedWriter.newLine();

        bufferedReader.close();
        bufferedWriter.close();
    }
}
