import java.util.*;

/*Please dont change class name, Dcoder 
and class must not be public*/

//Compiler version JDK 1.8

class Dcoder
{   
    public static void main(String args[])
    {   
        Scanner scn = new Scanner(System.in);
        int n = scn.nextInt();
        int k = scn.nextInt();
        boolean a[] = new boolean[n];
        for(int i = 0; i < n ; i++)
        {
            a[i] = false;
        }
        for(int i = 0; i < k ; i++)
        {
            if(a[Integer.parseInt((scn.next()).substring(6))] == true)
                a[Integer.parseInt((scn.next()).substring(6))] = false;
            else
                a[Integer.parseInt((scn.next()).substring(6))] = true;
        }
    }
}
