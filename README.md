Download Link: https://assignmentchef.com/product/solved-cse111-lab-5
<br>
<strong>Consider the following code: </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="575"><strong>class msgClass{ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public int content; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>} </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>public class FinalT5A{ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  private int sum = 2; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  private int y = 1; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public int x = 1; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public void methodA(){     </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int x=0, y =0, i = 0; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    while (i &lt; 2){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>      msgClass myMsg = new msgClass(); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>      myMsg.content = this.x; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>      this.y = this.y + methodB(myMsg, myMsg.content);      </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>      System.out.println(x + ” ” + y+ ” ” + sum);     </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>      y =  this.y / 2;    </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>      x = y + sum/2 – i;       </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>      sum = x + y + myMsg.content; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>      i++; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);  </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  private int methodB(msgClass mg2, int mg1){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int x = 0; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    y = y + mg2.content; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    mg2.content = y + mg1; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    x = this.x + 3 + mg1; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = sum + x + y;     </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    System.out.println(this.x + ” ” + this.y+ ” ” + sum);       </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    mg2.content = sum – mg1 ; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    return sum; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>}   </strong></td>

  </tr>

 </tbody>

</table>

What is the output of the following code sequence?

<table width="0">

 <tbody>

  <tr>

   <td rowspan="8" width="289"><strong>FinalT5A fT5A = new FinalT5A(); fT5A.methodA(); </strong></td>

   <td width="104"><strong>x </strong></td>

   <td width="93"><strong>y </strong></td>

   <td width="89"><strong>sum </strong></td>

  </tr>

  <tr>

   <td width="104"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="104"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="104"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="104"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="104"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="104"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="104"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

 </tbody>

</table>







<h1>Task 2</h1>




<table width="0">

 <tbody>

  <tr>

   <td width="575"><strong>public class FinalT6A{ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public static int temp = 3; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  private int sum; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  private int y = 2; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public FinalT6A(int x, int p){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    temp+=3; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    y = temp – p; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = temp + x; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public void methodA(){     </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int x=0, y =0; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    y = y + this.y;  </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    x = this.y + 2 + temp; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = x + y + methodB(temp, y); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public int methodB(int temp, int n){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int x = 0; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    y = y + (++temp); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    x = x + 2 +  n; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    return sum; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>} </strong></td>

  </tr>

 </tbody>

</table>

What is the output of the following code sequence?




<table width="0">

 <tbody>

  <tr>

   <td rowspan="8" width="300"><strong>FinalT6A q1 = new FinalT6A(2,1); q1.methodA(); q1.methodA();   </strong></td>

   <td width="93"><strong>x </strong></td>

   <td width="93"><strong>y </strong></td>

   <td width="89"><strong>sum </strong></td>

  </tr>

  <tr>

   <td width="93"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="93"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="93"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="93"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="93"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="93"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

  <tr>

   <td width="93"><strong> </strong></td>

   <td width="93"><strong> </strong></td>

   <td width="89"><strong> </strong></td>

  </tr>

 </tbody>

</table>










<strong> </strong>

<h1>Task 3</h1>

<strong>public class Quiz1{   public static int temp = 4;   public int sum;   public int y;   public Quiz1(){     y = temp – 1;     sum = temp + 1;     temp+=2;   } </strong>

<strong>  public Quiz1(int p){     y = temp + p ;     sum = p+ temp + 1;     temp-=1;   }   </strong>

<strong>  public void methodA(){         int x=0, y =0;     y = y + this.y;      x = this.y + 2 + temp;     sum = x + y + methodB(x, y); </strong>

<strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong>

<strong>  } </strong>

<strong>  public int methodB(int m, int n){     int x = 0;     y = y + m + (++temp);     x = x + 2 +  n;     sum = sum + x + y; </strong>

<strong>    System.out.println(x + ” ” + y+ ” ” + sum);       return sum; </strong>

<strong>  } } </strong>

<strong>Consider the following code: </strong>

<strong> </strong>

<table width="0">

 <tbody>

  <tr>

   <td rowspan="8" width="295"><strong>Quiz1 q1 = new Quiz1(); q1.methodA(); q1.methodA(); Quiz1.temp+= 2; </strong><strong>Quiz1 q2 = new Quiz1(2); q2.methodA(); q2.methodA();</strong></td>

   <td width="96"><strong>x </strong></td>

   <td width="84"><strong>y </strong></td>

   <td width="96"><strong>sum </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

  <tr>

   <td width="96"><strong> </strong></td>

   <td width="84"><strong> </strong></td>

   <td width="96"><strong> </strong></td>

  </tr>

 </tbody>

</table>







<h2>Task 4</h2>




<table width="0">

 <tbody>

  <tr>

   <td width="582"><strong>class A{ </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public static int temp = 4; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public int sum; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public int y; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public A(){ </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    y = temp – 2; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    sum = temp + 1; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    temp-=2; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public void methodA(int m, int n){ </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    int x = 0; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    y = y + m + (temp++); </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    x = x + 1 +  n; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>}    </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>class B{ </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public static int x; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public int y = 5; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public int temp = -5; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public int sum = 2; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public B(){ </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    y = temp + 3 ; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    sum = 3 + temp + 2; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    temp-=2; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  }   </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public B(B b){ </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    sum = b.sum; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    x = b.x; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    b.methodB(2,3); </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>   public void methodA(int m, int n){ </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    int x = 2; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    y = y + m + (temp++); </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    x = x + 5 +  n; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    System.out.println(x + ” ” + y+ ” ” + sum);   </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  public void methodB(int m, int n){     </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    int  y = 0; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    y = y + this.y;  </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    x = this.y + 2 + temp; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    methodA(x, y); </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    sum = x + y + sum; </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>    System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="582"><strong>} </strong></td>

  </tr>

 </tbody>

</table>




<strong>Consider the following code: </strong>

<table width="0">

 <tbody>

  <tr>

   <td rowspan="6" width="209"><strong>A        </strong><strong>a1 = new A(); </strong><strong>B        </strong><strong>b1 = new B(); B b2 = new B(b1); b1.methodA(1, 2); b2.methodB(3, 2); </strong></td>

   <td width="96"><strong>x </strong></td>

   <td width="84"><strong>y </strong></td>

   <td width="96"><strong>sum </strong></td>

  </tr>

  <tr>

   <td width="96"></td>

   <td width="84"></td>

   <td width="96"></td>

  </tr>

  <tr>

   <td width="96"></td>

   <td width="84"></td>

   <td width="96"></td>

  </tr>

  <tr>

   <td width="96"></td>

   <td width="84"></td>

   <td width="96"></td>

  </tr>

  <tr>

   <td width="96"></td>

   <td width="84"></td>

   <td width="96"></td>

  </tr>

  <tr>

   <td width="96"></td>

   <td width="84"></td>

   <td width="96"></td>

  </tr>

 </tbody>

</table>







<h2>Task 5</h2>




<table width="0">

 <tbody>

  <tr>

   <td width="575"><strong>class A{</strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public static int temp = 3; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public int sum; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public int y; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public int x; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public A(){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int temp = -3; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int sum = 7; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    y = temp – 5; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = temp + 2; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    temp-=2; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    this.x = sum + temp + y; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public A(int y, int temp){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    y = temp – 1+ x; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = temp + 2 -x; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    temp-=2; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public void methodA(int m, int [] n){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int x = 0; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    y = y + m + methodB(x,m)+(temp++)+y; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    x = this.x + 2 +  (++n[0]); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = sum + x + y; </strong></td>

  </tr>

 </tbody>

</table>




<table width="0">

 <tbody>

  <tr>

   <td width="575"><strong>    n[0] = sum + 2; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    System.out.println(n[0] + x + ” ” + y+ ” ” + sum + n[0]);   </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>   public int methodB(int m, int n){     </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int [] y = {0}; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    this.y = y[0] + this.y + m;  </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    x = this.y + 2 + temp – n; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = x + y[0] + this.sum; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    System.out.println(y[0]+ x + “this.temp” + y[0]+ ” ” +sum+ y[0]); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    return y[0]; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>} </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>class B{ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public int y=1; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public int temp=-3; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public int x = 1; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public static int sum = 2; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public B(){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    y = temp + 1 ; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    x = 3 + temp + x; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    temp-=2; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  }   </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public B(B b){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = b.sum + this.sum; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    x = b.x + x; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    b.methodB(3,5); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public void methodA(int m, int [] n){ </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int x = 0; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    y = y + m + (temp++); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    x = x + 2 +  (++n[0]); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    n[0] = sum + 2; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    System.out.println(temp + x + ” ” + y+ ” ” + sum + temp);   </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  public void methodB(int m, int n){     </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int [] y = {0}; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    this.y = y[0] + this.y + m;  </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    x = this.y + 2 + temp – n; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    methodA(x, y); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    sum = x + y[0] + this.sum; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    System.out.println(n + x + ” ” + y[0]+ ” ” + sum + n); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>  } </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>} </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>Consider the following code:  </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    int x[] = {35}; </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    A a1 = new A(); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    A a2 = new A(-5,-7); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    B b1 = new B(); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    B b2 = new B(b1); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    a1.methodA(1, x); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    b2.methodB(3, 2); </strong></td>

  </tr>

  <tr>

   <td width="575"><strong>    a2.methodA(1, x); </strong></td>

  </tr>

 </tbody>

</table>




<h1>Task 6</h1>







<table width="0">

 <tbody>

  <tr>

   <td width="630"><strong>class msgClass{ </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     public int content; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>} </strong></td>

  </tr>

  <tr>

   <td width="630"><strong> </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>public class Quiz3{ </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     private int sum; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     private int y; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     public static int x; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     public Quiz3(){ </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          sum = 5; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          x = 2; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          y = 2; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     }   </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     public Quiz3(int k){ </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          sum = sum + k; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          y = 3; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          x += 2; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     }      </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     public void methodA(){ </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          int x=1, y=1; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          msgClass [] msg = new msgClass[1]; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          msgClass myMsg = new msgClass(); </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          myMsg.content = Quiz3.x; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          msg[0] = myMsg; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          msg[0].content = this.y + myMsg.content; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          this.y = this.y + methodB(msg[0]); </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          y = methodB(msg[0]) + this.y; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          x = y + methodB(msg, msg[0]); </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          sum = x + y + msg[0].content; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     } </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     private int methodB(msgClass [] mg2, msgClass mg1){ </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          int x = 2; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          y = y + mg2[0].content; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          mg2[0].content = y + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          x = x + 2 + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          mg1.content = sum – mg2[0].content ; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          System.out.println(Quiz3.x + ” ” + this.y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          return sum; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     } </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     public int methodB(msgClass mg1){ </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          int x = 1, y = 2; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          y = sum + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          this.y = y + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          x = Quiz3.x + 5 + mg1.content; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          sum = sum + x + y; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          Quiz3.x = mg1.content + x + 3; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          System.out.println(x + ” ” + y+ ” ” + sum); </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>          return y; </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>     } </strong></td>

  </tr>

  <tr>

   <td width="630"><strong>} </strong></td>

  </tr>

 </tbody>

</table>




<strong>Consider the following code: </strong>

<strong> </strong>

<table width="0">

 <tbody>

  <tr>

   <td rowspan="7" width="306"><strong>Quiz3 a1 = new Quiz3(); Quiz3 a2 = new Quiz3(5); msgClass msg = new msgClass(); a1.methodA(); a2.methodB(msg); </strong></td>

   <td width="101"><strong>x </strong></td>

   <td width="95"><strong>y </strong></td>

   <td width="125"><strong>sum </strong></td>

  </tr>

  <tr>

   <td width="101"><strong> </strong></td>

   <td width="95"><strong> </strong></td>

   <td width="125"><strong> </strong></td>

  </tr>

  <tr>

   <td width="101"><strong> </strong></td>

   <td width="95"><strong> </strong></td>

   <td width="125"><strong> </strong></td>

  </tr>

  <tr>

   <td width="101"><strong> </strong></td>

   <td width="95"><strong> </strong></td>

   <td width="125"><strong> </strong></td>

  </tr>

  <tr>

   <td width="101"><strong> </strong></td>

   <td width="95"><strong> </strong></td>

   <td width="125"><strong> </strong></td>

  </tr>

  <tr>

   <td width="101"><strong> </strong></td>

   <td width="95"><strong> </strong></td>

   <td width="125"><strong> </strong></td>

  </tr>

  <tr>

   <td width="101"><strong> </strong></td>

   <td width="95"><strong> </strong></td>

   <td width="125"><strong> </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>







<h1>Task 7</h1>




<strong>Study the following output </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="375"><strong>Code </strong></td>

   <td width="197"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="375"><strong>public class StudentTest{ </strong><strong>  public static void main(String [] args){ </strong><strong>    Student s1 = new Student(); </strong><strong>    System.out.println(s1.getName());  </strong><strong>    Student s2 = new Student(“Matin”); </strong><strong>    System.out.println(s2.getName()); </strong><strong> </strong><strong>    Student s3 = new Student(“Saad”); </strong><strong>    System.out.println(s3.getName()); </strong><strong>    </strong><strong>System.out.println(Student.numberOfStudents); </strong><strong>  } </strong><strong>}</strong></td>

   <td width="197"><strong>default name </strong><strong>Matin </strong><strong>Saad </strong><strong>3</strong></td>

  </tr>

 </tbody>

</table>







Write the code for the Student class so that the StudentTest class generates the output shown above.

<h2>Task 8</h2>




<strong>Output:  </strong>

<strong> </strong>

<strong>======================== </strong>

<strong>Name: Saad Abdullah </strong>

<strong>Department: CSE </strong>

<strong>List of courses </strong>

<strong>======================== </strong>

<strong>CSE 110 Programming Language I </strong>

<strong>CSE 111 Programming Language-II </strong>

<strong>======================== </strong>

<strong>======================== </strong>

<strong>Name: Mumit Khan </strong>

<strong>Department: CSE </strong>

<strong>List of courses </strong>

<strong>======================== </strong>

<strong>CSE 220 Data Structures </strong>

<strong>CSE 221 Algorithms </strong>

<strong>CCSE 230 Discrete Mathematics </strong>

<strong>======================== </strong>

<strong>======================== </strong>

<strong>Name: Sadia Kazi </strong>

<strong>Department: CSE </strong>

<strong>List of courses </strong>

<strong>======================== </strong>

<strong>CSE 310 Object Oriented Programming </strong>

<strong>CSE 320 Data Communications </strong>

<strong>CSE 340 Computer Architecture </strong>

<strong>======================== </strong>

<strong> </strong>

<strong><u>Tester:</u></strong>




public class TestTeacher{

public static void main(String [] args){

Teacher t1 = new Teacher(“Saad Abdullah”, “CSE”);

Teacher t2 = new Teacher(“Mumit Khan”, “CSE”);

Teacher t3 = new Teacher(“Sadia Kazi”, “CSE”);

Course c1 = new Course(“CSE 110 Programming Language I”);                       Course c2 = new Course(“CSE 111 Programming Language-II”);                      Course c3 = new Course(“CSE 220 Data Structures”);                              Course c4 = new Course(“CSE 221 Algorithms”);

Course c5 = new Course(“CCSE 230 Discrete Mathematics”);

Course c6 = new Course(“CSE 310 Object Oriented

Programming”);

Course c7 = new Course(“CSE 320 Data Communications”);

Course c8 = new Course(“CSE 340 Computer Architecture”);       t1.addCourse(c1);     t1.addCourse(c2);     t2.addCourse(c3);     t2.addCourse(c4);     t2.addCourse(c5);     t3.addCourse(c6);     t3.addCourse(c7);     t3.addCourse(c8);     t1.printDetail();     t2.printDetail();     t3.printDetail();

} }




Write the Teacher and Course classes so that the TestTeacher class produces the outputs given above







<h2>Task 9</h2>

<strong> </strong>

Consider the following code:

<strong>public class AccountTester </strong>

<strong>{ </strong>

<strong>  public static void main(String[] args) </strong>

<strong>  { </strong>

<strong>    System.out.println(Account.interestRate); </strong>

<strong>    Account a1 = new Account(); </strong>

<strong>    System.out.println(a1.nameKi()); </strong>

<strong>    System.out.println(a1.balanceKi()); </strong>

<strong>    a1.nameBoshao(“Mashrafe Murtaza”);     a1.balanceBoshao(5000);     System.out.println(a1.nameKi()); </strong>

<strong>    System.out.println(a1.balanceKi()); </strong>

<strong>    Account a2 = new Account(“Mustafizur Rahman”,50); </strong>

<strong>    System.out.println(a2.nameKi());     System.out.println(a2.balanceKi());     a1.withdraw(4900);     a2.withdraw(25);     a1.withdraw(4899); </strong>

<strong>  } </strong>

<strong>} </strong>

<strong> </strong>

<strong> </strong>

<strong>Write the account class given that the output for the above code is :  </strong>

<strong> </strong>

<strong>5.0 </strong>

<strong>Default Account </strong>

<strong>0.0 </strong>

<strong>Mashrafe Murtaza </strong>

<strong>5000.0 </strong>

<strong>Mustafizur Rahman </strong>

<strong>50.0 </strong>

<strong>The account balance after deducting withdraw amount is equal to or less than minimum. Cannot withdraw The account balance after deducting withdraw amount is equal to or less than minimum. Cannot withdraw </strong>

<strong>Withdraw successful! New balance is: 101.0 </strong>

<strong> </strong>

Task 10




Complete the <strong>Student </strong>class so that the <strong>main </strong>method prints the following:

<strong>Name of the Student: Bob </strong>

<strong>ID of the Student: 1 </strong>

<strong>Name of the Student: Tom </strong>

<strong>ID of the Student: 2 </strong>

<strong>Name of the Student: Jack </strong>

<strong>ID of the Student: 3 </strong>

<strong>Name of the Student: Jill ID of the Student: 4 public class Student{ </strong>

<h2>//Your code here</h2>

<strong>} </strong>

<strong>public class Printer{ </strong>

<strong>public void printDetail(Student s){ </strong>

<strong>System.out.println(“Name of the Student: “+s.name); </strong>

<strong>System.out.println(“ID of the Student: “+s.id); </strong>

<strong>} </strong>

<strong>} </strong>

<strong>public class Test{ </strong>

<strong>public static void main(String [] args){ Student s1 = new Student(“Bob”, 1); </strong>

<strong>Student s2 = new Student(“Tom”, 2); </strong>

<strong>Student s3 = new Student(“Jack”, 3); </strong>

<strong>Student s4 = new Student(“Jill”, 4); Printer pr = new Printer(); pr.printDetail(s1); pr.printDetail(s2); pr.printDetail(s3); pr.printDetail(s4); </strong>

<strong>} </strong>

<strong>} </strong>

<strong> </strong>

<strong>Task 11 </strong>

<strong> </strong>

<strong>Task 1 </strong> <strong>public class Dog { </strong>

<strong>private String color = “Black”; </strong>

<strong>//your code here </strong>

<strong>} </strong>

<strong>public class Quiz { </strong>

<strong>public static void main (String[] args){ </strong>

<strong>Dog odie = new Dog(“Red”); </strong> <strong>Dog goofy = new Dog(“Blue”); </strong> <strong>odie.bark(); </strong> <strong>goofy.bark(); </strong> <strong>odie.changeColor(“Brown”); </strong> <strong>odie.bark(); </strong>

<strong>} </strong>

<strong>} </strong>

<strong>//Complete the Dog class so the main method above produces the following output: </strong>

<strong>Red dog is barking </strong>

<strong>Blue dog is barking </strong>

<strong>Brown dog is barking </strong>

<strong> </strong>

<h2>Task 12</h2>

<strong> </strong>




Page 1 of 1 SET-A




<strong>public class Cat{ </strong>

public String color = “White”;  public String action = “sitting”;  //your code here

<strong>} </strong>

<strong>public class Test{ </strong>

public static void main(String [] args){  Cat c1 = new Cat();

Cat c2 = new Cat(“Black”);

Cat c3 = new Cat(“Brown”, “jumping”);  Cat c4 = new Cat(“Red”, “purring”);

c1.printCat();  c2.printCat();  c3.printCat();  c4.printCat();  c1.changeColor(“Blue”);  c3.changeColor(“Purple”);  c1.printCat();  c3.printCat();  }

<strong>} </strong>

<strong><u>Output</u></strong>:

White cat is sitting Black cat is sitting jumping cat is Brown purring cat is Red Blue cat is sitting

Purple cat is Brown


