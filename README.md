# Factprial-of-number
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner s = new Scanner(System.in);
        int n = s.nextInt();
        int prod  =1;
        for(int i =n;i>=1;i--)
        {
            prod=prod*i;
        }
        System.out.println(prod);
    }
}
