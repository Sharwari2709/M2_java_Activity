# Problem

![image](https://user-images.githubusercontent.com/83021508/156704151-1b52298e-d801-41b3-a682-0c520a84dd5c.png)

#  code

import java.util.*;
import java.io.*;
import java.util.Scanner;
class program
{
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        String p=sc.next();
        String r=sc.next();
        int len_x=p.length();
        int len_y=r.length();
        System.out.println(((" "+ p.substring(0,1)).toUpperCase()+(p.substring(1,len_x).toLowerCase()))+" "+ ((r.toUpperCase())));
    }

}

# output

![image](https://user-images.githubusercontent.com/83021508/156968835-543c7570-953d-454e-bc00-723ad899c8be.png)



