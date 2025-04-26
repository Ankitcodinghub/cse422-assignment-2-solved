# cse422-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CSE422 Assignment 2 Solved](https://www.ankitcodinghub.com/product/cse422-artificial-intelligence-c02-lab-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;132108&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE422 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Part 1 [7 points]

Chromosome Representation (Encoding):

● Length of the Chromosome: The length of a chromosome will be equal to

𝑁𝑥𝑇 (𝑝𝑟𝑜𝑑𝑢𝑐𝑡 𝑜𝑓 𝑁 𝑎𝑛𝑑 𝑇), where 𝑁 is the number of courses and 𝑇 is the number of timeslots.

● Structure of the Chromosome: Each chromosome will be divided into 𝑇 segments, where each segment will be of length 𝑁. Each segment will represent a timeslot, and each bit within a segment will represent whether a particular course is scheduled in that timeslot.

Fitness Calculation:

● The fitness function will evaluate each solution based on the number of course overlaps and consistency of a course.

𝐹𝑖𝑡𝑛𝑒𝑠𝑠 (𝑆) = −[ 𝑃𝑒𝑛𝑎𝑙𝑡𝑦𝑜𝑣𝑒𝑟𝑙𝑎𝑝(𝑆) + 𝑃𝑒𝑛𝑎𝑙𝑡𝑦𝑐𝑜𝑛𝑠𝑖𝑠𝑡𝑒𝑛𝑐𝑦(𝑆) ]

Here:

● 𝑆: 𝐵𝑖𝑛𝑎𝑟𝑦 𝑆𝑡𝑟𝑖𝑛𝑔 𝑟𝑒𝑝𝑟𝑒𝑠𝑒𝑛𝑡𝑖𝑛𝑔 𝑠𝑐ℎ𝑒𝑑𝑢𝑙𝑒

● 𝑃𝑒𝑛𝑎𝑙𝑡𝑦𝑜𝑣𝑒𝑟𝑙𝑎𝑝(𝑆):

∑(𝑁𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝑐𝑜𝑢𝑟𝑠𝑒𝑠 𝑜𝑣𝑒𝑟𝑙𝑎𝑝 𝑖𝑛 𝑠𝑐ℎ𝑒𝑑𝑢𝑙𝑒 𝑆 𝑖𝑛 𝑡ℎ𝑒 𝑠𝑎𝑚𝑒 𝑡𝑖𝑚𝑒𝑠𝑙𝑜𝑡).

● 𝑃𝑒𝑛𝑎𝑙𝑡𝑦𝑐𝑜𝑛𝑠𝑖𝑠𝑡𝑒𝑛𝑐𝑦(𝑆):

∑(𝑁𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝑡𝑖𝑚𝑒𝑠 𝑐𝑜𝑢𝑟𝑠𝑒𝑠 𝑎𝑝𝑝𝑒𝑎𝑟𝑒𝑑 𝑚𝑜𝑟𝑒 𝑡ℎ𝑎𝑛 𝑜𝑛𝑐𝑒 𝑖𝑛 𝑠𝑐ℎ𝑒𝑑𝑢𝑙𝑒 𝑆)

Overlap Penalty:

● For each timeslot, count the number of courses scheduled.

● If more than one course is scheduled in the same timeslot, add a penalty equal to the number of extra courses.

Consistency Penalty:

● For each course, check if it is scheduled exactly once.

● If a course is not scheduled exactly once, add a penalty.

Task Breakdown:

2. Implement the fitness function that penalizes overlapping courses and ensures each course is scheduled exactly once.

3. Choose two parents based on random selection for crossover. Show it as a separate function.

4. Perform single-point crossover to create 2 offspring from each pair of selected parents. Show it as a separate function.

5. Write the mutation function to introduce random changes.

6. Create a population of randomly generated course schedules.

7. Run genetic algorithms on the population until the highest fitness has been reached and/or the number of maximum iterations has been reached.

Input

The first line has a number 𝑁 denoting the number of courses and a number T denoting the number of timeslots for a particular day. It will be followed by 𝑁 lines each having a string that represents a course code that needs to be scheduled where,

T&gt;=N

[In this problem statement, we are considering that 1 course will have only 1 section]

Output

The output should be a binary string denoting 1 for scheduled courses and 0 for not scheduled courses in each timeslot. A string consisting of all zeros won’t be accepted. You also need to print the fitness value of the output string.

Example:

Sample Input

3 3

CSE110

MAT110

PHY112

Sample Output

110110010

-6

Explanation

Chromosome Representation

● N×T=3×3=9

● Each timeslot is represented by a segment of length N=3.

Fitness Calculation

Let’s take the output chromosome: 110110010

● Timeslot 1: 110

○ CSE110: 1 (scheduled)

○ MAT110: 1 (scheduled)

○ PHY112: 0 (not scheduled)

● Timeslot 2: 110

○ CSE110: 1 (scheduled)

○ MAT110: 1 (scheduled)

○ PHY112: 0 (not scheduled)

● Timeslot 3: 010

○ CSE110: 0 (not scheduled)

○ MAT110: 1 (scheduled)

○ PHY112: 0 (not scheduled)

Interpretation of the Chromosome

1. Timeslot 1: CSE110, MAT110 are scheduled.

2. Timeslot 2: CSE110, MAT110 are scheduled.

3. Timeslot 3: MAT110 is scheduled.

Penalty Calculation

Overlap Penalty:

● Timeslot 1: 2 courses scheduled, penalty = 2−1=1

● Timeslot 2: 2 courses scheduled, penalty = 2−1=1

● Timeslot 3: 1 course scheduled, penalty = 1−1=0

● Total overlap penalty = 1+1+0=2

Consistency Penalty:

● CSE110: scheduled 2 times, penalty = 2−1 =1

● MAT110: scheduled 3 times, penalty = 3−1 =2

● PHY112: scheduled 0 times, penalty = 0−1 =1

● Total consistency penalty = 1+2+1=4

Total penalty = overlap penalty + consistency penalty = 2+4=6

Summary

● Chromosome 110110010 results in a penalty of 6. So Fitness will be -6

Part 2 [3 points]

For this part randomly select two parents from the initial population of your problem statement. Then perform a two-point crossover to generate two children. The two points have to be chosen randomly, but it has to be made sure the second point always comes after the first point.

Here is an example of how two-point crossover works:

Parent 1: 000111000

Parent 2: 111000111

For two points crossover, we have randomly chosen the following points:

1st point:- between index 2 and index 3

2nd point:- between index 6 and index 7

So the two resultant offsprings are, 000000100 &amp; 111111011

[In this part, you just need to iterate once and print the resultant offspring after doing the crossover]

Part 3 [0 points]

In part 1, you selected parents through random sampling from the initial population. Another advanced technique for parent selection is known as Tournament Selection. Please take some time to research and understand this method at home. Might be helpful in the near future!
