**Unit 3: Vector Spaces, Fields, Linear Transformations, and Markov
Chains** <span id="3"></span> 
*In this unit, we will begin by defining fields and discussing some
important examples.  Complex numbers (C) will give us insight into some
of the key mathematical concepts of linear algebra.  We will define
vector spaces and study their basic properties before studying finite
dimensional vectors spaces.  Then, concepts of linear independence,
span, bases, subspaces, and dimension are examined in the context of
vector spaces.  A strong understanding of vector spaces is necessary,
because linear algebra is the study of linear maps on vectors spaces. 
Without a good grasp of vector spaces, understanding linear algebra
becomes difficult. *  
 *   
 *After studying vectors spaces, we will begin to study a special kind
of function known as a linear map.  These functions arise naturally in
linear algebra.  We will study linear maps from one vector space to
another, as well as linear maps from a vector space to itself (these
maps are known as operators and are extremely important in linear
algebra).  Keep in mind that most of the results in this unit are for
finite-dimensional vector spaces only.  We will then learn how some
matrices can be transformed into*  *Jordan canonical form, an upper
triangular form for the matrix in which the eigenvalues appear on the
diagonal.  Note that linear maps have many applications in fields
outside of mathematics, such as physics (quantum mechanics, etc.) and
engineering (traffic flow, difference equations, etc.).  You will
finally learn about a certain kind of matrices, called Markov matrices,
and see that the existence of the Jordan form is the basis for the proof
of limit theorems for Markov matrices.**

**Unit 3 Time Advisory**  
This unit will take you approximately 35.5 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit  3.1: 17.5 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 3.1.1: 2.5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 3.1.2: 10 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 3.1.2.1: 4.5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 3.1.2.2: 1.5 hour

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 3.1.2.3: 4 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 3.1.3: 5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit  3.2: 9.5 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 3.2.1: 2 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 3.2.2: 2.5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Sub-subunit 3.2.3: 5 hours

☐    Subunit  3.3: 5 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Reading: 1 hour

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Activity: 4 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 14.545454025268555px; line-height: 21px; -webkit-text-size-adjust: none;">☐
   </span>Subunit  3.4: 3.5 hours 

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Define a vector space and state its properties.
-   Define and identify subspaces of a vector space.
-   Compute the linear span of a set of vectors.
-   Determine the linear independence or dependence of a set of vectors.
-   Determine a basis of a vector space.
-   Determine the dimension of a vector space.
-   Define and identify linear transformations.
-   Find the matrix of certain types of linear transformations.
-   Define the characteristic polynomial of a linear transformation .
-   State properties of invertible matrices.
-   Define a Markov matrix.
-   State what it means to have the property of being a stochastic
    matrix.
-   Perform range-nullspace decompositions.
-   Perform orthogonal decomposition of space.
-   Perform singular-value decomposition.

**3.1 Vector Spaces and Fields** <span id="3.1"></span> 
**3.1.1 Vector Spaces and Their Properties** <span id="3.1.1"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 8: Vector Spaces and
    Fields”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 8: Vector Spaces and
    Fields”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 8.1 (pages 199 and 200) in  its
    entirety. The definition of a vector space is an important one, and
    you should compare the axioms with their more familiar analogs from
    algebra.  
      
     Studying this reading should take approximately 1 hour to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 4: Vector Spaces”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 4: Vector
    Spaces”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Pleaseread Sections 4.1 and 4.2. Here the notion of a
    vector is abstracted. Pay particular attention to the example of
    polynomial functions, which is the first example of a vector space
    which is not simply an ordered n-tuple of numbers.  
        
     Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

**3.1.2 Subspaces, Span, and Bases** <span id="3.1.2"></span> 
**3.1.2.1 Subspaces** <span id="3.1.2.1"></span> 
-   **Activity: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Exercises for Chapter 4”**

    Link: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Exercises for Chapter
    4”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please complete calculational exercises 2 and 4 and
    proof-writing exercises 1, 2, and 3 (pages 46–47). 

    Completing this activity should take approximately 2.5 hours.

       
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 8: Vector Spaces and
    Fields”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 8: Vector Spaces and
    Fields”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Sections 8.2.1 and 8.2.2 (pages 200–205)
    in their entirety. The notions of basis and subspace are extremely
    important ones to master. Read through the examples and proofs on
    your own. If the proofs are confusing, try working them out in a low
    dimensional case first.  
        
     Studying this reading should take approximately 1 hour to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 4: Vector Spaces”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 4: Vector
    Spaces”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Sections 4.3 and 4.4. Work through the
    examples on your own, and compare your work with that in the text.

    Studying this reading should take approximately 1 hour to complete.

       
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes, and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
     Any reproduction or redistribution for commercial use is strictly
    prohibited.

**3.1.2.2 Span** <span id="3.1.2.2"></span> 
-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 5: Span and Bases”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 5: Span and
    Bases”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Sections 5.1 and 5.2. The notions of
    span, basis, independence, and dimension are crucial to
    understanding linear algebra and its applications.  
      

    Studying this reading should take approximately 1.5 hour to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

**3.1.2.3 Bases** <span id="3.1.2.3"></span> 
-   **Activity: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Exercises for Chapter 5”**

    Link: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Exercises for Chapter
    5”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please complete calculational exercises 2 and 5 and
    proof-writing exercises 2, 4, 5, and 6 (pages 60 and 61).   
      

    Completing this activity should take approximately 2.5 hours to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf). Any
    reproduction or redistribution for commercial use is strictly
    prohibited.

-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 8: Vector Spaces and
    Fields”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 8: Vector Spaces and
    Fields”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 8.2.3 (page 205) in its entirety.
    Read through the proof of the theorem and make sure you understand
    why the process presented in the proof must terminate.  
      

    Studying this reading should take approximately 45 minutes to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 5: Span and Bases”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 5: Span and
    Bases”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
      
     Instructions: Please read Sections 5.3 and 5.4. Work through the
    examples on your own, and compare your work with that in the text.

     

    Studying this reading should take approximately 45 minutes to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

**3.1.3 Fields** <span id="3.1.3"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 8: Vector Spaces and
    Fields”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 8: Vector Spaces and
    Fields”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 8.3 (pages 205–219) in its
    entirety. Note how the existence of roots of a particular polynomial
    depends heavily on the field being considered. You should also
    compare this to the situation regarding the Fundamental Theorem of
    Algebra.  
        
     Studying this reading should take approximately 1 hour to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Activity: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 8: Vector Spaces and
    Fields”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 8: Vector Spaces and
    Fields”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)

    Instructions: Please work through the odd-numbered problems for 1–25
    for Section 8.4 on pages 219–221. When you are done, check your
    solutions with the answers on page 494.

    Completing this activity should take approximately 4 hours to
    complete.  
      

    Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

**3.2 Linear Transformations** <span id="3.2"></span> 
**3.2.1 Basics** <span id="3.2.1"></span> 
-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 6: Linear Maps”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 6: Linear
    Maps”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please read Sections 6.1–6.5 in their entirety.
    Linear maps are those which preserve the structure of a vector space
    and are a rich source of additional vector spaces. Work through the
    examples on your own, and compare your work with that in the text.  
        
     Studying this reading should take approximately 2 hours to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

**3.2.2 Matrices and Linear Transformations** <span id="3.2.2"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 9: Linear
    Transformations”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 9: Linear
    Transformations”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Sections 9.1–9.3 (pages 225–240) in their
    entirety.  Pay particular attention to the relationship between a
    linear transformation and an associated matrix.  
        
     Studying this reading should take approximately 1 hour to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Reading: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Chapter 6: Linear Maps”**

    Links: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Chapter 6: Linear
    Maps”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please  read Sections 6.6 and 6.7 in their entirety.
    A linear map between two vector spaces can be represented by a
    matrix, once a basis is chosen for each vector space. Work through
    the examples on your own, and compare your work with that in the
    text.  
      

    Studying this reading should take approximately 1.5 hours to
    complete.  
        
     Terms of Use: These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

**3.2.3 Eigenvalues, Eigenvectors, and Invertibility** <span
id="3.2.3"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 9: Linear
    Transformations”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 9: Linear
    Transformations”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Section 9.4 (pages 240 and 241) in its
    entirety. Note the similarities between the spectral theory for
    matrices and those for more general linear maps.  
        
     Studying this reading should take approximately 30 minutes to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Activity: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 9: Linear
    Transformations”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 9: Linear
    Transformations”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)

    Instructions: Please click on the link above, and work through
    problems 1, 7, 11, 13, 15, and 19 in Section 9.5 on pages 242
    through 244. When you are done, check your solutions with the
    answers on page 494.  
        
     Completing this activity should take approximately 2.5 hours to
    complete.

    Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Activity: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s Linear Algebra: As an Introduction to Abstract
    Mathematics: “Exercises for Chapter 6”**

    Link: UC Davis: Isaiah Lankham, Bruno Nachtergaele, and Anne
    Schilling’s *Linear Algebra: As an Introduction to Abstract
    Mathematics*: [“Exercises for Chapter
    6”](https://resources.saylor.org/archived/wp-content/uploads/2012/10/mat67_course_notes.pdf)
    (PDF)  
        
     Instructions: Please complete calculational exercises 1, 3, and 4
    and proof-writing exercises 1 and 4 (pages 79 and 80).  
        
     Completing this activity should take approximately 2 hours to
    complete.  
        
     Terms of Use:  These materials have been reproduced for educational
    and non-commercial purposes and can be viewed in their original
    format
    [here](https://mail.whittier.edu/owa/redir.aspx?C=fa77263df66842f9a74d8d1b871cd15b&URL=http%3A%2F%2Fwww.math.ucdavis.edu%2F~anne%2Flinear_algebra%2Fmat67_course_notes.pdf).
    Any reproduction or redistribution for commercial use is strictly
    prohibited.

**3.3 Linear Transformations Canonical Forms** <span id="3.3"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 10: Linear Transformations
    Canonical Forms”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 10: Linear Transformations Canonical
    Forms”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Chapter 10 (pages 245–274) in its
    entirety. Pay particular attention to the Jordan canonical form.  
        
     Studying this reading should take approximately 1 hour to
    complete.  
      
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Activity: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 10: Linear Transformations
    Canonical Forms”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 10: Linear Transformations Canonical
    Forms”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)

       
     Instructions: Please work through problems 2, 8, 10, 11, and 16 in
    Section 10.6 (pages 262 and 264) and problems 4–8 in Section 10.9
    (pages 273 and 274). When you are done, check your solutions with
    the answers on pages 494 and 495.  
        
    Completing this activity should take approximately 4 hours to
    complete.

       
    Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

**3.4 Linear Transformations Canonical Forms** <span id="3.4"></span> 
-   **Reading: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 11: Markov Chains and
    Migration Processes”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 11: Markov Chains and Migration
    Processes”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)  
        
     Instructions: Please read Chapter 11 (pages 275–286) in its
    entirety. Markov chains have applications in many fields.   
        
     Studying this reading should take approximately 1 hour to
    complete.  
        
     Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.

-   **Activity: Brigham Young University: Kenneth Kuttler’s An
    Introduction to Linear Algebra: “Chapter 11: Markov Chains and
    Migration Processes”**

    Link: Brigham Young University: Kenneth Kuttler’s *An Introduction
    to Linear Algebra:* [“Chapter 11: Markov Chains and Migration
    Processes”](https://resources.saylor.org/archived/wp-content/uploads/2012/02/Linear-Algebra-Kuttler-1-30-11-OTC.pdf)
    (PDF)

       
     Instructions: Please work through problems 1, 6, 8, 9, and 12 in
    Section 11.4 on pages 284 and 285. When you are done, check your
    solutions with the answers on page 495.  
        
    This activity should take approximately 2.5 hours to complete.

       
    Terms of Use: *An Introduction to Linear Algebra* was written by
    Kenneth Kuttler and was relicensed as CC-BY 3.0 as part of the
    Saylor Foundation’s Open Textbook Challenge.  
      


