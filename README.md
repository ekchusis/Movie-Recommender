# Movie-Recommender

**Cosine Similarity/Correlation**

- Cosine Similarity is basically 'cosine of the angle between any two vectors'
- Vector A = [a1  a2  a3....an] and Vector B = [b1  b2  b3...bn]
- We can visualise the above vector as a straight line in two-dimensional space

**Let's understand with the help of a simple example**
```
A = [4  3] and B = [3  4]

if one remembers the basics of linear algebra...then it's like (vectors i and j)

for two dimensions i.e. x-y plane

cos(T) = A.B / |A||B|

 - where (A.B) is dot product of two vectors
 - |A|, |B| are the magnitude of A & B
 
cos(T) = (4*3 + 3*4) / 5*5

cos(T) = 0.96  

```
**Another example with somewhat more dimensions**

```
A = [4  2  0  0  1  0  0  1], B = [0  2  0  0  1  1  0  0]

cos(T) = A.B / |A||B|

cos(T) = (4*0 + 2*2 + 0*0 + 0*0 + 1*1 + 0*1 + 0*0 + 1*0) / sqrt(21) * sqrt(6)

cos(T) = 0.45
```

**Real Example**

