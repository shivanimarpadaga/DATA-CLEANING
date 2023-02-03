# DATA-CLEANING

---
title: "HW2, CS 625, Spring 2023"
output: github_document
---
author: “Shivani Marpadaga”  
date: “2023-02-02”
```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```
#PART1

#1. How many types (kinds) of pets are there?
Ans There are 30 pets(snippet 1(c)).Before there were 83 pets(snippet 1(b)). I have done Facet->Text Facet(snippet 1(a)) and then did corrections on the pet names. There are certain corrections to the pet names like
   giunea pig-->Guinea Pig
   frogg------->Frog
	 other-cat--->Cat
	 Leopard----->Lizard
	
#2. How many dogs?
Ans There are 1130 dogs. Before the dogs were listed with incorrect spellings(snippet 2(a)) like (dig,Digg,doggo etc). Later i have selected the pet name"s column and did Facet->Text Facet(snippet 1(a)) and then selected the dog from the list of pets and tried to edit the names as follows
   dig--->Dog
   Digg-->Dog
   doggo->Dog
   
The result is shown in (snippet 2(b)) with the number of dogs as 1130
   
#3. How many breeds of dogs?
Ans There are 472 pet breeds.I have changed their repeated breeds and spelling mistakes by doing Breeds of dogs->Facet->Text Facet (snippet 3(a)) and then it displays the dog breeds list as in (snippet 3(b)) and rest of the other small changes are done by doing
   Edit cells->Cluster and Edit.(snippet 3(c))
   
   
I have corrected the breeds as follows

  German Shepard  -->German Shepherd
  Golden Retriverr-->Golden Retriever
  Greatpyrenies ---->Great Pyrenees
  Domestic Shorthaired->Domestic Shorthair


#4. What's the most popular dog breed?
Ans The most popular dog breed is Golden Retriever with 175 number of breeds. I have done Facet->Text facet(snippet 1(a)) on the pet's column and then selected the dog from the list of pets and then did the following operations (snippet 4(a))

   Golden Retriever-> Facet -> Text facet -> Count
   
This operation gives the result of breed of dogs which is more number of times repeated

#5. What's the age range of the dogs?
Ans To find the age range of the dogs, select the type of pets column and then perform  Facet->Text Facet(snippet 1(a)) then select the dogs from the list of pets and perform the following operations like (snippet 5(a) snippet 5(b) snippet 5(c))

    Sort -> number-> largest->75.
    
It dispalys the column with all the ages of dogs from highest to lowest as shown in (snippet 5(d))


#6. What's the age range of the guinea pigs?
Ans To find the age of the Guinea pig i have selected the pet's name column and then done the Facet->Text facet and select the guinea pigs from the list of pets and then select (snippet 6(a) snippet 6(b)

   Sort -> number-> largest
   
After performing the above operation on the column of age , it will display the ages from highest to the least 

#7. What is the oldest pet?
Ans  To find the oldest pet, perform the below operation on the pet's age column (snippet 7(a),snippet 7(b),snippet 7(c))

    Sort -> number-> largest->167(cat)
    
It displays the list of ages of pets from highest till the least on which the cat has the highest number of years which is 167.

#8. Which are more popular, betta fish or goldfish? How many of each?
Ans To find the number of betta fish, first select Facet->Text Facet on the pet's name column and then select the betta fish.Then perform the below operation on betta fish column.(snippet 8(a))

betta fish ---> facet---> text facet--->2 count

To find the number of gold fish, first select Facet->Text Facet on the pet's name column and then select the gold fish.Then perform the below operation on gold fish column., (snippet 8(b))

goldfish---- >facet----> text facet--- >7 count.

   
#9 What's the most popular everyday name for a cat?
Ans  select the type of pets column and then perform  Facet->Text Facet then select the cats from the list of pets and perform the following operations like as in (snippet 9(a), snippet 9(b), snippet 9(c))

Pets everyday name -> facet -> textfacet->count-> KITTY(7)

#10 What's the most popular full name for a dog?
Ans  select the type of pets column and then perform  Facet->Text Facet then select the dog from the list of pets and perform the following operations as in (snippet 10(a), snippet 10(b), snippet10(c))

Pets Full name -> facet -> textfacet->count-> DAISY(12)

#PART2

#1. How many types (kinds) of pets are there?
Ans There are 30 pets.

   Facet->Text Facet->30

#2. How many dogs?
Ans There are 1130 dogs
     
     What kind of pet->Facet->Text Facet->Dog->1130

#3. How many breeds of dogs?
Ans There are 472 breeds

    Pet's breed-> Facet->Text Facet->472

#4. What's the most popular dog breed?
Ans The most popular dog breed is Golden Retriever with 174 number      of breeds
     
#5. What's the age range of the dogs?
Ans The age range of the dog is from 0 to 75 years

      Sort -> number-> largest->75

#6. What's the age range of the guinea pigs?
Ans The age range of the guinea pig is from 0 to 5 years

     Guinea pig -> Sort -> number-> largest->5

#7. What is the oldest pet?
Ans  Cat is the oldest pet with 167 years

    Sort -> number-> largest->167(cat)

#8. Which are more popular, betta fish or goldfish? How many of each?
Ans The popular is goldfish with count 7 and the least popular is betta fish with count 2

   betta fish --- facet--- text facet--- 2 count
   goldfish---- facet---- text facet--- 7 count
   
#9 What's the most popular everyday name for a cat?
Ans The popular name for everyday cat is KITTY which is repeated 7 times

    Pets everyday name -> facet -> textfacet->count-> KITTY(7)

#10 What's the most popular full name for a dog?
Ans  The most popular full name for a dog is DAISY which is repeated 12times

  Pets Full name -> facet -> textfacet->count-> DAISY

   
  
