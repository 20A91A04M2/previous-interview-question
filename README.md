package pack1;
import.java.util.*;
public class file1{
public static void main{string[]args}{
int n,e sum=0,o sum=0;
scanner obj=new scanner(system.in);
n=obj.nextint();
int a[]=new int [n];
int i,sum=0;
for(i=0;i<n;i++)
{
a[i]=obj.nextint();
}
for(int i=0;i<n;i++)
{
if(a[i]%2==0&&i%2==0)
e sum=e sum+a[i];
else if(a[i]%2==1&&i%2==1)
o sum=o sum+a[i];
}
system.out.println(e sum+""o sum)
}}
