---
layout: post
title: java pratice 01
tags: [frontpage, jekyll, blog]
image: '/images/posts/7.jpg'
---

pro1
package lecture20190818;
public class Pro1 {
public static void main(String[] args) {
String a = "100";
String b = "200";
int c = Integer.parseInt(a);
int d = Integer.parseInt(b);
System.out.println(c);
// TODO Auto-generated method stub
}
}
pro2
package lecture20190818;
public class Pro2 { 
public static void main(String[] args) {
int i;
for(i=2;i<100;i=i+2)
{
System.out.println(i);
}
// TODO Auto-generated method stub
}
}
pro3
package lecture20190818;
public class Pro3 {
public static void main(String[] args) {
int a = 65430;
System.out.println("만원:"+a/10000 +" 천원:"+(a/1000)%10+" 백원:"+(a/100)%10+" 십원:"+(a/10)%10);
// TODO Auto-generated method stub
}
}
pro4
package lecture20190818;
public class Pro4 {
public static void main(String[] args) {
int a;
a = 1500000 + 55000 - (1500000/10);
// TODO Auto-generated method stub
}
}
pro5
package lecture20190818;
public class Pro5 {
public static void main(String[] args) {
System.out.println("이름 : 이효리");
System.out.printf("부서 : 개발부\n");
System.out.print("직위 : 대리");
// TODO Auto-generated method stub
}
}
pro6
package lecture20190818;
public class Pro6 {
public static void main(String[] args) {
System.out.println("*\n**\n**\n**\n***");
// TODO Auto-generated method stub
}
}
pro7
package lecture20190818;
public class Pro7 {
public static void main(String[] args) {
System.out.println("이름 : 민들레\n합계점수 : 235점\n평균점수 78.3");
// TODO Auto-generated method stub
}
}
pro8
package lecture20190818;
import java.util.Scanner;
public class Pro8 {
private static Object scan;
public static void main(String[] args) {
int a, b;1
Scanner scan = new Scanner(System.in);
a = scan.nextInt();
b = scan.nextInt();
System.out.println((a*b)/2);
// TODO Auto-generated method stub
}
}
pro9
package lecture20190818;
import java.util.Scanner;
public class Pro9 {
public static void main(String[] args) {
Scanner scan = new Scanner(System.in);
int a;
a = scan.nextInt();
System.out.println((a+2000)*1.1);
// TODO Auto-generated method stub
}
}
pro10
package lecture20190818;
import java.util.Scanner;
public class Pro10 {
public static void main(String[] args) {
Scanner scan = new Scanner(System.in);
int a;
a = scan.nextInt();
System.out.println(a/100);
System.out.println((a/10)%10);
System.out.println(a%10);
// TODO Auto-generated method stub
}
}
pro11
package lecture20190818;
import java.util.Scanner;
public class Pro11 {
public static void main(String[] args) {
Scanner scan = new Scanner(System.in);
double a = scan.nextDouble();
double b = scan.nextDouble();
System.out.println(a/(b*b));
// TODO Auto-generated method stub
}
}
pro12
package lecture20190818;
import java.util.Scanner;
public class Pro12 {
public static void main(String[] args) {
Scanner scan = new Scanner(System.in);
int a = scan.nextInt();
if(a%4 == 0)
{
if(a%100 != 0 || a%400 == 0)
{
System.out.println("운년");
}
else
{
System.out.println("평년");
}
}
else
{
System.out.println("평년");
}
// TODO Auto-generated method stub
}
}
pro13
package lecture20190818;
import java.util.Random;
import java.util.Scanner;
public class Pro13 {
public static void main(String[] args) {
Scanner scan = new Scanner(System.in);
int a = (int)(Math.random()*100);
int b = 0;
while(a != b)
{
b = scan.nextInt();
if(a>b)
{
System.out.println("난수의 숫자가 더 큽니다");
}
if(a<b)
{
System.out.println("난수의 숫자가 더 작습니다");
}
}
System.out.println("숫자를 맞쳤습니다");
// TODO Auto-generated method stub
}
}