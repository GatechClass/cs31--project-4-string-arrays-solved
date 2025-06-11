# cs31--project-4-string-arrays-solved
**TO GET THIS SOLUTION VISIT:** [CS31- Project 4: String Arrays Solved](https://mantutor.com/product/cs31-project-4-string-arrays-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;79085&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS31- Project 4: String Arrays Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
<h3><b><span class="">Introduction</span></b><span class="">&nbsp;</span></h3>
<p id="yui_3_17_2_1_1595141673874_46"><span class="">As you gain experience with arrays, you’ll discover that many applications do the same kinds of things with them (e.g., find where an item is in an array, or check whether two arrays differ). You’ll find that it’s helpful to have a library of useful functions that manipulate arrays. (For our purposes now, a library is a collection of functions that developers can call instead of having to write them themselves. For a library to be most useful, the functions in it should be related and organized around a central theme. For example, a screen graphics library might have functions that allow you to draw shapes like lines and circles on the screen, move them around, fill them with color, etc. In this view, the Standard C++ library is really a collection of libraries: a string library, a math library, an input/output library, and much more.)</span>

<span class="">Your assignment is to produce a library that provides functions for many common manipulations of arrays of strings. For each function you must write, this specification will tell you its interface (what paramet</span><span class="">ers it takes, what it returns, and&nbsp;</span><em><span class="">what</span></em><span class="">&nbsp;it must do). It’s up to you to decide on the implementation (</span><em><span class="">how</span></em><span class="">&nbsp;it will do it).</span>

The source file you turn in will contain all the functions and a main routine. You can have the main routine do whatever you want, because we will rename it to something harmless, never call it, and append our own main routine to your file. Our main routine will thoroughly test your functions. You’ll probably want your main routine to do the same. If you wish, you may write functions in addition to those required here. We will not directly call any such additional functions. If you wish, your implementation of a function required here may call other functions required here.<span class="">&nbsp;</span>

<span class="">The program you turn in must build successfully, and during execution, no function (other than main) may read anything from&nbsp;</span><code><span class="">cin</span></code><span class="">&nbsp;or write anything to&nbsp;</span><code><span class="">cout</span></code><span class="">. If you want to print things out for debugging purposes, write to&nbsp;</span><code><span class="">cerr</span></code><span class="">&nbsp;instead of&nbsp;</span><code><span class="">cout</span></code><span class="">. When we test your program, we will cause everything written to&nbsp;</span><code><span class="">cerr</span></code><span class="">&nbsp;to be discarded instead — we will never see that output, so you may leave those debugging output statements in your program if you wish.</span>

<p id="yui_3_17_2_1_1595141673874_50"><span id="yui_3_17_2_1_1595141673874_49" class="">All of the functions you must write take at least two parameters: an array of strings, and the number of items the function will consider in the array, starting from the beginning. For example, in</span>

<span class=""> string folks[8] = {

</span><span class=""> “samwell”, “jon”, “margaery”, “daenerys”,

</span><span class=""> “tyrion”, “sansa”, “llewmas</span><span class="">“, “noj” }; bool b = hasReverse( folks, 5 ); // should return false and not inspect the last three elements….

</span> <span class="">even though the array has 8 elements, only the first 5 had values we were interested in for this call to the function; the function must not examine any of the others. </span>

<span class="">The one error your function implementations don’t have to handle (because they cannot) is when the caller of the function lies and says the array is bigger than it really is. For example, in this situation. the function can’t possibly know the caller is lying about the number of items in the array: </span><span class=""> string people[5] = { “jon”, “mamabbcc!”, “samwell,”, “daenerys.”, “tyrion” }; </span> bool b = hasReverse(people, 25 ); // Bad driver code call // your implementation doesn’t have to check for this, because it can’t

<span class="">T</span><span class="">o make your life easier, whenever this specification talks about strings being equal or about one string being less than or greater than another, the case of letters matters. This means that you can simply use comparison operators like == or &lt; to compare strings. Because of the character collating sequence, all upper case letters come before all lower case letters, so don’t be surprised by that result. The&nbsp;</span><a href="http://web.cs.ucla.edu/classes/spring15/cs31/stahl/Projects/4/faq.html"><span class="">FAQ</span></a><span class="">&nbsp;has a note about string comparisons.</span>

<h3><b><span class="">Your task</span></b></h3>
<span class="">Here are the functions you must implement:&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</span>

<dl id="yui_3_17_2_1_1595141673874_62">
<dd id="yui_3_17_2_1_1595141673874_61"><b><span class="">int</span><span class="">&nbsp;locateMinimum(&nbsp;</span><span class="">const</span><span class="">&nbsp;</span><span class="">string</span><span class="">&nbsp;</span><span class="">array[ ],&nbsp;</span><span class="">int</span></b><b><span class="">&nbsp;n );</span></b>

<span class="">Return the index of the smallest item found in the passed array or -1 if n &lt;= 0. &nbsp;</span><span class="">For example, for the array&nbsp;</span><span class="">people[ 5 ]</span><span class="">&nbsp;shown above,&nbsp;</span><span class=""><del>locateMaximum</del>&nbsp;locateMinimum( people, 5 )</span><span class="">&nbsp;should return the value 3, corresponding to the index of&nbsp;“daenerys.”. &nbsp;If there are multiple duplicate minimum values, return the smallest index that has this minimum value.&nbsp; The minimum value is determined by its dictionary-sorted order which is what &lt; and &gt; use in C++ to determine&nbsp;true&nbsp;and&nbsp;false.</span>

<p id="yui_3_17_2_1_1595141673874_59"><b><span class="">int</span><span class="">&nbsp;countPunctuation(&nbsp;</span><span class="">const</span><span class="">&nbsp;</span><span class="">string</span><span class="">&nbsp;array[ ],&nbsp;</span><span class="">int</span><span class="">&nbsp;&nbsp;</span><span class="">n );</span>

</b><span id="yui_3_17_2_1_1595141673874_58"><span class="">Return the number of punctuation characters found inside each of the elements of the passed array or if n &lt;= 0 return -1</span><span class="">.&nbsp; Punctuation characters to be counted should include:&nbsp; &nbsp;,&nbsp; &nbsp;.&nbsp; &nbsp;;&nbsp; –&nbsp; &nbsp;?&nbsp; !&nbsp; &nbsp;:&nbsp; ”&nbsp; (&nbsp; &nbsp;)&nbsp; &nbsp; &nbsp;namely, comma, period, semicolon, dash, question mark, exclamation mark, colon, double quote and parentheses.&nbsp;&nbsp;</span><span class="">For example, for the array&nbsp;</span><span class="">&nbsp;</span><span class="">people[ 5 ]</span><span class="">&nbsp;</span><span class="">&nbsp;shown above,&nbsp;</span><span class="">countPunctuation( people, 5 )</span><span class="">&nbsp;</span><span id="yui_3_17_2_1_1595141673874_57"><span class="">&nbsp;should return&nbsp;</span><span class="">3</span><span class="">. &nbsp;&nbsp;</span><span class="">For the array&nbsp;</span><span class="">&nbsp;</span><span class="">people[ 5 ]</span><span class="">&nbsp;</span><span class="">&nbsp;shown above,&nbsp;</span><span class="">&nbsp;</span><span class="">countPunctuation( people, 1 )</span><span class="">&nbsp;</span><span id="yui_3_17_2_1_1595141673874_56"><span class="">&nbsp;should return&nbsp;</span><span id="yui_3_17_2_1_1595141673874_55"><span class="">0&nbsp;</span><span class="">because the first element has no punctuation characters.&nbsp;</span></span></span></span></span>

<b><span class="">bool hasReverse(&nbsp;</span><span class="">const</span><span class="">&nbsp;</span><span class="">string</span><span class="">&nbsp;array[ ],&nbsp;</span><span class="">int</span><span class="">&nbsp;n</span><span class="">&nbsp;);</span>

</b><span class="">If there is an element in the passed array whose value is the reverse of an existing value found in the array, return&nbsp;true&nbsp;otherwise&nbsp;false&nbsp;or if n &lt;= 0 return&nbsp;false&nbsp;. &nbsp;For example, for the array&nbsp;people[ 5 ]&nbsp;shown above,&nbsp;hasReverse( people, 5 )&nbsp;should return&nbsp;false.&nbsp; For example, for the array&nbsp;folks[ 8 ]&nbsp;shown above,&nbsp;hasReverse( folks, 8 )&nbsp;should return&nbsp;true&nbsp; because “samwell” and its reverse “llewmas” are in the array as well as “jon” and “noj”.</span>

<b><span class="">char highestOccurredCharacter( const&nbsp;</span><span class="">string</span><span class="">&nbsp;array[ ],&nbsp;</span><span class="">int</span><span class="">&nbsp;n,&nbsp;</span><span class="">int</span><span class="">&nbsp;index</span><span class="">&nbsp;);</span>

</b><span class="">For the element found at position index in the passed array, return the character that occurred more frequently than any other character in the identified string element.&nbsp; Unlike the other functions in this assignment, your code should only inspect a single string, not an entire array.&nbsp; If multiple characters occur an identical number of times, your function can decide which of these characters to return.&nbsp; For example, for the array&nbsp;people[ 5 ]&nbsp;shown above,&nbsp;highestOccurredCharacter( people, 5, 0 )&nbsp;can return either&nbsp;‘j’&nbsp;or&nbsp;‘o’&nbsp;or&nbsp;‘n’.&nbsp; For example, for the array&nbsp;people[ 5 ]&nbsp;shown above,&nbsp;highestOccurredCharacter( people, 5, 2 )&nbsp;should return&nbsp;‘l’.</span><span class="">&nbsp;&nbsp;</span><span class="">If n &lt;= 0 or index &gt;= n or index &lt; 0, return&nbsp;‘\0’&nbsp;which is the NULL character.&nbsp;&nbsp;</span>

<b><span class="">bool</span><span class="">&nbsp;isInIncreasingOrder(&nbsp;</span><span class="">const</span><span class="">&nbsp;</span><span class="">string</span><span class="">&nbsp;array[ ],&nbsp;</span><span class="">int</span><span class="">&nbsp;&nbsp;</span><span class="">n );</span>

</b><span class="">If every value in the array is larger than the one that precedes it, return&nbsp;</span><span class="">true</span><span class="">&nbsp;</span><span class="">&nbsp;otherwise&nbsp;</span><span class="">false</span><span class="">&nbsp;or if n &lt;= 0 return&nbsp;</span><span class="">false</span><span class="">&nbsp;</span><span class="">. &nbsp;</span><span class="">For example, for the array&nbsp;</span><span class="">&nbsp;</span><span class="">people[ 5 ]</span><span class="">&nbsp;shown above,&nbsp;</span><span class="">isInIncreasingOrder( people, 5 )&nbsp;should return&nbsp;</span><span class="">false</span><span class="">.&nbsp; For example, for the array&nbsp;people[ 5 ]&nbsp;shown above,&nbsp;isInIncreasingOrder( people, 3 )&nbsp;should return&nbsp;true.</span>
</dd>
<dd><span class=""><b>char firstNonRepeatedCharacter( const string array[ ], int n, int index );</b>

For the element found at position index in the passed array, return the first non-repeated character found in the identified string element.&nbsp; Unlike the other functions in this assignment, your code should only inspect a single string, not an entire array.&nbsp; For example, for the array&nbsp;people[ 5 ]&nbsp;shown above,&nbsp;firstNonRepeatedCharacter( people, 5, 1 )&nbsp;should return&nbsp;‘!’.&nbsp; For example, for the array&nbsp;people[ 5 ]&nbsp;shown above,&nbsp;firstNonRepeatedCharacter( people, 5, 0 )&nbsp;should return&nbsp;‘j’.&nbsp;&nbsp;If n &lt;= 0 or index &gt;= n or index &lt; 0, return&nbsp;‘\0’&nbsp;which is the NULL character.&nbsp;&nbsp;</span></dd>
<dd><span class=""><b>bool isOnlyDigits( const string array[ ], int n );

</b></span>If every element in the passed array is comprised of only digit characters 0-9, return&nbsp;<span class="">true</span>&nbsp;otherwise&nbsp;<span class="">false</span>&nbsp;or if n &lt;= 0 return&nbsp;<span class="">false</span>.&nbsp; &nbsp;An example of using this function is shown below.</dd>
<dd>Additionally, I have created a testing tool called CodeBoard to help you check your code.&nbsp; CodeBoard enables you to be sure you are naming things correctly by running a small number of tests against your code.&nbsp; Passing CodeBoard tests is not sufficient testing so please do additional testing yourself.&nbsp; To access CodeBoard for Project 4, please click the link you see in this week named CodeBoard for Project 4.&nbsp; Inside the file named user_functions.cpp, copy and paste your implementation of the assigned functions.&nbsp; CodeBoard uses its own main( ) to run tests against your code.&nbsp; Click Compile and Run.&nbsp; However please be aware that no editing changes can be saved inside CodeBoard.&nbsp; In this anonymous user configuration, CodeBoard is read-only and does not allow for saving changes.</dd>
</dl>
<dl>
<dd>
<p class="p1"><b><span class="">Programming Guidelines</span></b>

</dd>
</dl>
<span class="">Your program must&nbsp;<em>not</em>&nbsp;use any function templates from the algorithms portion of the Standard C++ library or use STL &lt;list&gt; or &lt;vector&gt;. If you don’t know what the previous sentence is talking about, you have nothing to worry about. Additionally, your code must&nbsp;<i>not</i>&nbsp;use any global variables which are variables declared outside the scope of your individual functions.</span>

<span class="">Your program must build successfully under both Visual C++ and either clang++ or g++.</span>

<span class="">The correctness of your program must not depend on undefined program behavior. Your program could not, for example, assume anything about&nbsp;</span><code><span class="">t</span></code><span class="">‘s value in the following, or even whether or not the program crashes:</span>

<pre>	int main()
	{
	    string s[3] = { "samwell", "jon", "tyrion" };
	    string t = s[3];  // position 3 is out of range
	    …
</pre>
<span class="">What you will turn in for this assignment is a zip file containing these two files and nothing more:</span>

<ol>
<li><span class="">A text file named&nbsp;</span><b><span class="">array.cpp</span><span class="">&nbsp;</span></b><span class="">&nbsp;that contains the source code for your C++ program. Your source code should have helpful comments that explain any non-obvious code.</span></li>
<li><span class="">A file named&nbsp;</span><strong><span class="">report.doc</span></strong><span class="">&nbsp;</span><span class="">or&nbsp;</span><strong><span class="">report.docx</span></strong><span class="">&nbsp;(in Microsoft Word format) or&nbsp;</span><strong><span class="">report.txt</span></strong><span class="">&nbsp;(an ordinary text file) that contains in addition&nbsp;</span><b><span class="">your name</span></b><span class="">&nbsp;and&nbsp;</span><b><span class="">your UCLA Id Number</span></b><span class="">:</span>
<ol>
<li><span class="">A brief description of notable obstacles you overcame.</span></li>
<li><span class="">A list of the test data that could be used to thoroughly test your functions, along with the reason for each test. You must note which test cases your program does not handle correctly. (This could happen if you didn’t have time to write a complete solution, or if you ran out of time while still debugging a supposedly complete solution.) Notice that most of this portion of your report can be written just after you read the requirements in this specification, before you even start designing your program.</span></li>
</ol>
</li>
</ol>
<span class="">How nice! Your report this time doesn’t have to contain any design documentation.</span>

<span class="">As with Project 3, a nice way to test your functions is to use the&nbsp;</span><code><span class="">assert</span></code><span class="">&nbsp;facility from the standard library. As an example, here’s a very incomplete set of tests for Project 4:</span>

<pre>	#include &lt;iostream&gt;
	#include &lt;string&gt;
	#include &lt;cassert&gt;

	using namespace std;   

	int main()
	{</pre>
<p class="p1"><span class="s1"> string a[6] = { </span>“123”, “456”, “789”, “gamma”, “beta”, “delta” };

<p class="p1"><span class="s1">&nbsp; &nbsp; </span><span class="s2">assert</span><span class="s1">(isOnlyDigits</span><span class="s1">(a, 6</span><span class="s1"> ) == false</span><span class="s1">); </span><span class="s2"> assert</span><span class="s1">(</span><span class="s3">isOnlyDigits</span><span class="s1">(a, 3</span><span class="s1"> ) == true</span><span class="s1">);</span>

<pre>	    cout &lt;&lt; "All tests succeeded" &lt;&lt; endl;
            return( 0 );</pre>
<pre>         }
</pre>
<span class="">The reason for the one line of output at the end is to ensure that you can distinguish the situation of all tests succeeding from the case where one test silently crashes the program.</span>

<span class="">Make sure that if you were to replace your main routine with the one above, your program would build successfully under both Visual C++ and either clang++ or g++.&nbsp; This means that even if you haven’t figured out how to implement some of the functions, you must still have&nbsp;</span><em><span class="">some</span></em><span class="">&nbsp;kind of implementations for them, even if those implementations do nothing more than immediately return.&nbsp;</span>

<span class="">Turn in the file by the due time above. Give yourself enough time to be sure you can turn something in, because we will not accept excuses like “My network connection at home was down, and I didn’t have a way to copy my files and bring them to a SEASnet machine.” There’s a lot to be said for turning in a preliminary version of your program and report early (You can always overwrite it with a later submission). That way you have something submitted in case there’s a problem later.</span>

&nbsp;

<dl>
<dd><b>G31 Build Commands</b></dd>
</dl>
<pre>	g31 -c array.cpp
        g31 array.o -o runnable
        ./runnable</pre>
