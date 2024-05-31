import java.util.*;
class Main 
{
    public static int countingValley(int n, String path)
    {
        int level=0,valley=0;
        for(int i=0;i<n;i++)
        {
            if(path.charAt(i)=='U')
                level++;
            else if(path.charAt(i)=='D')
            {
                if(level==1)
                    valley++;
                level--;
            }
        }
        return valley;
    }
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        String str=sc.next();
        int result=countingValley(n,str);
        System.out.println(result);
    }
}
