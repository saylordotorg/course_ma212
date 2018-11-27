**Unit 2: Spectral Theory** <span id="2"></span> 
*In this unit, you will study Spectral Theory, which refers to the study
of eigenvalues and eigenvectors of a matrix.  The name Spectral Theory
is due to David Hilbert, who coined the phrase in his study of Hilbert
space theory. Hilbert's original work was in the setting of quadratic
forms, and only later was it discovered that Spectral Theory had
applications to quantum mechanics, where it could be used to describe
the behavior of atomic spectra. Eigenvalues and eigenvectors of a linear
operator are two of the most important concepts in Linear Algebra with
applications to many fields, such as computer science (Google's PageRank
algorithm), physics (quantum mechanics, vibration analysis), and
economics (equilibrium states of Markov models).  You will then learn
about trace and determinants, two important numbers associated to a
matrix.  There are several operations that can be applied to a square
matrix, and the determinant is a very important operation of this
type. The determinant is a number that is calculated from a square
matrix and is used to check for many different properties of that
matrix, including invertibility.  We will learn to compute the
determinant and study properties of determinants and the effects of row
operations on them.  The trace of a matrix is related to the
characteristic polynomial of the matrix and can be used to detect
nilpotency. You will then learn about Schur's Theorem, which describes
how every matrix is related to an upper triangular matrix.  Finally, you
will learn about quadratic forms, the second derivative test, and some
advanced theorems. *

**Unit 2 Time Advisory**  
This unit will take you approximately 18 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit 2.1: 8.5 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 2.1.1: 2.5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 2.1.2: 6 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit  2.2: 2 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit  2.3: 3.5 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit  2.4: 4 hours  
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Reading: 1 hour

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Activity: 3 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Define and compute eigenvectors and eigenvalues.
-   Define and compute invariant subspaces.
-   Define and compute an eigenspace of a linear operator.
-   Prove properties of invariant subspaces.
-   State Schur's Theorem.
-   Define and identify normal matrices.
-   Explain the composition and the inversion of permutations.
-   Define and compute the determinant.
-   Explain when eigenvalues exist for a given operator.
-   Determine the normal form of a nilpotent operator.
-   Explain the idea of Jordan blocks, Jordan matrices, and the Jordan
    form of a matrix.
-   Define quadratic forms.
-   State the second derivative test.

**2.1 Eigenvalues, Eigenvectors, and Applications** <span
id="2.1"></span> 
**2.1.1 Eigenvalues and Eigenvectors** <span id="2.1.1"></span> 
-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 7: Eigenvalues and Eigenvectors”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: “[Chapter 7: Eigenvalues and
    Eigenvectors”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Sections 7.1–7.5. The eigenvectors and
    eigenvalues of a matrix help to describe the behavior of the
    associated linear transformation.  
      
     Studying this reading should take approximately 1.5 hours to
    complete.  
      
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
     Any reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 7: Spectral Theory”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 7: Spectral
    Theory”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 7.1 (pages 157–164) in its
    entirety. Work through the eigenvalue/eigenvector examples on your
    own and check your work with that in the text. Being able to
    accurately and efficiently perform these computations is
    essential.  
      
     Studying this reading should take approximately 1 hour to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

**2.1.2 Eigenvalues and Eigenvectors** <span id="2.1.2"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 7: Spectral Theory”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 7: Spectral
    Theory”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 7.2 (pages 164–167) in its
    entirety.  Here, you will learn about applications of eigenvalues
    and eigenvectors.  
      
     Studying this reading should take approximately 45 minutes to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Activity: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 7: Spectral Theory”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 7: Spectral
    Theory”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF) 

    Instructions: Please work through the odd-numbered problems for
    19–33 in Section 7.3 on pages 168–170. When you are done, check your
    solutions with the answers on page 492.  
        
     Completing this activity should take approximately 2.5 hours to
    complete.

    Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 7: Eigenvalues and Eigenvectors”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 7: Eigenvalues and
    Eigenvectors”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Section 7.6. Note the relationship
    between the eigenvectors for a rotation matrix and the angle of
    rotation.  
      
     Studying this reading should take approximately 45 minutes to
    complete.  
      
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
     Any reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Activity: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Exercises for Chapter 7”**

    Link: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Exercises for Chapter
    7”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please complete calculational exercises 3 and 7 and
    proof-writing exercises 10, 11, and 12 (pages 95, 96, and 98).   
      
     Completing this activity should take approximately 2 hours to
    complete.  
      
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
     Any reproduction or redistribution for commercial use is strictly
    prohibited.

**2.2 Schur’s Theorem** <span id="2.2"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 7: Spectral Theory”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 7: Spectral
    Theory”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 7.4 (pages 173–180) in its
    entirety. Schur's Theorem relates any matrix to an associated upper
    triangular matrix in which the eigenvalues for the original matrix
    appear on the diagonal. Read through the proof of this theorem and
    the accompanying lemmas and corollaries.  
      
     Studying this reading should take approximately 2 hours to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

**2.3 Trace and Determinant** <span id="2.3"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 7: Spectral Theory”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 7: Spectral
    Theory”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 7.5 (page 180) in its entirety. 
    Pay particular attention to the algebraic properties of the trace.  
      
     Studying this reading should take approximately 30 minutes to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 8: Permutations and the Determinant of a
    Square Matrix”**

    Link: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 8: Permutations and the Determinant of a
    Square
    Matrix”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Chapter 8 in its entirety. Pay particular
    attention to the algebraic properties of the determinant.  
      
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
    Mathematics: “Exercises for Chapter 8”**

    Link: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Exercises for Chapter
    8”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please complete calculational exercises 1, 4, and 5
    and the proof-writing exercises 1, 2, and 3 (pages 115 and 116).   
      
     This activity should take approximately 2 hours complete.  
      
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
     Any reproduction or redistribution for commercial use is strictly
    prohibited.

**2.4 Quadratic Forms, Second Derivative Test, and Advanced Theorems**
<span id="2.4"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 7: Spectral Theory”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 7: Spectral
    Theory”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Sections 7.6–7.9 (pages 181–190) in their
    entirety. Note how the matrix algebra you have been studying is
    applied to prove a familiar theorem from multivariable calculus.  
        
     Studying this reading should take approximately 1 hour to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Activity: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 7: Spectral Theory”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 7: Spectral
    Theory”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)

       
     Instructions: Please work through problems 1, 4, 15, and the
    odd-numbered problems for 19–31 for Section 7.10. When you are done,
    check your solutions with the answers on page 493.  
        
    This activity should take approximately 3 hours to complete.

       
    Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.


