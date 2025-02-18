# Java-String-Program-to-Print-Even-Length-Words

class Main {
    public static void main(String[] args) {
      String a="once upon a time";
       for(int i=0;i<a.length();i++)
       {
           if(i%2==0)
           System.out.println(a.charAt(i));
       }
}
}
