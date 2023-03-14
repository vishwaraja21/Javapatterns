# Javapatterns
# 1. write a java program for the following pattern:
~~~
*****
*****
*****
*****
*****
~~~
~~~
public class pattern1
{
 public static void main(String[] args)
 {
  int row=5;
  for(int i=0;i<row;i++)
  {
    for(int j=0;j<row;j++)
     {
       System.out.print(“*”);
     }
     System.out.println();
     }
   }
}
~~~

#Output:

![image](https://user-images.githubusercontent.com/102411421/224884421-4ee1e820-c415-4ac9-b1da-0bd0823f2128.png)


# 2. Write a java program for the following pattern:
~~~
*********
 *******
  *****
   ***
    *
~~~
~~~
public class pattern2
{
 public static void main(String[] args)
 {
  int rows = 5;
  int spaces = 0;
  for (int i = rows; i >= 1; i--)
  {
    for (int j = 1; j <= spaces; j++)
    {
      System.out.print(" ");
    }
    for (int j = 1; j <= i * 2 - 1; j++)
    {
      System.out.print("*");
    }
    System.out.println();
    spaces++;
    }
  }
}
~~~

#Output:

![image](https://user-images.githubusercontent.com/102411421/224884490-28156f92-0634-4055-838e-a747c092e29e.png)

# 3.write a java program for the following pattern:
~~~
*
**
***
****
*****
****
***
**
*
~~~
~~~
public class pattern3
{
  public static void main(String[] args)
  {
    int rows = 5;
    for (int i = 1; i <= rows; i++)
    {
      for (int j = 1; j <= i; j++)
      {
        System.out.print("*");
      }
      System.out.println();
    }
    for (int i = rows - 1; i >= 1; i--)
    {
      for (int j = 1; j <= i; j++)
      {
        System.out.print("*");
      }
      System.out.println();
      }
    }
}
~~~

#Output:

![image](https://user-images.githubusercontent.com/102411421/224884554-895d5c68-ac05-48ac-a0de-fcc9377501ef.png)
