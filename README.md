# p1-12getter-setter
date 07/09/26
day 03
p1-12

Access modifiers, getters/setters, invariants, immutable object basics

access modifiers decide who can access a  class, variable , constructor , or method

1.private  : only inside the same class
2.public   : accessible from anywhere
3.protected : class + package +  subclass
4.default  : same package

example :

class student {
  int rno;             //default
  private String name; //private
  protected int age;   //protected
  public string contact; //public


2.getters/setters
if a variable is private how can we read it?

we use a getter.

example :
getter : value read 
s.getName();


setter : value set krvi otherwise value ne change krvi
s.setname("Sneha");

3.invariants
an invariant is a rule that must always remain true for an object.

that's best example 
age connot be negative age >= 0
balance connot be negative 0 <= percentage <=100

example
class student{
  private int age;
  public void setage(int age){
    if(age >=0){
       this.age = age;
   }
 }
public int getage(){
  return age;
 }
}


4.immmutable object
immutable means once an object is created, itself uts state connot be changed.
String        → IMMUTABLE ✅
StringBuilder → MUTABLE   ✅






