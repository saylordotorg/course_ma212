---
layout: default
title: "MA212: Linear Algebra II"
course_description: "A review of linear algebra, building up to the study of row operations, the factorization of matrices, eigenvalues, eigenvectors, spectral theorem, and vector spaces."
next: ../Unit05
previous: ../Unit03
---
**Unit 4: Inner Product Spaces, Self-adjoint Operators and the Spectral
Theorem for Normal Maps** <span id="4"></span> 
*Linear algebra deals with not only Euclidean spaces but also abstract
vector spaces.  This unit will discuss lengths and angles in an abstract
vector space.*  *Inner products allow us to generalize notions such as
length, because an inner product is a generalization of a dot product
for Euclidean n-space.  Having notions of length, angles, and distances
in an abstract vector space allow us to apply more tools and methods
which help us to better understand the structure of the space.*  
  
 **In this unit, we will discuss inner product spaces, which are vector
spaces with an additional structure known as an inner product.  Much of
the motivation for the subject grew from the need to generalize some
geometric properties of two-dimensional and three-dimensional Euclidean
spaces to higher dimensional spaces.   In this unit, we will finally
begin to understand the geometric aspects of linear algebra, such as
representing rotations in the three-dimensional Euclidean space as
matrices.  From this we will understand how to generalize and represent
rotations in higher dimensional Euclidean spaces as matrices.  The
concepts in this unit, such as norm and inner product, provide structure
on spaces.  We will finally study the basic properties of inner product
spaces, orthonormal bases, and the Gram-Schmidt orthogonalization
procedure.  We will further study range-nullspace decomposition,
orthogonal decomposition, and singular-value decomposition of spaces.*  
    
 *Next, we will try to understand and answer the question of when a
linear operator on an inner product space is diagonalizable.  We will
study the notion of an adjoint of an operator as well as normal
operators and then discuss the spectral theorem, which characterizes the
linear operators for which an orthonormal basis consisting of
eigenvectors exists.  The spectral theory studied here is closely
related to that studied in Unit 2.  In fact, the eigenvalues and
eigenvectors for a matrix are the same as those for the linear
transformation determined by the matrix.  We will then learn about
finding the singular-value decomposition of an operator.  We will
conclude by exploring some advanced topics. **

**Unit 4 Time Advisory**  
This unit will take you approximately 31.5 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit  4.1: 15.5 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 4.1.1: 3 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 4.1.2: 3 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 4.1.3: 9.5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit  4.2: 16 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 4.2.1: 3 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 4.2.2: 3 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 4.2.3: 3 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 4.2.4: 7 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Define a normed vector space.
-   Find an orthonormal basis for a given inner product space.
-   Apply the Cauchy Schwarz inequality.
-   Compute the tensor product of two vectors.
-   State the Riesz representation theorem.
-   Find the volume of a parallelepiped determined by three given
    vectors.
-   State what it means for a nxn matrix to be diagonalizable.
-   Define and identify Hermitian operators.
-   Define and identify Hilbert spaces.
-   Prove the Cayley Hamilton theorem.
-   Define and compute the adjoint of an operator.
-   Define and identify normal operators.
-   State the spectral theorem.
-   Determine the singular-value decomposition of an operator.
-   Define the notion of length for abstract vectors in abstract vector
    spaces.
-   Define and identify orthogonal vectors.
-   Define and identify orthogonal and orthonormal subsets of R^n.
-   Use the Gram-Schmidt process.
-   Compute the range-nullspace decomposition given by a linear
    transformation.
-   Explain how the matrix for a linear operator changes if we change
    from one orthonormal basis to another. 

**4.1 Inner Product Spaces** <span id="4.1"></span> 
**4.1.1 General Theory** <span id="4.1.1"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 12: Inner Product Spaces”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 12: Inner Product
    Spaces”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 12.1 (pages 287–289) in its
    entirety. Note that the notion of an inner product space is a
    generalization of the situation with Euclidean spaces.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 9: Inner Product Spaces”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 9: Inner Product
    Spaces”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Sections 9.1–9.4. Note the parallels to
    the situation with Euclidean spaces.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: . These materials have been reproduced for
    educational and non-commercial purposes and can be viewed in their
    original format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

**4.1.2 The Gram-Schmidt Process** <span id="4.1.2"></span> 
-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 9: Inner Product Spaces”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 9: Inner Product
    Spaces”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Section 9.5. The Gram-Schmidt process can
    be used to turn any basis for an inner product space into an
    orthogonal basis.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 12: Inner Product Spaces”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 12: Inner Product
    Spaces”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 12.2 (pages 289–292) in its
    entirety. The Gram-Schmidt process can be used to turn any basis for
    an inner product space into an orthogonal basis.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

**4.1.3 Advanced Topics** <span id="4.1.3"></span> 
-   **Activity: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Exercises for Chapter 9”**

    Link: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Exercises for Chapter
    9”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please complete calculational exercises 1, 3, and 5
    and proof-writing exercises 1, 2, 5, and 6 (pages 133–135).   
        
     Completing this activity should take approximately 2.5 hours to
    complete.  
        
     Terms of Use:  These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 9: Inner Product Spaces”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 9: Inner Product
    Spaces”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Section 9.6 on pages 128–132. Work
    through the examples on your own, and compare your work with that in
    the text.  
      

    Studying this reading should take approximately 1 hour to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf). Any
    reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 12: Inner Product Spaces”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 12: Inner Product
    Spaces”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Sections 12.3–12.8 (pages 292–305) in
    their entirety.  If the proofs are difficult to understand, try
    working through them in the low dimensional setting first.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Activity: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 12: Inner Product Spaces”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 12: Inner Product
    Spaces”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)

    Instructions: Please work through problems 1–3, 9, 11, 14, 16, 21,
    and 22 in Section 12.7 (pages 299–302) and problems 1 and 3 in
    Section 12.9 (page 306). When you are done, check your solutions
    with the answers on pages 495 and 496.  
        
     This activity should take approximately 4.5 hours to complete.

    Terms of Use*An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

**4.2 Spectral Theorem** <span id="4.2"></span> 
**4.2.1 Self Adjoint Operators** <span id="4.2.1"></span> 
-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 11: The Spectral Theorem for Normal Linear
    Maps”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 11: The Spectral Theorem for Normal Linear
    Maps”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Sections 11.1 and 11.2. Work through the
    examples on your own, and compare your work with that in the text.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 13: Self Adjoint
    Operators”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 13: Self Adjoint
    Operators”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Sections 13.1 and 13.2 (pages 307–312) in
    their entirety. Note that Schur's Theorem reappears in this
    generalized setting.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

**4.2.2 Spectral Theorem** <span id="4.2.2"></span> 
-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 11: The Spectral Theorem for Normal Linear
    Maps”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 11: The Spectral Theorem for Normal Linear
    Maps”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Sections 11.3 and 11.4. The Spectral
    Theorem describes the relationship between normal operators and
    eigenvectors. Work through the examples on your own, and compare
    your work with that in the text.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf). Any
    reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 13: Self Adjoint
    Operators”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 13: Self Adjoint
    Operators”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 13.3 (pages 312–316) in its
    entirety. Here, you will learn about Hilbert spaces and their
    properties.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

**4.2.3 Positive and Negative Operators** <span id="4.2.3"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 13: Self Adjoint
    Operators”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 13: Self Adjoint
    Operators”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Sections 13.4 and 13.5 (pages 317–321) in
    their entirety. You will read about the possibility of taking
    fractional powers of certain linear operators.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 11: The Spectral Theorem for Normal Linear
    Maps”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 11: The Spectral Theorem for Normal Linear
    Maps”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Section 11.5. Work through the examples
    on your own, and compare your work with that in the text.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

**4.2.4 Decomposition and Applications** <span id="4.2.4"></span> 
-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 11: The Spectral Theorem for Normal Linear
    Maps”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 11: The Spectral Theorem for Normal Linear
    Maps”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Sections 11.6 and 11.7. The
    singular-value decomposition generalizes the notion of
    diagonalization.  
      

    Studying this reading should take approximately 1 hour to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Activity: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Exercises for Chapter 11”**

    Link: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Exercises for Chapter
    11”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please complete calculational exercises 1 and 6 and
    proof-writing exercises 3 and 4 (pages 158–160).  
        
     Completing this activity should take approximately 3 hours to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format here. Any reproduction or redistribution for commercial use
    is strictly prohibited.

-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 13: Self Adjoint
    Operators”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 13: Self Adjoint
    Operators”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Sections 13.6–13.11 (pages 322–334) in
    their entirety. Here, you will learn about the singular-value
    decomposition of a matrix, which has applications in statistics and
    image analysis.  
        
     Studying this reading should take approximately 1 hour to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Activity: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 2: Matrices and Linear
    Transformations”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 2: Matrices and Linear
    Transformations”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)

    Instructions: Please work through problems 13, 15, 16, and 19 in
    Section 13.12. When you are done, check your solutions with the
    answers on page 496.  
        
     This activity should take approximately 2 hours to complete.

    Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.


