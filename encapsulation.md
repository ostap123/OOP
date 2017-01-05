//encapsulation


//File name: Human.java

public class Human{
  private String name;
  private String surname;
  private int age;

public String getName(){
  return name; 
}
public String getSurname(){
  return surname;
}
public int getAge(){
  return age;
}
public void setName(String name){
 this.name=name;
}
public void setSurname(String surname){
 this.surname=surname;
}
public void setAge(int age){
 this.age.=age;
}
}

//File name: Access.java

public class Access{
  public static void main(String [] args){
  Human human=new Human();
  human.setName("Ostap  ");
  human.setSurname("Shevchenko  ");
  human.setAge(21);
  
  System.out.println("Dear,  "+human.getName()+human.getSurname()"your age is  "+ human.getAge+", you can buy this product" )
}
