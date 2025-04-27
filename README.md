# cs1301---homework-8---apis-solved
**TO GET THIS SOLUTION VISIT:** [CS1301 – Homework 8 – APIs Solved](https://www.ankitcodinghub.com/product/cs1301-homework-8-apis-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123759&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1301 - Homework 8 - APIs Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
How to Think Like a Computer Scientist

CS 1301 YouTube Channel

Comment out or delete all function calls. Only import statements, global variables, and comments are okay to be outside of your functions.

Read the entire document before starting this assignment.

The goal of this homework is for you to enhance your understanding of APIs and making requests. The homework will consist of 5 functions for you to implement. You have been given

HW08.py skeleton file to fill out. However, below you will find more detailed information to complete your assignment. Read it thoroughly before you begin.

Hidden Test Cases: In an effort to encourage debugging and writing robust code, we will be including hidden test cases on Gradescope for some functions. You will not be able to see the input or output to these cases. Below is an example output from a failed hidden test case:

Written by Fareeda Kasim (kasimfareeda@gatech.edu), Grace Saad (gsaad6@gatech.edu), &amp; Josh Tabb (jtabb6@gatech.edu)

Helpful Information to Know

API Documentation: This homework uses two APIs across its problems. In order to use an API properly, looking through the documentation is essential. Here is the documentation for the two APIs in this homework:

Harry Potter: https://www.potterapi.com/#introduction Star Wars: https://swapi.dev/documentation

API Keys: In order to prevent people from spamming/abusing their services, some APIs require you to register for keys so that you can use them. You will need to register for an API key for the Harry Potter API, the API used for the first two problems. Register for a key at this link (it’s free): https://www.potterapi.com/login/#signup.

Once you create an account, click your email address on the right menu, and your key is the long string beside the key icon. Add this key in each of your requests to the Harry Potter API. You do not need a key for the Star Wars API.

To actually use your key, you’ll need to attach it to the end of your request URL. For example, let’s say your key is the string below:

Meet New People

Function Name: meetNewPeople()

Parameters: house ( str )

Returns: list of people ( list )

Matching Students

Function Name: matchingStudents()

Parameters: character name ( str )

Returns: list of students ( list )

Description: You want to see how many students are similar to a given character. Using the Harry Potter API, write a function that returns a list of all characters that are students and have the same blood status and house as the given character. The given character should not be included in this list. The given character will always be a real character, and will have a house and blood status.

Similar Characters

Function Name: similarCharacters()

Parameters: movieID1 ( str ), movieID2 ( str )

Returns: number of people ( int )

Description: You just found out that the Star Wars API has info on 6 Star Wars movies, and you’ve decided to binge watch all of them this weekend. Given two movie IDs, you want to find out how many characters appear in both movies. Using the Star Wars API, write a function that takes in two movie IDs, and returns the number of characters that appear in both movies. If any of the movie IDs are invalid, return 0 .

Hint: Look for an API endpoint related to films that also takes an “id”. You only need 2 API requests to solve this problem.

Space Drifting

Function Name: spaceDrifting()

Parameters: passengers( int ), max price( int )

Returns: list of valid starships ( list )

Description: You recently heard about some illegal starship racing going down on the intergalactic streets, and you want in. But first, you’ll need a starship. Create a function that takes in a minimum number of passengers (inclusive) and maximum price that you’re willing to pay (exclusive), return a list of starships that meet our requirements in the form of tuples. The first element of each tuple is the name of the starship, and the second element is the manufacturer of the starship. If there are no starships that satisfy our requirements, return an empty list.

Note: For simplicity’s sake, we will only be looking at the first page of results of starships in the API.

Hint: Some starships will have values of ‘n/a’ for passengers or some other format of string which prevents us from converting that string to an integer. We will ignore these starships; to do this, you might consider using Try/Except .

&gt;&gt;&gt; spaceDrifting(0, 1000000)

[(‘Sentinel-class landing craft’, ‘Sienar Fleet Systems, Cyngus Spaceworks’),

(‘Millennium Falcon’, ‘Corellian Engineering Corporation’),

(‘Y-wing’, ‘Koensayr Manufacturing’), (‘X-wing’, ‘Incom Corporation’)]

Leia’s Perfect Match

Function Name: perfectMatch()

Parameters: list of candidates ( list )

Returns: list of potential matches ( list )

Description: After unforunately learning that Luke was her brother in Return of the Jedi, Leia has decided to try out some intergalactic speed dating. With so many people in the galaxy, Leia needs some kind of filter so she doesn’t end up wasting her time. Leia has decided that any candidate must be at least 180 centimeters tall (inclusive), must be a male, and CANNOT be Darth Vader or Luke Skywalker (they are both automatically disqualified). Write a function that takes in a list of candidates, and returns a list of potential matches based on Leia’s requirements. This list should be in alphabetical order. If either the height or gender are unavailable, then the candidate should be disqualified. If none of the candidates are a good match for Leia, then return an empty list.

Note: For simplicity’s sake, we will only be looking at the first page of results of people in the API.

Grading Rubric

Function Points

meetNewPeople() 20

matchingStudents() 20

similarCharacters() 20

spaceDrifting() 20

perfectMatch() 20

Total 100

Provided

The HW08.py skeleton file has been provided to you. This is the file you will edit and implement. All instructions for what the functions should do are in this skeleton and this document.

Submission Process
