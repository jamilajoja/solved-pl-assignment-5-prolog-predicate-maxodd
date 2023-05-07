Download Link: https://assignmentchef.com/product/solved-pl-assignment-5-prolog-predicate-maxodd
<br>
<strong>Assignment 5 </strong>

<ol>

 <li> Write a Prolog predicate <strong>maxodd(L,Res)</strong> that computes the maximum integer that appears in the odd position of an integer list L and stores the result in Res. Assume that L contains at least 1 element. E.g. |?-maxodd([1,5,3,4,2], Res).</li>

</ol>

Res = 3  //3 is the maximum number that appears in the odd position of the list [1,5,3,4,2]

<ol start="2">

 <li> Define a Prolog predicate<strong> deleteNList(N,L,Res) </strong>that delete <strong>every Nth</strong> argument of a list : and store the results in Res.</li>

</ol>

E.g. | ?- deleteNList(3, [2,3,4,5,6,7,8], Res).

Res = [2,3,5,6,8].

no

<ol start="3">

 <li><strong> </strong>Write a Prolog predicate <strong>replace_first(L, X, Y, Res)</strong> that replaces the first occurrences of X in a list L with Y and stores the result in Res. IF L does not contain X, then return L. e.g. | ?- replace_first([2,1,3,1,4,1,5,1,6,1], 1, 6, Res).        Res = [2,6,3,1,4,1,5,1,6,1].</li>

</ol>

<ol start="4">

 <li>Write a Prolog program<strong> position(X, L, Res) </strong>that takes an integer X and an integer list L, returns a list of positions of X in L. The result is stored in Res. e.g. |?- position(1, [1,3,1,2,5,1], Res).</li>

</ol>

Res = [1,3,6].

No

<ol start="5">

 <li><strong> </strong>Given the following code in Java</li>

</ol>

public class A

{ public void p() { System.out.println(“A.p”);}    public void q() { System.out.println(“A.q”);}

public void r() { p(); q();}

}

class B extends A

{ public void p() { System.out.println(“B.p”);}

}

class C extends B

{ public void q() { System.out.println(“C.q”);}

public void r() { q(); p();}

}

…

A a = new B();

a.r();

a = new C();

a.r();

What does the above program print?




<ol start="6">

 <li><strong> [12 points]</strong> Question 10.20 Given the following code in C++:</li>

</ol>

<h1>class A{ public:</h1>

virtual void p(){cout &lt;&lt; “A.p”&lt;&lt; endl;}          void q(){cout &lt;&lt; “A.q” &lt;&lt; endl;}              virtual void r(){p(); q();}

<h1>};</h1>

class B: public A{   public:

void p(){cout &lt;&lt; “B.p” &lt;&lt; endl;}

}; class C: public B{   public:

void q(){cout &lt;&lt; “C.q” &lt;&lt; endl;}

void r(){q(); p();}

};

…

A a; C c; a = c; a.r();

A* ap = new B; ap -&gt; r();

A* ap1 = new C; ap1 -&gt; r();




What does the above program print?




<ol start="7">

 <li><strong> [16 points]</strong> Question 10.48 Class A</li>

</ol>

{ public:

virtual void f();

virtual void g();

private: int a;

}; class B: public A { public:

void f();

void h();

private: int b;

}

Class C: public B

<h1>{ public: void g();</h1>

Private: int c; }

Draw the VMT of each class and the layout of memory for a dynamically-allocated object of each class.


