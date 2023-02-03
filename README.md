# JyothiYerraguntla_HW2

NLP HW-2
Jyothi Yerraguntla-11547245

Run: Run Jupyter notebook named Hw_2.ipynb file.

Input: "Baker Betty Lou bought some butter. But, it made her batter bitter. So, Baker Betty Lou bought some better butter to make her bitter batter better."

After ‘k’ iterations: Here k= 9

Output:

Initial Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y

Iteration 1:

Merge ‘e’ ,’r’ to ‘er’
Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y,er
after merging corpus is: {'B a k er </w>': 2, 
'B e t t y </w>': 2, 
'L o u </w>': 2, 
'b o u g h t </w>': 2, 
's o m e </w>': 2, 
'b u t t er . </w>': 1,
'B u t , </w>': 1,
'i t </w>': 1, 
'm a d e </w>': 1,
'h er </w>': 2,
'b a t t er </w>': 2, 
'b i t t er . </w>': 1,
'S o , </w>': 1, 
'b e t t er </w>': 1,
'b u t t er </w>': 1, 
't o </w>': 1, 
'm a k e </w>': 1, 
'b i t t er </w>': 1, 
'b e t t er . </w>': 1}

Iteration 2:

Merge ‘t’,’t’ to ’tt’
Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y,er,tt
after merging corpus is: {'B a k er</w>': 2, 
'B e tt y </w>': 2, 
'L o u </w>': 2, 
'b o u g h t </w>': 2, 
's o m e </w>': 2, 
'b u tt er . </w>': 1, 
'B u t , </w>': 1, 
'i t </w>': 1, 
'm a d e </w>': 1, 
'h er</w>': 2, 
'b a tt er</w>': 2, 
'b i tt er . </w>': 1, 
'S o , </w>': 1, 
'b e tt er</w>': 1, 
'b u tt er</w>': 1, 
't o </w>': 1, 
'm a k e </w>': 1, 
'b i tt er</w>': 1, 
'b e tt er . </w>': 1}

Iteration3:

Merge ‘er’,’</w>’ to ‘er</w>’
Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y,er,tt,er</w>
after merging corpus is: 
{'B a k er</w>': 2, 
'B e tt y </w>': 2, 
'L o u </w>': 2, 
'b o u g h t </w>': 2, 
's o m e </w>': 2, 
'b u tt er . </w>': 1, 
'B u t , </w>': 1, 
'i t </w>': 1, 
'm a d e </w>': 1, 
'h er</w>': 2, 
'b a tt er</w>': 2, 
'b i tt er . </w>': 1, 
'S o , </w>': 1, 
'b e tt er</w>': 1, 
'b u tt er</w>': 1, 
't o </w>': 1, 
'm a k e </w>': 1, 
'b i tt er</w>': 1, 
'b e tt er . </w>': 1}

Iteration 4:

Merge ‘tt’,’er</w>’ to ‘tter</w>’
Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y,er,tt,er</w>,tter</w>
after merging corpus is: {'B a k er</w>': 2, 
'B e tt y </w>': 2, 
'L o u </w>': 2, 
'b o u g h t </w>': 2, 
's o m e </w>': 2, 
'b u tt er . </w>': 1, 
'B u t , </w>': 1, 
'i t </w>': 1, 
'm a d e </w>': 1, 
'h er</w>': 2, 
'b a tter</w>': 2, 
'b i tt er . </w>': 1, 
'S o , </w>': 1, 
'b e tter</w>': 1, 
'b u tter</w>': 1, 
't o </w>': 1, 
'm a k e </w>': 1, 
'b i tter</w>': 1, 
'b e tt er . </w>': 1}

Iteration 5:

Merge ‘o’,’u’ to ‘ou’:
Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y,er,tt,er</w>,tter</w>,ou
after merging corpus is: {'B a k er</w>': 2, 
'B e tt y </w>': 2, 
'L ou </w>': 2, 
'b ou g h t </w>': 2, 
's o m e </w>': 2, 
'b u tt er . </w>': 1, 
'B u t , </w>': 1, 
'i t </w>': 1, 
'm a d e </w>': 1, 
'h er</w>': 2, 
'b a tter</w>': 2, 
'b i tt er . </w>': 1, 
'S o , </w>': 1, 
'b e tter</w>': 1, 
'b u tter</w>': 1, 
't o </w>': 1, 
'm a k e </w>': 1, '
b i tter</w>': 1, 
'b e tt er . </w>': 1}


Iteration 6:

Merge ‘e’,’</w>’ to ‘e</w>’
Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y,er,tt,er</w>,tter</w>,ou,e</w>
after merging corpus is: {'B a k er</w>': 2, 
'B e tt y </w>': 2, 
'L ou </w>': 2, 
'b ou g h t </w>': 2, 
's o m e</w>': 2, 
'b u tt er . </w>': 1, 
'B u t , </w>': 1, 
'i t </w>': 1, 
'm a d e</w>': 1, 
'h er</w>': 2, 
'b a tter</w>': 2, 
'b i tt er . </w>': 1, 
'S o , </w>': 1, 
'b e tter</w>': 1, 
'b u tter</w>': 1, 
't o </w>': 1, 
'm a k e</w>': 1, 
'b i tter</w>': 1, 
'b e tt er . </w>': 1}


Iteration 7:

Merge ‘a’,’k’ to ‘ak’
Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y,er,tt,er</w>,tter</w>,ou,e</w>,ak
after merging corpus is: {'B ak er</w>': 2, 
'B e tt y </w>': 2, 
'L ou </w>': 2, 
'b ou g h t </w>': 2, 
's o m e</w>': 2, 
'b u tt er . </w>': 1, 
'B u t , </w>': 1, 
'i t </w>': 1, 
'm a d e</w>': 1, 
'h er</w>': 2, 
'b a tter</w>': 2, 
'b i tt er . </w>': 1, 
'S o , </w>': 1, 
'b e tter</w>': 1, 
'b u tter</w>': 1, 
't o </w>': 1, 
'm ak e</w>': 1, 
'b i tter</w>': 1, 
'b e tt er . </w>': 1}


Iteration 8:

Merge ‘e’, ‘tt’ to ‘ett’
Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y,er,tt,er</w>,tter</w>,ou,e</w>,ak,ett
after merging corpus is: {'B ak er</w>': 2, 
'B ett y </w>': 2, 
'L ou </w>': 2, 
'b ou g h t </w>': 2, 
's o m e</w>': 2, 
'b u tt er . </w>': 1, 
'B u t , </w>': 1, 
'i t </w>': 1, 
'm a d e</w>': 1, 
'h er</w>': 2, 
'b a tter</w>': 2, 
'b i tt er . </w>': 1, 
'S o , </w>': 1, 
'b e tter</w>': 1, 
'b u tter</w>': 1, 
't o </w>': 1, 
'm ak e</w>': 1, 
'b i tter</w>': 1, 
'b ett er . </w>': 1}


Iteration 9:

Merge ‘t’, ‘</w>’ to ‘t</w>’
Vocabulary: </w>,a,b,B,d,e,g,h,i,k,L,m,o,r,S,s,t,u,y,er,tt,er</w>,tter</w>,ou,e</w>,ak,ett,t</w>
after merging corpus is: {'B ak er</w>': 2, 
'B ett y </w>': 2, 
'L ou </w>': 2, 
'b ou g h t</w>': 2, 
's o m e</w>': 2, 
'b u tt er . </w>': 1, 
'B u t , </w>': 1, 
'i t</w>': 1, 
'm a d e</w>': 1, 
'h er</w>': 2, 
'b a tter</w>': 2, 
'b i tt er . </w>': 1, 
'S o , </w>': 1, 
'b e tter</w>': 1, 
'b u tter</w>': 1, 
't o </w>': 1, 
'm ak e</w>': 1, 
'b i tter</w>': 1, 
'b ett er . </w>': 1}


