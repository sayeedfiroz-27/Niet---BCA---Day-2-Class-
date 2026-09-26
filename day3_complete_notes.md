<h1>Day 3 - Complete Notes</h1>

<p class="viewer-heading">Complete project-based notes with every topic, code, output, and detailed code explanation.</p>

<section class="toc"><h2>Topics Covered</h2><ol><li><a href="#arithmetic">Arithmetic Operators</a></li><li><a href="#relational">Relational Operators</a></li><li><a href="#logical">Logical Operators</a></li><li><a href="#assignment">Assignment Operators</a></li><li><a href="#membership">Membership Operators</a></li><li><a href="#identity">Identity Operators</a></li><li><a href="#precedence">Operator Precedence</a></li><li><a href="#expression">Expression Evaluation</a></li><li><a href="#if">if Statement</a></li><li><a href="#ifelse">if-else Statement</a></li><li><a href="#ifelif">if-elif-else</a></li><li><a href="#nested">Nested Conditions</a></li><li><a href="#loops">Introduction to Loops</a></li><li><a href="#forloop">for Loop</a></li><li><a href="#whileloop">while Loop</a></li><li><a href="#breakcontinuepass">break, continue, pass</a></li><li><a href="#range">Range Function</a></li><li><a href="#patterns">Pattern-Based Programs</a></li><li><a href="#project">Complete Mini Project</a></li><li><a href="#mixed-project">Mixed Practice Project</a></li><li><a href="#practice-tasks">5 Practice Tasks</a></li><li><a href="#student-notes">Student Notes Summary</a></li></ol></section>
<section class="card"><h2>Class Flow</h2><p>Is page ka flow project-building style me rakha gaya hai. Har topic sirf syntax nahi sikhata, balki Student Marks Management System ka ek real feature ready karta hai. Isliye examples random nahi hain; har example result calculation, validation, report generation, grade assignment, attendance check ya scholarship decision se connected hai.</p><p>Top to bottom padhne par learner pehle calculations samjhega, phir comparisons, phir decisions, phir loops, aur end me complete result report project build karega.</p></section>
<h2 id="arithmetic" class="topic">1. Arithmetic Operators</h2>
<p>Arithmetic operators Python me numerical calculation ke liye use hote hain. Jab hume marks add karne ho, percentage nikalni ho, average calculate karna ho, ya remaining marks find karne ho, tab arithmetic operators ka use hota hai.</p>
<p>Student Marks Management System me arithmetic operators sabse pehle use honge, kyunki project ka core output total marks, percentage, average marks aur result summary hota hai.</p>
<p>Common operators hain: + addition ke liye, - subtraction ke liye, * multiplication ke liye, / decimal division ke liye, // floor division ke liye, % remainder ke liye, aur ** power ke liye. In operators ko samajhne ke baad learner kisi bhi calculation based Python project ka base bana sakta hai.</p>
<div class="box use"><span class="tag">Real World Use</span>School result apps, college ERP, scholarship portals, billing systems aur analytics dashboards me arithmetic operators calculation engine ki tarah kaam karte hain.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 1: Total marks, percentage, average aur remaining marks calculate karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Complete Result Calculation</h3><p>Ye example project ka sabse useful calculation part hai. Isme 5 subjects ke marks se total, percentage aur average nikal raha hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>maths = 88
english = 76
science = 91
computer = 95
hindi = 80
total_marks = maths + english + science + computer + hindi
maximum_marks = 500
percentage = (total_marks / maximum_marks) * 100
average_marks = total_marks / 5
print(&quot;Total Marks:&quot;, total_marks)
print(&quot;Percentage:&quot;, percentage)
print(&quot;Average Marks:&quot;, average_marks)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Total Marks: 430
Percentage: 86.0
Average Marks: 86.0</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>maths = 88</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>english = 76</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>science = 91</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>4</td><td><code>computer = 95</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>5</td><td><code>hindi = 80</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>6</td><td><code>total_marks = maths + english + science + computer + hindi</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>7</td><td><code>maximum_marks = 500</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>8</td><td><code>percentage = (total_marks / maximum_marks) * 100</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>9</td><td><code>average_marks = total_marks / 5</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>10</td><td><code>print(&quot;Total Marks:&quot;, total_marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>11</td><td><code>print(&quot;Percentage:&quot;, percentage)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>12</td><td><code>print(&quot;Average Marks:&quot;, average_marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Marks Gap for Target Percentage</h3><p>Ye example learner ko practical thinking deta hai: agar target percentage chahiye to aur kitne marks required hain.</p>
<div class="run-loc">Python Code</div>
<pre><code>current_marks = 430
maximum_marks = 500
target_percentage = 90
target_marks = (target_percentage / 100) * maximum_marks
marks_needed = target_marks - current_marks
print(&quot;Target Marks:&quot;, target_marks)
print(&quot;More Marks Needed:&quot;, marks_needed)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Target Marks: 450.0
More Marks Needed: 20.0</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>current_marks = 430</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>maximum_marks = 500</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>target_percentage = 90</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>4</td><td><code>target_marks = (target_percentage / 100) * maximum_marks</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>5</td><td><code>marks_needed = target_marks - current_marks</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>6</td><td><code>print(&quot;Target Marks:&quot;, target_marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>7</td><td><code>print(&quot;More Marks Needed:&quot;, marks_needed)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="relational" class="topic">2. Relational Operators</h2>
<p>Relational operators two values ko compare karte hain aur result True ya False dete hain. Ye operators program ko decision lene ke liye data provide karte hain.</p>
<p>Student result project me hume bar-bar compare karna hota hai: marks passing marks se zyada hain ya nahi, percentage distinction limit se upar hai ya nahi, attendance allowed limit se kam hai ya nahi.</p>
<p>Important relational operators hain >, <, >=, <=, == aur !=. Inka output boolean hota hai, aur ye boolean output conditions ke saath milkar program ko intelligent banata hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Eligibility systems, result portals, stock alerts, attendance systems aur admission filters me relational operators values ko compare karne ke liye use hote hain.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 2: Marks ko rules, limits aur targets ke saath compare karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Subject Pass Check</h3><p>Is example me ek subject ke marks ko passing rule se compare kiya gaya hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>subject_marks = 34
passing_marks = 35
is_pass = subject_marks &gt;= passing_marks
print(&quot;Subject Marks:&quot;, subject_marks)
print(&quot;Pass Status:&quot;, is_pass)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Subject Marks: 34
Pass Status: False</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>subject_marks = 34</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>passing_marks = 35</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>is_pass = subject_marks &gt;= passing_marks</code></td><td>Is line me comparison ya logical expression evaluate ho raha hai. Python right side condition solve karta hai aur result True ya False deta hai. Phir ye boolean result left side variable me store hota hai. Student project me pass/fail, scholarship, promotion, attendance aur validation decisions ke liye aise expressions use hote hain. Ye line program ko decision-ready data deti hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Subject Marks:&quot;, subject_marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>5</td><td><code>print(&quot;Pass Status:&quot;, is_pass)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Top Performer Benchmark Check</h3><p>Is example me check karenge ki student top performer category me aata hai ya nahi.</p>
<div class="run-loc">Python Code</div>
<pre><code>percentage = 86
topper_benchmark = 85
is_top_performer = percentage &gt;= topper_benchmark
print(&quot;Percentage:&quot;, percentage)
print(&quot;Top Performer:&quot;, is_top_performer)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Percentage: 86
Top Performer: True</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>percentage = 86</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>topper_benchmark = 85</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>is_top_performer = percentage &gt;= topper_benchmark</code></td><td>Is line me comparison ya logical expression evaluate ho raha hai. Python right side condition solve karta hai aur result True ya False deta hai. Phir ye boolean result left side variable me store hota hai. Student project me pass/fail, scholarship, promotion, attendance aur validation decisions ke liye aise expressions use hote hain. Ye line program ko decision-ready data deti hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Percentage:&quot;, percentage)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>5</td><td><code>print(&quot;Top Performer:&quot;, is_top_performer)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="logical" class="topic">3. Logical Operators</h2>
<p>Logical operators multiple conditions ko combine karte hain. Python me and, or aur not logical operators hote hain.</p>
<p>Student result project me ek decision sirf ek condition se nahi banta. Scholarship ke liye percentage high bhi honi chahiye aur attendance bhi good honi chahiye. Promotion ke liye overall percentage pass honi chahiye aur koi subject fail nahi hona chahiye.</p>
<p>and tab True hota hai jab dono conditions True hon. or tab True hota hai jab at least ek condition True ho. not result ko reverse karta hai. Ye operators project logic ko real-world jaisa banate hain.</p>
<div class="box use"><span class="tag">Real World Use</span>Scholarship checks, placement eligibility, login access, discount eligibility aur form validation me logical operators multiple conditions ko combine karte hain.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 3: Multiple result rules ko ek saath combine karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Scholarship Eligibility Check</h3><p>Is example me percentage aur attendance dono check ho rahe hain. Dono rules satisfy honge tabhi scholarship milegi.</p>
<div class="run-loc">Python Code</div>
<pre><code>percentage = 86
attendance = 82
scholarship_eligible = percentage &gt;= 85 and attendance &gt;= 75
print(&quot;Percentage:&quot;, percentage)
print(&quot;Attendance:&quot;, attendance)
print(&quot;Scholarship Eligible:&quot;, scholarship_eligible)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Percentage: 86
Attendance: 82
Scholarship Eligible: True</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>percentage = 86</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>attendance = 82</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>scholarship_eligible = percentage &gt;= 85 and attendance &gt;= 75</code></td><td>Is line me comparison ya logical expression evaluate ho raha hai. Python right side condition solve karta hai aur result True ya False deta hai. Phir ye boolean result left side variable me store hota hai. Student project me pass/fail, scholarship, promotion, attendance aur validation decisions ke liye aise expressions use hote hain. Ye line program ko decision-ready data deti hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Percentage:&quot;, percentage)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>5</td><td><code>print(&quot;Attendance:&quot;, attendance)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>6</td><td><code>print(&quot;Scholarship Eligible:&quot;, scholarship_eligible)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Promotion Eligibility Check</h3><p>Is example me student promote tab hoga jab percentage pass ho aur failed subjects zero hon.</p>
<div class="run-loc">Python Code</div>
<pre><code>percentage = 62
failed_subjects = 0
promoted = percentage &gt;= 35 and failed_subjects == 0
print(&quot;Failed Subjects:&quot;, failed_subjects)
print(&quot;Promoted:&quot;, promoted)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Failed Subjects: 0
Promoted: True</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>percentage = 62</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>failed_subjects = 0</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>promoted = percentage &gt;= 35 and failed_subjects == 0</code></td><td>Is line me comparison ya logical expression evaluate ho raha hai. Python right side condition solve karta hai aur result True ya False deta hai. Phir ye boolean result left side variable me store hota hai. Student project me pass/fail, scholarship, promotion, attendance aur validation decisions ke liye aise expressions use hote hain. Ye line program ko decision-ready data deti hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Failed Subjects:&quot;, failed_subjects)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>5</td><td><code>print(&quot;Promoted:&quot;, promoted)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="assignment" class="topic">4. Assignment Operators</h2>
<p>Assignment operators variables me value store karne aur existing value update karne ke liye use hote hain. Basic assignment operator = hota hai.</p>
<p>Student project me student name, roll number, marks list, total marks, percentage aur grade sab assignment se store honge. Jab hum running total banate hain, tab shortcut assignment operator += bahut useful hota hai.</p>
<p>total = total + marks ko short me total += marks likh sakte hain. Ye code ko clean, short aur professional banata hai, especially loops ke andar.</p>
<div class="box use"><span class="tag">Real World Use</span>Score counters, wallet balance, stock update, game points, cart totals aur marks calculators me assignment operators values ko update karte hain.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 4: Project values ko store aur update karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Running Total with Assignment Operator</h3><p>Is example me har subject ke marks total variable me step by step add ho rahe hain.</p>
<div class="run-loc">Python Code</div>
<pre><code>total_marks = 0
maths = 88
total_marks += maths
english = 76
total_marks += english
science = 91
total_marks += science
print(&quot;Running Total:&quot;, total_marks)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Running Total: 255</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>total_marks = 0</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>maths = 88</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>total_marks += maths</code></td><td>Ye shortcut assignment operator wali line hai. <code>+=</code> ka matlab hota hai old value me new value add karke result same variable me store karna. Isse running total, counters aur updates clean way me hote hain. Student project me total marks ya failed subjects count update karne ke liye ye pattern useful hai. Ye long syntax ko short aur readable banata hai.</td></tr>
<tr><td>4</td><td><code>english = 76</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>5</td><td><code>total_marks += english</code></td><td>Ye shortcut assignment operator wali line hai. <code>+=</code> ka matlab hota hai old value me new value add karke result same variable me store karna. Isse running total, counters aur updates clean way me hote hain. Student project me total marks ya failed subjects count update karne ke liye ye pattern useful hai. Ye long syntax ko short aur readable banata hai.</td></tr>
<tr><td>6</td><td><code>science = 91</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>7</td><td><code>total_marks += science</code></td><td>Ye shortcut assignment operator wali line hai. <code>+=</code> ka matlab hota hai old value me new value add karke result same variable me store karna. Isse running total, counters aur updates clean way me hote hain. Student project me total marks ya failed subjects count update karne ke liye ye pattern useful hai. Ye long syntax ko short aur readable banata hai.</td></tr>
<tr><td>8</td><td><code>print(&quot;Running Total:&quot;, total_marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Bonus Marks Update</h3><p>Is example me internal assessment ke bonus marks final marks me add ho rahe hain.</p>
<div class="run-loc">Python Code</div>
<pre><code>computer_marks = 95
bonus_marks = 3
computer_marks += bonus_marks
print(&quot;Updated Computer Marks:&quot;, computer_marks)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Updated Computer Marks: 98</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>computer_marks = 95</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>bonus_marks = 3</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>computer_marks += bonus_marks</code></td><td>Ye shortcut assignment operator wali line hai. <code>+=</code> ka matlab hota hai old value me new value add karke result same variable me store karna. Isse running total, counters aur updates clean way me hote hain. Student project me total marks ya failed subjects count update karne ke liye ye pattern useful hai. Ye long syntax ko short aur readable banata hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Updated Computer Marks:&quot;, computer_marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="membership" class="topic">5. Membership Operators</h2>
<p>Membership operators check karte hain ki koi value kisi collection ke andar present hai ya nahi. Python me in aur not in membership operators hote hain.</p>
<p>Student Marks Management System me user koi subject ya menu option enter karega. Program ko check karna hoga ki entered value allowed list me hai ya nahi. Is validation se wrong data avoid hota hai.</p>
<p>in True deta hai agar value list/string/tuple me milti hai. not in True deta hai agar value collection me nahi milti. Ye operators readable validation ke liye best hain.</p>
<div class="box use"><span class="tag">Real World Use</span>Search systems, menu validation, course availability, grade validation, username blacklist aur keyword detection me membership operators use hote hain.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 5: Valid subject, valid grade aur valid option check karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Subject Validation</h3><p>Is example me check hoga ki entered subject allowed subject list me hai ya nahi.</p>
<div class="run-loc">Python Code</div>
<pre><code>subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;, &quot;Computer&quot;, &quot;Hindi&quot;]
entered_subject = &quot;Computer&quot;
is_valid_subject = entered_subject in subjects
print(&quot;Entered Subject:&quot;, entered_subject)
print(&quot;Valid Subject:&quot;, is_valid_subject)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Entered Subject: Computer
Valid Subject: True</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;, &quot;Computer&quot;, &quot;Hindi&quot;]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>entered_subject = &quot;Computer&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>is_valid_subject = entered_subject in subjects</code></td><td>Is line me membership operator <code>in</code> use ho raha hai. Python check karta hai ki left side wali value right side collection ke andar present hai ya nahi. Agar value milti hai to True, warna False result aata hai. Student project me subject validation, absent student check ya menu option validation ke liye ye useful hai. Result variable me store ho kar later decision me use ho sakta hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Entered Subject:&quot;, entered_subject)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>5</td><td><code>print(&quot;Valid Subject:&quot;, is_valid_subject)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Absent Student Check</h3><p>Is example me check karenge ki roll number absent list me present hai ya nahi.</p>
<div class="run-loc">Python Code</div>
<pre><code>absent_roll_numbers = [104, 109, 115]
student_roll = 109
is_absent = student_roll in absent_roll_numbers
print(&quot;Roll Number:&quot;, student_roll)
print(&quot;Absent:&quot;, is_absent)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Roll Number: 109
Absent: True</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>absent_roll_numbers = [104, 109, 115]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>student_roll = 109</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>is_absent = student_roll in absent_roll_numbers</code></td><td>Is line me membership operator <code>in</code> use ho raha hai. Python check karta hai ki left side wali value right side collection ke andar present hai ya nahi. Agar value milti hai to True, warna False result aata hai. Student project me subject validation, absent student check ya menu option validation ke liye ye useful hai. Result variable me store ho kar later decision me use ho sakta hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Roll Number:&quot;, student_roll)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>5</td><td><code>print(&quot;Absent:&quot;, is_absent)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="identity" class="topic">6. Identity Operators</h2>
<p>Identity operators check karte hain ki variable exactly same object ko refer kar raha hai ya nahi. Python me is aur is not identity operators hote hain.</p>
<p>Beginners ke liye iska sabse practical use None check hai. None ka matlab hota hai value abhi available nahi hai. Student project me optional remark, grade, report path ya input value missing ho sakti hai.</p>
<p>None check ke liye best style value is None aur value is not None hota hai. Ye code ko safe banata hai aur missing data ke errors avoid karta hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Form validation, database records, optional remarks, missing profile data aur default settings me identity operators mostly None check ke liye use hote hain.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 6: Missing data ko safely handle karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Optional Remark Missing Check</h3><p>Is example me check hoga ki teacher remark available hai ya missing.</p>
<div class="run-loc">Python Code</div>
<pre><code>teacher_remark = None
remark_missing = teacher_remark is None
print(&quot;Remark Missing:&quot;, remark_missing)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Remark Missing: True</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>teacher_remark = None</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>remark_missing = teacher_remark is None</code></td><td>Is line me identity operator <code>is</code> ya <code>is not</code> use ho raha hai. Python check karta hai ki variable exactly <code>None</code> hai ya None nahi hai. None ka matlab hota hai value abhi available nahi hai. Student project me optional remark, grade ya missing input ko safely check karne ke liye ye important hai. Ye missing data ke errors avoid karta hai.</td></tr>
<tr><td>3</td><td><code>print(&quot;Remark Missing:&quot;, remark_missing)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Grade Generated Check</h3><p>Is example me check hoga ki grade generate ho chuka hai ya nahi.</p>
<div class="run-loc">Python Code</div>
<pre><code>grade = &quot;A&quot;
grade_generated = grade is not None
print(&quot;Grade:&quot;, grade)
print(&quot;Grade Generated:&quot;, grade_generated)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Grade: A
Grade Generated: True</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>grade = &quot;A&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>grade_generated = grade is not None</code></td><td>Is line me identity operator <code>is</code> ya <code>is not</code> use ho raha hai. Python check karta hai ki variable exactly <code>None</code> hai ya None nahi hai. None ka matlab hota hai value abhi available nahi hai. Student project me optional remark, grade ya missing input ko safely check karne ke liye ye important hai. Ye missing data ke errors avoid karta hai.</td></tr>
<tr><td>3</td><td><code>print(&quot;Grade:&quot;, grade)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Grade Generated:&quot;, grade_generated)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="precedence" class="topic">7. Operator Precedence</h2>
<p>Operator precedence batata hai ki expression me kaunsa operator pehle solve hoga. Python multiplication aur division ko addition/subtraction se pehle solve karta hai.</p>
<p>Student project me percentage, weighted score aur final report formulas me precedence important hai. Agar formula wrong order me solve hua to output wrong aa sakta hai.</p>
<p>Brackets use karke hum formula ka order clear kar sakte hain. Beginners ke liye recommendation hai ki complex formulas me brackets zaroor use karein.</p>
<div class="box use"><span class="tag">Real World Use</span>Percentage formula, weighted score, discount calculation, tax calculation aur billing logic me precedence result ko correct ya wrong bana sakta hai.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 7: Formulas ko correct order me solve karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Correct Percentage Formula</h3><p>Is example me brackets ka use karke percentage formula clear banaya gaya hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>total_marks = 430
maximum_marks = 500
percentage = (total_marks / maximum_marks) * 100
print(&quot;Percentage:&quot;, percentage)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Percentage: 86.0</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>total_marks = 430</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>maximum_marks = 500</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>percentage = (total_marks / maximum_marks) * 100</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Percentage:&quot;, percentage)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Weighted Final Score</h3><p>Is example me theory aur practical marks ko weightage ke saath combine kiya gaya hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>theory_marks = 78
practical_marks = 92
final_score = (theory_marks * 0.70) + (practical_marks * 0.30)
print(&quot;Final Weighted Score:&quot;, final_score)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Final Weighted Score: 82.2</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>theory_marks = 78</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>practical_marks = 92</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>final_score = (theory_marks * 0.70) + (practical_marks * 0.30)</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Final Weighted Score:&quot;, final_score)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="expression" class="topic">8. Expression Evaluation</h2>
<p>Expression values, variables, operators aur function calls ka combination hota hai jise Python solve karke final value banata hai.</p>
<p>Python assignment line me pehle right side expression evaluate karta hai, phir result left side variable me store karta hai. Ye rule project ke har calculation me apply hota hai.</p>
<p>Student project me total, percentage, grade message, result status aur report line sab expressions se ban sakte hain.</p>
<div class="box use"><span class="tag">Real World Use</span>Every real program uses expressions for formulas, messages, status generation, totals, averages and comparisons.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 8: Right side logic solve karke final report values banana. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Result Summary Message Expression</h3><p>Is example me variables aur text combine karke readable result message banega.</p>
<div class="run-loc">Python Code</div>
<pre><code>student_name = &quot;Rahul&quot;
percentage = 86.0
result_message = student_name + &quot; scored &quot; + str(percentage) + &quot;%&quot;
print(result_message)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Rahul scored 86.0%</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>student_name = &quot;Rahul&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>percentage = 86.0</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>result_message = student_name + &quot; scored &quot; + str(percentage) + &quot;%&quot;</code></td><td>Ye string expression line hai. Yahan student name, normal text, percentage aur percent symbol ko combine karke ek readable message banaya ja raha hai. <code>str(percentage)</code> number ko string me convert karta hai taki text ke saath join ho sake. <code>+</code> yahan text concatenation ke liye use ho raha hai. Student project me final report messages banane ke liye ye useful pattern hai.</td></tr>
<tr><td>4</td><td><code>print(result_message)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Performance Index Expression</h3><p>Is example me percentage aur attendance ko combine karke performance index banaya gaya hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>percentage = 86
attendance = 82
performance_index = (percentage * 0.80) + (attendance * 0.20)
print(&quot;Performance Index:&quot;, performance_index)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Performance Index: 85.2</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>percentage = 86</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>attendance = 82</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>performance_index = (percentage * 0.80) + (attendance * 0.20)</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>4</td><td><code>print(&quot;Performance Index:&quot;, performance_index)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="if" class="topic">9. if Statement</h2>
<p>if statement decision making ka first step hai. Agar condition True hoti hai to if block ke andar ka code run hota hai. Agar condition False hoti hai to block skip ho jata hai.</p>
<p>Student project me if statement high score appreciation, low marks warning, missing data alert ya perfect attendance message ke liye use ho sakta hai.</p>
<p>Python me if ke baad condition aur colon : lagta hai. Uske andar jo code run karna hai usko indentation ke saath likhna padta hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Alerts, warnings, appreciation messages, notifications aur validation messages me if statement use hota hai.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 9: Single condition true hone par action lena. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - High Performer Message</h3><p>Is example me high percentage hone par appreciation message print hoga.</p>
<div class="run-loc">Python Code</div>
<pre><code>percentage = 86
if percentage &gt;= 85:
    print(&quot;Excellent result, keep it up!&quot;)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Excellent result, keep it up!</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>percentage = 86</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>if percentage &gt;= 85:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>3</td><td><code>    print(&quot;Excellent result, keep it up!&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Improvement Alert</h3><p>Is example me low subject marks hone par improvement message print hoga.</p>
<div class="run-loc">Python Code</div>
<pre><code>science_marks = 31
if science_marks &lt; 35:
    print(&quot;Science needs improvement before final report&quot;)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Science needs improvement before final report</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>science_marks = 31</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>if science_marks &lt; 35:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>3</td><td><code>    print(&quot;Science needs improvement before final report&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="ifelse" class="topic">10. if-else Statement</h2>
<p>if-else statement tab use hota hai jab hume two possible paths me se ek choose karna hota hai. Condition True hui to if block chalega, warna else block chalega.</p>
<p>Student project me pass/fail, exam allowed/not allowed, subject valid/invalid jaise outputs if-else se easily ban sakte hain.</p>
<p>else ke saath condition nahi likhi jaati, kyunki else ka matlab hota hai remaining case. Ye decision ko complete banata hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Pass/fail, allowed/not allowed, available/not available, valid/invalid jaise decisions me if-else use hota hai.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 10: Two-way result decision banana. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Subject Result Decision</h3><p>Is example me subject marks ke basis par Pass ya Fail output aayega.</p>
<div class="run-loc">Python Code</div>
<pre><code>marks = 42
if marks &gt;= 35:
    print(&quot;Subject Result: Pass&quot;)
else:
    print(&quot;Subject Result: Fail&quot;)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Subject Result: Pass</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>marks = 42</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>if marks &gt;= 35:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>3</td><td><code>    print(&quot;Subject Result: Pass&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>4</td><td><code>else:</code></td><td>Ye <code>else</code> block hai. Jab upar wali if/elif conditions me se koi bhi True nahi hoti, tab else run hota hai. else ke saath condition nahi likhte kyunki ye remaining/default case handle karta hai. Student project me else Fail grade, invalid input ya default output dene ke liye useful hai. Ye decision chain ko complete banata hai.</td></tr>
<tr><td>5</td><td><code>    print(&quot;Subject Result: Fail&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Attendance Exam Permission</h3><p>Is example me attendance ke basis par exam permission decide hogi.</p>
<div class="run-loc">Python Code</div>
<pre><code>attendance = 68
if attendance &gt;= 75:
    print(&quot;Exam Permission: Allowed&quot;)
else:
    print(&quot;Exam Permission: Not Allowed&quot;)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Exam Permission: Not Allowed</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>attendance = 68</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>if attendance &gt;= 75:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>3</td><td><code>    print(&quot;Exam Permission: Allowed&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>4</td><td><code>else:</code></td><td>Ye <code>else</code> block hai. Jab upar wali if/elif conditions me se koi bhi True nahi hoti, tab else run hota hai. else ke saath condition nahi likhte kyunki ye remaining/default case handle karta hai. Student project me else Fail grade, invalid input ya default output dene ke liye useful hai. Ye decision chain ko complete banata hai.</td></tr>
<tr><td>5</td><td><code>    print(&quot;Exam Permission: Not Allowed&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="ifelif" class="topic">11. if-elif-else</h2>
<p>if-elif-else multiple conditions check karne ke liye use hota hai. Jab result sirf two cases me nahi balki multiple categories me divide ho, tab ye structure useful hota hai.</p>
<p>Student Marks Management System me grade assignment ke liye if-elif-else main logic hai. Percentage ke basis par A+, A, B, C ya Fail decide hoga.</p>
<p>Python conditions top to bottom check karta hai. Jo first condition True hoti hai, uska block run hota hai aur baaki conditions skip ho jati hain.</p>
<div class="box use"><span class="tag">Real World Use</span>Grade systems, rating systems, performance bands, salary slabs aur ticket priority systems me if-elif-else use hota hai.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 11: Multiple grade categories handle karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Grade Generator</h3><p>Is example me percentage ke basis par grade generate hoga.</p>
<div class="run-loc">Python Code</div>
<pre><code>percentage = 86
if percentage &gt;= 90:
    grade = &quot;A+&quot;
elif percentage &gt;= 75:
    grade = &quot;A&quot;
elif percentage &gt;= 60:
    grade = &quot;B&quot;
elif percentage &gt;= 35:
    grade = &quot;C&quot;
else:
    grade = &quot;Fail&quot;
print(&quot;Grade:&quot;, grade)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Grade: A</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>percentage = 86</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>if percentage &gt;= 90:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>3</td><td><code>    grade = &quot;A+&quot;</code></td><td>Ye grade assignment line hai. Indentation batata hai ki ye line upar wali condition True hone par hi run hogi. Right side <code>&quot;A+&quot;</code> ek string value hai jo top grade ko represent karti hai. Ye value <code>grade</code> variable me store hoti hai. Student result project me aisi line final report ke liye grade category set karti hai.</td></tr>
<tr><td>4</td><td><code>elif percentage &gt;= 75:</code></td><td>Ye <code>elif</code> line hai, jiska meaning hota hai else-if. Agar upar wali condition False ho jaati hai tab Python is condition ko check karta hai. Grade system me multiple percentage ranges handle karne ke liye elif useful hota hai. Python top se bottom conditions check karta hai aur first True condition ka block run karta hai. Isse A+, A, B, C aur Fail jaise categories clean way me manage hoti hain.</td></tr>
<tr><td>5</td><td><code>    grade = &quot;A&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>6</td><td><code>elif percentage &gt;= 60:</code></td><td>Ye <code>elif</code> line hai, jiska meaning hota hai else-if. Agar upar wali condition False ho jaati hai tab Python is condition ko check karta hai. Grade system me multiple percentage ranges handle karne ke liye elif useful hota hai. Python top se bottom conditions check karta hai aur first True condition ka block run karta hai. Isse A+, A, B, C aur Fail jaise categories clean way me manage hoti hain.</td></tr>
<tr><td>7</td><td><code>    grade = &quot;B&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>8</td><td><code>elif percentage &gt;= 35:</code></td><td>Ye <code>elif</code> line hai, jiska meaning hota hai else-if. Agar upar wali condition False ho jaati hai tab Python is condition ko check karta hai. Grade system me multiple percentage ranges handle karne ke liye elif useful hota hai. Python top se bottom conditions check karta hai aur first True condition ka block run karta hai. Isse A+, A, B, C aur Fail jaise categories clean way me manage hoti hain.</td></tr>
<tr><td>9</td><td><code>    grade = &quot;C&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>10</td><td><code>else:</code></td><td>Ye <code>else</code> block hai. Jab upar wali if/elif conditions me se koi bhi True nahi hoti, tab else run hota hai. else ke saath condition nahi likhte kyunki ye remaining/default case handle karta hai. Student project me else Fail grade, invalid input ya default output dene ke liye useful hai. Ye decision chain ko complete banata hai.</td></tr>
<tr><td>11</td><td><code>    grade = &quot;Fail&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>12</td><td><code>print(&quot;Grade:&quot;, grade)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Attendance Category</h3><p>Is example me attendance ko category me convert kiya gaya hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>attendance = 82
if attendance &gt;= 90:
    category = &quot;Excellent Attendance&quot;
elif attendance &gt;= 75:
    category = &quot;Good Attendance&quot;
elif attendance &gt;= 60:
    category = &quot;Warning Zone&quot;
else:
    category = &quot;Critical Attendance&quot;
print(&quot;Attendance Category:&quot;, category)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Attendance Category: Good Attendance</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>attendance = 82</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>if attendance &gt;= 90:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>3</td><td><code>    category = &quot;Excellent Attendance&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>4</td><td><code>elif attendance &gt;= 75:</code></td><td>Ye <code>elif</code> line hai, jiska meaning hota hai else-if. Agar upar wali condition False ho jaati hai tab Python is condition ko check karta hai. Grade system me multiple percentage ranges handle karne ke liye elif useful hota hai. Python top se bottom conditions check karta hai aur first True condition ka block run karta hai. Isse A+, A, B, C aur Fail jaise categories clean way me manage hoti hain.</td></tr>
<tr><td>5</td><td><code>    category = &quot;Good Attendance&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>6</td><td><code>elif attendance &gt;= 60:</code></td><td>Ye <code>elif</code> line hai, jiska meaning hota hai else-if. Agar upar wali condition False ho jaati hai tab Python is condition ko check karta hai. Grade system me multiple percentage ranges handle karne ke liye elif useful hota hai. Python top se bottom conditions check karta hai aur first True condition ka block run karta hai. Isse A+, A, B, C aur Fail jaise categories clean way me manage hoti hain.</td></tr>
<tr><td>7</td><td><code>    category = &quot;Warning Zone&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>8</td><td><code>else:</code></td><td>Ye <code>else</code> block hai. Jab upar wali if/elif conditions me se koi bhi True nahi hoti, tab else run hota hai. else ke saath condition nahi likhte kyunki ye remaining/default case handle karta hai. Student project me else Fail grade, invalid input ya default output dene ke liye useful hai. Ye decision chain ko complete banata hai.</td></tr>
<tr><td>9</td><td><code>    category = &quot;Critical Attendance&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>10</td><td><code>print(&quot;Attendance Category:&quot;, category)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="nested" class="topic">12. Nested Conditions</h2>
<p>Nested condition ka matlab hota hai ek if ke andar doosra if. Jab pehle main condition check karni ho aur uske baad extra detail condition check karni ho, tab nested conditions useful hoti hain.</p>
<p>Student project me pehle check kar sakte hain ki marks valid hain ya nahi. Agar valid hain, tab pass/fail ya grade decide kar sakte hain. Isse program invalid data par wrong result generate nahi karta.</p>
<p>Nested conditions powerful hoti hain, lekin indentation clear rakhna bahut important hai. Har inner block ko proper spaces ke saath likhna hota hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Admission systems, result systems, loan approval, order validation aur access control me nested conditions use hote hain.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 12: Ek decision ke andar second decision lagana. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Validate Marks then Decide Result</h3><p>Is example me pehle marks valid range me hain ya nahi check hoga, phir result decide hoga.</p>
<div class="run-loc">Python Code</div>
<pre><code>marks = 91
if marks &gt;= 0 and marks &lt;= 100:
    if marks &gt;= 35:
        print(&quot;Valid Marks and Student Pass&quot;)
    else:
        print(&quot;Valid Marks but Student Fail&quot;)
else:
    print(&quot;Invalid Marks Entered&quot;)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Valid Marks and Student Pass</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>marks = 91</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>if marks &gt;= 0 and marks &lt;= 100:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>3</td><td><code>    if marks &gt;= 35:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>4</td><td><code>        print(&quot;Valid Marks and Student Pass&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>5</td><td><code>    else:</code></td><td>Ye <code>else</code> block hai. Jab upar wali if/elif conditions me se koi bhi True nahi hoti, tab else run hota hai. else ke saath condition nahi likhte kyunki ye remaining/default case handle karta hai. Student project me else Fail grade, invalid input ya default output dene ke liye useful hai. Ye decision chain ko complete banata hai.</td></tr>
<tr><td>6</td><td><code>        print(&quot;Valid Marks but Student Fail&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>7</td><td><code>else:</code></td><td>Ye <code>else</code> block hai. Jab upar wali if/elif conditions me se koi bhi True nahi hoti, tab else run hota hai. else ke saath condition nahi likhte kyunki ye remaining/default case handle karta hai. Student project me else Fail grade, invalid input ya default output dene ke liye useful hai. Ye decision chain ko complete banata hai.</td></tr>
<tr><td>8</td><td><code>    print(&quot;Invalid Marks Entered&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Pass Student Award Check</h3><p>Is example me pehle student pass hai ya nahi check hoga, phir award eligibility check hogi.</p>
<div class="run-loc">Python Code</div>
<pre><code>percentage = 86
if percentage &gt;= 35:
    print(&quot;Result: Pass&quot;)
    if percentage &gt;= 85:
        print(&quot;Award: Academic Star&quot;)
else:
    print(&quot;Result: Fail&quot;)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Result: Pass
Award: Academic Star</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>percentage = 86</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>if percentage &gt;= 35:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>3</td><td><code>    print(&quot;Result: Pass&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>4</td><td><code>    if percentage &gt;= 85:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>5</td><td><code>        print(&quot;Award: Academic Star&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>6</td><td><code>else:</code></td><td>Ye <code>else</code> block hai. Jab upar wali if/elif conditions me se koi bhi True nahi hoti, tab else run hota hai. else ke saath condition nahi likhte kyunki ye remaining/default case handle karta hai. Student project me else Fail grade, invalid input ya default output dene ke liye useful hai. Ye decision chain ko complete banata hai.</td></tr>
<tr><td>7</td><td><code>    print(&quot;Result: Fail&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="loops" class="topic">13. Introduction to Loops</h2>
<p>Loops repeated work ko automate karte hain. Agar same type ka kaam baar-baar karna ho, to repeated lines likhne ke bajay loop use karte hain.</p>
<p>Student Marks Management System me multiple subjects ke marks process karna, total calculate karna, report rows print karna aur fail subjects count karna loops se easy hota hai.</p>
<p>Python me for loop sequence ke items par repeat karta hai, aur while loop condition true hone tak repeat karta hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Report generation, data processing, email sending, attendance marking, billing rows aur dashboards me loops repeated work automate karte hain.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 13: Repeated marks processing automate karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Print Marks Report Rows</h3><p>Is example me loop marks list ke har item ko report row ki tarah print karega.</p>
<div class="run-loc">Python Code</div>
<pre><code>marks_list = [88, 76, 91, 95, 80]
for marks in marks_list:
    print(&quot;Subject Marks:&quot;, marks)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Subject Marks: 88
Subject Marks: 76
Subject Marks: 91
Subject Marks: 95
Subject Marks: 80</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>marks_list = [88, 76, 91, 95, 80]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>for marks in marks_list:</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>3</td><td><code>    print(&quot;Subject Marks:&quot;, marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Count Passed Subjects</h3><p>Is example me loop count karega ki kitne subjects pass hain.</p>
<div class="run-loc">Python Code</div>
<pre><code>marks_list = [88, 31, 91, 95, 80]
passed_subjects = 0
for marks in marks_list:
    if marks &gt;= 35:
        passed_subjects += 1
print(&quot;Passed Subjects:&quot;, passed_subjects)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Passed Subjects: 4</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>marks_list = [88, 31, 91, 95, 80]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>passed_subjects = 0</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>for marks in marks_list:</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>4</td><td><code>    if marks &gt;= 35:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>5</td><td><code>        passed_subjects += 1</code></td><td>Ye shortcut assignment operator wali line hai. <code>+=</code> ka matlab hota hai old value me new value add karke result same variable me store karna. Isse running total, counters aur updates clean way me hote hain. Student project me total marks ya failed subjects count update karne ke liye ye pattern useful hai. Ye long syntax ko short aur readable banata hai.</td></tr>
<tr><td>6</td><td><code>print(&quot;Passed Subjects:&quot;, passed_subjects)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="forloop" class="topic">14. for Loop</h2>
<p>for loop sequence ke har item par one by one repeat hota hai. Sequence list, string, tuple ya range ho sakta hai.</p>
<p>Student project me subject names aur marks list ko pair karke report print karne ke liye for loop very useful hai. Ye manual repeated print lines ko avoid karta hai.</p>
<p>for loop ka syntax hota hai: for variable in sequence. Variable har iteration me current item ko hold karta hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Lists, CSV rows, database records, report lines aur dashboard data processing me for loop daily use hota hai.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 14: Subject list par one-by-one kaam karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Subject-wise Report using for Loop</h3><p>Is example me subjects aur marks ko together print kiya gaya hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;]
marks_list = [88, 76, 91]
for index in range(len(subjects)):
    print(subjects[index], &quot;=&quot;, marks_list[index])</code></pre>
<div class="run-loc">Output</div>
<pre><code>Maths = 88
English = 76
Science = 91</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>marks_list = [88, 76, 91]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>for index in range(len(subjects)):</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>4</td><td><code>    print(subjects[index], &quot;=&quot;, marks_list[index])</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Total Marks using for Loop</h3><p>Is example me for loop list ke marks add karke total banayega.</p>
<div class="run-loc">Python Code</div>
<pre><code>marks_list = [88, 76, 91, 95, 80]
total_marks = 0
for marks in marks_list:
    total_marks += marks
print(&quot;Total Marks:&quot;, total_marks)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Total Marks: 430</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>marks_list = [88, 76, 91, 95, 80]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>total_marks = 0</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>for marks in marks_list:</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>4</td><td><code>    total_marks += marks</code></td><td>Ye shortcut assignment operator wali line hai. <code>+=</code> ka matlab hota hai old value me new value add karke result same variable me store karna. Isse running total, counters aur updates clean way me hote hain. Student project me total marks ya failed subjects count update karne ke liye ye pattern useful hai. Ye long syntax ko short aur readable banata hai.</td></tr>
<tr><td>5</td><td><code>print(&quot;Total Marks:&quot;, total_marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="whileloop" class="topic">15. while Loop</h2>
<p>while loop tab tak repeat hota hai jab tak condition True rahti hai. Iska use tab hota hai jab repeat count fixed na ho ya condition ke basis par loop chalana ho.</p>
<p>Student project me while loop marks validation, menu system, retry input aur report options ke liye use ho sakta hai.</p>
<p>while loop me condition update karna zaroori hai. Agar condition kabhi False nahi hui to infinite loop ban sakta hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Menu systems, retry logic, OTP attempts, input validation aur background monitoring me while loop useful hota hai.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 15: Condition-based repeated input ya menu banana. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Marks Correction using while Loop</h3><p>Is example me invalid marks ko correct value se replace karne ka validation flow dikhaya gaya hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>marks = 105
while marks &gt; 100:
    print(&quot;Invalid marks found:&quot;, marks)
    marks = 95
print(&quot;Final Valid Marks:&quot;, marks)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Invalid marks found: 105
Final Valid Marks: 95</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>marks = 105</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>while marks &gt; 100:</code></td><td>Ye <code>while</code> loop line hai. while loop tab tak repeat hota hai jab tak condition True rahti hai. Is line me Python pehle condition check karta hai, phir indented block run karta hai. Student project me while loop validation, retry input ya menu system ke liye use ho sakta hai. Condition ko update karna important hota hai, warna loop infinite chal sakta hai.</td></tr>
<tr><td>3</td><td><code>    print(&quot;Invalid marks found:&quot;, marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>4</td><td><code>    marks = 95</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>5</td><td><code>print(&quot;Final Valid Marks:&quot;, marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Simple Report Menu Simulation</h3><p>Is example me menu option 3 aane tak loop run ho raha hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>option = 1
while option != 3:
    print(&quot;Showing menu option:&quot;, option)
    option += 1
print(&quot;Exit report menu&quot;)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Showing menu option: 1
Showing menu option: 2
Exit report menu</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>option = 1</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>while option != 3:</code></td><td>Ye <code>while</code> loop line hai. while loop tab tak repeat hota hai jab tak condition True rahti hai. Is line me Python pehle condition check karta hai, phir indented block run karta hai. Student project me while loop validation, retry input ya menu system ke liye use ho sakta hai. Condition ko update karna important hota hai, warna loop infinite chal sakta hai.</td></tr>
<tr><td>3</td><td><code>    print(&quot;Showing menu option:&quot;, option)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>4</td><td><code>    option += 1</code></td><td>Ye shortcut assignment operator wali line hai. <code>+=</code> ka matlab hota hai old value me new value add karke result same variable me store karna. Isse running total, counters aur updates clean way me hote hain. Student project me total marks ya failed subjects count update karne ke liye ye pattern useful hai. Ye long syntax ko short aur readable banata hai.</td></tr>
<tr><td>5</td><td><code>print(&quot;Exit report menu&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="breakcontinuepass" class="topic">16. break, continue, pass</h2>
<p>break, continue aur pass loop control statements hain. Ye loop ke normal flow ko control karte hain.</p>
<p>break loop ko turant stop karta hai. continue current iteration skip karta hai. pass kuch nahi karta, sirf placeholder hota hai.</p>
<p>Student project me break failing subject milte hi search stop karne ke liye, continue absent student ko skip karne ke liye, aur pass future feature placeholder ke liye use ho sakta hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Search systems, filtering invalid data, skipping absent records, stopping after match aur future placeholders me break/continue/pass useful hote hain.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 16: Loop ke flow ko smartly control karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Find First Failed Subject using break</h3><p>Is example me first failed subject milte hi loop stop ho jayega.</p>
<div class="run-loc">Python Code</div>
<pre><code>subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;, &quot;Computer&quot;]
marks_list = [88, 76, 31, 95]
for index in range(len(subjects)):
    if marks_list[index] &lt; 35:
        print(&quot;First Failed Subject:&quot;, subjects[index])
        break</code></pre>
<div class="run-loc">Output</div>
<pre><code>First Failed Subject: Science</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;, &quot;Computer&quot;]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>marks_list = [88, 76, 31, 95]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>for index in range(len(subjects)):</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>4</td><td><code>    if marks_list[index] &lt; 35:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>5</td><td><code>        print(&quot;First Failed Subject:&quot;, subjects[index])</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>6</td><td><code>        break</code></td><td><code>break</code> loop ko turant stop kar deta hai. Jab required result mil jaye, to loop ko aage chalane ki need nahi hoti. Student project me first failed subject milte hi search stop karne ke liye break useful hai. Isse extra iterations avoid hoti hain aur code efficient hota hai. break hamesha loop ke andar use hota hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Skip Absent Students using continue</h3><p>Is example me absent students ko skip karke sirf present students ka report print hoga.</p>
<div class="run-loc">Python Code</div>
<pre><code>students = [&quot;Aman&quot;, &quot;Riya&quot;, &quot;Kabir&quot;, &quot;Neha&quot;]
absent_students = [&quot;Kabir&quot;]
for student in students:
    if student in absent_students:
        continue
    print(&quot;Generate report for:&quot;, student)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Generate report for: Aman
Generate report for: Riya
Generate report for: Neha</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>students = [&quot;Aman&quot;, &quot;Riya&quot;, &quot;Kabir&quot;, &quot;Neha&quot;]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>absent_students = [&quot;Kabir&quot;]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>for student in students:</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>4</td><td><code>    if student in absent_students:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>5</td><td><code>        continue</code></td><td><code>continue</code> current iteration ko skip karta hai aur loop next item par chala jata hai. Agar koi student absent ho ya data invalid ho, to us record ko ignore karke next record process kar sakte hain. Student report project me absent students ko skip karne ke liye continue useful hai. Ye loop ko stop nahi karta, sirf current round skip karta hai.</td></tr>
<tr><td>6</td><td><code>    print(&quot;Generate report for:&quot;, student)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="range" class="topic">17. Range Function</h2>
<p>range() function numbers ka sequence generate karta hai. Ye mostly for loop ke saath use hota hai jab hume fixed number of times repeat karna ho.</p>
<p>Student project me 5 subjects ke marks input prompts, roll number list, report serial numbers aur rank positions generate karne ke liye range useful hai.</p>
<p>range(start, stop, step) format me stop value include nahi hoti. Example range(1, 6) 1 se 5 tak numbers generate karta hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Roll number generation, repeated input prompts, table rows, pagination, batch processing aur numbered reports me range function use hota hai.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 17: Fixed number of subjects, roll numbers aur report rows generate karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Generate Roll Numbers</h3><p>Is example me roll numbers 101 se 105 tak generate honge.</p>
<div class="run-loc">Python Code</div>
<pre><code>for roll_number in range(101, 106):
    print(&quot;Roll Number:&quot;, roll_number)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Roll Number: 101
Roll Number: 102
Roll Number: 103
Roll Number: 104
Roll Number: 105</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>for roll_number in range(101, 106):</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>2</td><td><code>    print(&quot;Roll Number:&quot;, roll_number)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Generate Subject Input Labels</h3><p>Is example me 5 subjects ke marks input labels automatically generate honge.</p>
<div class="run-loc">Python Code</div>
<pre><code>for subject_no in range(1, 6):
    print(&quot;Enter marks for Subject&quot;, subject_no)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Enter marks for Subject 1
Enter marks for Subject 2
Enter marks for Subject 3
Enter marks for Subject 4
Enter marks for Subject 5</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>for subject_no in range(1, 6):</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>2</td><td><code>    print(&quot;Enter marks for Subject&quot;, subject_no)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="patterns" class="topic">18. Pattern-Based Programs</h2>
<p>Pattern programs loops practice karne ka strong way hain. Isme rows aur columns ka concept clear hota hai.</p>
<p>Student Marks Management System me pattern directly grade calculate nahi karta, lekin report formatting, separator lines aur nested loop thinking ke liye helpful hai.</p>
<p>Pattern programs me outer loop usually rows control karta hai aur inner logic row ka content decide karta hai. Isse loop visualization strong hoti hai.</p>
<div class="box use"><span class="tag">Real World Use</span>Console reports, table borders, certificates, formatted receipts aur text dashboards me pattern thinking helpful hoti hai.</div>
<div class="box project"><span class="tag">Project Connection</span>Project Step 18: Nested loops aur report formatting practice karna. Is topic ke examples se mini project ka ek practical feature ready hota jayega.</div>
<h3 class="example-title">Example 1 - Report Separator Pattern</h3><p>Is example me report ke liye clean separator lines generate hongi.</p>
<div class="run-loc">Python Code</div>
<pre><code>for line in range(3):
    print(&quot;=&quot; * 30)</code></pre>
<div class="run-loc">Output</div>
<pre><code>==============================
==============================
==============================</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>for line in range(3):</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>2</td><td><code>    print(&quot;=&quot; * 30)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<h3 class="example-title">Example 2 - Rank Stars Pattern</h3><p>Is example me rank ke according stars print honge, jo report ko visually interesting banata hai.</p>
<div class="run-loc">Python Code</div>
<pre><code>for rank in range(1, 4):
    stars = &quot;*&quot; * rank
    print(&quot;Rank&quot;, rank, stars)</code></pre>
<div class="run-loc">Output</div>
<pre><code>Rank 1 *
Rank 2 **
Rank 3 ***</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>for rank in range(1, 4):</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>2</td><td><code>    stars = &quot;*&quot; * rank</code></td><td>Ye pattern-building line hai. Yahan <code>&quot;*&quot; * rank</code> ka matlab hai star symbol ko rank number ke according repeat karna. Agar rank 2 hai to two stars banenge. Result <code>stars</code> variable me store hota hai. Report formatting, rating display aur visual output practice ke liye ye line useful hai.</td></tr>
<tr><td>3</td><td><code>    print(&quot;Rank&quot;, rank, stars)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="project" class="topic">Complete Mini Project - Student Marks Management System</h2>
<p>Ab saare topics ko combine karke ek productive mini project banate hain. Is final project me arithmetic operators se total/percentage/average nikalenge, relational aur logical operators se promotion aur scholarship checks karenge, for loop se marks process karenge, if-elif-else se grade generate karenge, aur print statements se professional report display karenge.</p>
<div class="box project"><span class="tag">Project Purpose</span>Is project ka purpose ye dikhana hai ki Python ke basic topics alag-alag theory nahi hain. Ye sab milkar ek real result report system banate hain jo learner ke liye practical aur useful output generate karta hai.</div>
<div class="run-loc">Python Code</div>
<pre><code>student_name = &quot;Rahul&quot;
roll_number = 101
subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;, &quot;Computer&quot;, &quot;Hindi&quot;]
marks_list = [88, 76, 91, 95, 80]
attendance = 82

total_marks = 0
failed_subjects = 0

for marks in marks_list:
    total_marks += marks
    if marks &lt; 35:
        failed_subjects += 1

maximum_marks = len(subjects) * 100
percentage = (total_marks / maximum_marks) * 100
average_marks = total_marks / len(subjects)

if percentage &gt;= 90:
    grade = &quot;A+&quot;
elif percentage &gt;= 75:
    grade = &quot;A&quot;
elif percentage &gt;= 60:
    grade = &quot;B&quot;
elif percentage &gt;= 35:
    grade = &quot;C&quot;
else:
    grade = &quot;Fail&quot;

promoted = percentage &gt;= 35 and failed_subjects == 0
scholarship_eligible = percentage &gt;= 85 and attendance &gt;= 75

print(&quot;=&quot; * 35)
print(&quot;STUDENT RESULT REPORT&quot;)
print(&quot;=&quot; * 35)
print(&quot;Name:&quot;, student_name)
print(&quot;Roll Number:&quot;, roll_number)
print(&quot;Total Marks:&quot;, total_marks)
print(&quot;Percentage:&quot;, percentage)
print(&quot;Average Marks:&quot;, average_marks)
print(&quot;Grade:&quot;, grade)
print(&quot;Failed Subjects:&quot;, failed_subjects)
print(&quot;Promoted:&quot;, promoted)
print(&quot;Scholarship Eligible:&quot;, scholarship_eligible)</code></pre>
<div class="run-loc">Output</div>
<pre><code>===================================
STUDENT RESULT REPORT
===================================
Name: Rahul
Roll Number: 101
Total Marks: 430
Percentage: 86.0
Average Marks: 86.0
Grade: A
Failed Subjects: 0
Promoted: True
Scholarship Eligible: True</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>student_name = &quot;Rahul&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>2</td><td><code>roll_number = 101</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>3</td><td><code>subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;, &quot;Computer&quot;, &quot;Hindi&quot;]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>4</td><td><code>marks_list = [88, 76, 91, 95, 80]</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>5</td><td><code>attendance = 82</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>6</td><td><code>blank line</code></td><td>Ye blank line code ko readable banane ke liye use hui hai. Python is line ko ignore karta hai, lekin learner ke liye code sections clear ho jate hain. Isse input data, calculation logic, condition logic aur final output visually separate dikhte hain. Jab project bada hota hai to blank lines debugging aur explanation dono me help karti hain. Is line ka kaam program run karna nahi, code ko organized banana hai.</td></tr>
<tr><td>7</td><td><code>total_marks = 0</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>8</td><td><code>failed_subjects = 0</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>9</td><td><code>blank line</code></td><td>Ye blank line code ko readable banane ke liye use hui hai. Python is line ko ignore karta hai, lekin learner ke liye code sections clear ho jate hain. Isse input data, calculation logic, condition logic aur final output visually separate dikhte hain. Jab project bada hota hai to blank lines debugging aur explanation dono me help karti hain. Is line ka kaam program run karna nahi, code ko organized banana hai.</td></tr>
<tr><td>10</td><td><code>for marks in marks_list:</code></td><td>Ye <code>for</code> loop line hai. for loop kisi sequence, list ya range ke har item par one by one repeat hota hai. Loop variable current item ko temporarily hold karta hai. Student marks project me ye subject list ya marks list par repeat karke calculation/report generation automate karta hai. Colon <code>:</code> ke baad indented block har iteration me run hota hai.</td></tr>
<tr><td>11</td><td><code>    total_marks += marks</code></td><td>Ye shortcut assignment operator wali line hai. <code>+=</code> ka matlab hota hai old value me new value add karke result same variable me store karna. Isse running total, counters aur updates clean way me hote hain. Student project me total marks ya failed subjects count update karne ke liye ye pattern useful hai. Ye long syntax ko short aur readable banata hai.</td></tr>
<tr><td>12</td><td><code>    if marks &lt; 35:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>13</td><td><code>        failed_subjects += 1</code></td><td>Ye shortcut assignment operator wali line hai. <code>+=</code> ka matlab hota hai old value me new value add karke result same variable me store karna. Isse running total, counters aur updates clean way me hote hain. Student project me total marks ya failed subjects count update karne ke liye ye pattern useful hai. Ye long syntax ko short aur readable banata hai.</td></tr>
<tr><td>14</td><td><code>blank line</code></td><td>Ye blank line code ko readable banane ke liye use hui hai. Python is line ko ignore karta hai, lekin learner ke liye code sections clear ho jate hain. Isse input data, calculation logic, condition logic aur final output visually separate dikhte hain. Jab project bada hota hai to blank lines debugging aur explanation dono me help karti hain. Is line ka kaam program run karna nahi, code ko organized banana hai.</td></tr>
<tr><td>15</td><td><code>maximum_marks = len(subjects) * 100</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>16</td><td><code>percentage = (total_marks / maximum_marks) * 100</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>17</td><td><code>average_marks = total_marks / len(subjects)</code></td><td>Is line me calculation expression evaluate ho raha hai. Python pehle right side formula solve karta hai aur final result left side variable me store karta hai. Arithmetic operators total marks, maximum marks, percentage, average ya weighted score nikalne me help karte hain. Brackets formula order ko clear banate hain. Student project me ye line final report ke numerical values generate karti hai.</td></tr>
<tr><td>18</td><td><code>blank line</code></td><td>Ye blank line code ko readable banane ke liye use hui hai. Python is line ko ignore karta hai, lekin learner ke liye code sections clear ho jate hain. Isse input data, calculation logic, condition logic aur final output visually separate dikhte hain. Jab project bada hota hai to blank lines debugging aur explanation dono me help karti hain. Is line ka kaam program run karna nahi, code ko organized banana hai.</td></tr>
<tr><td>19</td><td><code>if percentage &gt;= 90:</code></td><td>Ye <code>if</code> condition line hai. Python condition ko check karta hai, aur agar condition True hoti hai to niche indented code block execute hota hai. Agar condition False hoti hai to block skip ho jata hai. Student project me if marks, percentage, attendance ya failed subjects ke basis par decision lene ke liye use hota hai. Colon <code>:</code> condition ke baad block start hone ka signal deta hai.</td></tr>
<tr><td>20</td><td><code>    grade = &quot;A+&quot;</code></td><td>Ye grade assignment line hai. Indentation batata hai ki ye line upar wali condition True hone par hi run hogi. Right side <code>&quot;A+&quot;</code> ek string value hai jo top grade ko represent karti hai. Ye value <code>grade</code> variable me store hoti hai. Student result project me aisi line final report ke liye grade category set karti hai.</td></tr>
<tr><td>21</td><td><code>elif percentage &gt;= 75:</code></td><td>Ye <code>elif</code> line hai, jiska meaning hota hai else-if. Agar upar wali condition False ho jaati hai tab Python is condition ko check karta hai. Grade system me multiple percentage ranges handle karne ke liye elif useful hota hai. Python top se bottom conditions check karta hai aur first True condition ka block run karta hai. Isse A+, A, B, C aur Fail jaise categories clean way me manage hoti hain.</td></tr>
<tr><td>22</td><td><code>    grade = &quot;A&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>23</td><td><code>elif percentage &gt;= 60:</code></td><td>Ye <code>elif</code> line hai, jiska meaning hota hai else-if. Agar upar wali condition False ho jaati hai tab Python is condition ko check karta hai. Grade system me multiple percentage ranges handle karne ke liye elif useful hota hai. Python top se bottom conditions check karta hai aur first True condition ka block run karta hai. Isse A+, A, B, C aur Fail jaise categories clean way me manage hoti hain.</td></tr>
<tr><td>24</td><td><code>    grade = &quot;B&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>25</td><td><code>elif percentage &gt;= 35:</code></td><td>Ye <code>elif</code> line hai, jiska meaning hota hai else-if. Agar upar wali condition False ho jaati hai tab Python is condition ko check karta hai. Grade system me multiple percentage ranges handle karne ke liye elif useful hota hai. Python top se bottom conditions check karta hai aur first True condition ka block run karta hai. Isse A+, A, B, C aur Fail jaise categories clean way me manage hoti hain.</td></tr>
<tr><td>26</td><td><code>    grade = &quot;C&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>27</td><td><code>else:</code></td><td>Ye <code>else</code> block hai. Jab upar wali if/elif conditions me se koi bhi True nahi hoti, tab else run hota hai. else ke saath condition nahi likhte kyunki ye remaining/default case handle karta hai. Student project me else Fail grade, invalid input ya default output dene ke liye useful hai. Ye decision chain ko complete banata hai.</td></tr>
<tr><td>28</td><td><code>    grade = &quot;Fail&quot;</code></td><td>Ye assignment line hai. Right side ki value left side variable me store hoti hai. Variable ek named container jaisa hota hai jisme data future use ke liye save hota hai. Meaningful variable name code ko readable banata hai. Student project me name, roll number, subjects, marks, attendance, percentage aur grade sab variables me store hote hain.</td></tr>
<tr><td>29</td><td><code>blank line</code></td><td>Ye blank line code ko readable banane ke liye use hui hai. Python is line ko ignore karta hai, lekin learner ke liye code sections clear ho jate hain. Isse input data, calculation logic, condition logic aur final output visually separate dikhte hain. Jab project bada hota hai to blank lines debugging aur explanation dono me help karti hain. Is line ka kaam program run karna nahi, code ko organized banana hai.</td></tr>
<tr><td>30</td><td><code>promoted = percentage &gt;= 35 and failed_subjects == 0</code></td><td>Is line me comparison ya logical expression evaluate ho raha hai. Python right side condition solve karta hai aur result True ya False deta hai. Phir ye boolean result left side variable me store hota hai. Student project me pass/fail, scholarship, promotion, attendance aur validation decisions ke liye aise expressions use hote hain. Ye line program ko decision-ready data deti hai.</td></tr>
<tr><td>31</td><td><code>scholarship_eligible = percentage &gt;= 85 and attendance &gt;= 75</code></td><td>Is line me comparison ya logical expression evaluate ho raha hai. Python right side condition solve karta hai aur result True ya False deta hai. Phir ye boolean result left side variable me store hota hai. Student project me pass/fail, scholarship, promotion, attendance aur validation decisions ke liye aise expressions use hote hain. Ye line program ko decision-ready data deti hai.</td></tr>
<tr><td>32</td><td><code>blank line</code></td><td>Ye blank line code ko readable banane ke liye use hui hai. Python is line ko ignore karta hai, lekin learner ke liye code sections clear ho jate hain. Isse input data, calculation logic, condition logic aur final output visually separate dikhte hain. Jab project bada hota hai to blank lines debugging aur explanation dono me help karti hain. Is line ka kaam program run karna nahi, code ko organized banana hai.</td></tr>
<tr><td>33</td><td><code>print(&quot;=&quot; * 35)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>34</td><td><code>print(&quot;STUDENT RESULT REPORT&quot;)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>35</td><td><code>print(&quot;=&quot; * 35)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>36</td><td><code>print(&quot;Name:&quot;, student_name)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>37</td><td><code>print(&quot;Roll Number:&quot;, roll_number)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>38</td><td><code>print(&quot;Total Marks:&quot;, total_marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>39</td><td><code>print(&quot;Percentage:&quot;, percentage)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>40</td><td><code>print(&quot;Average Marks:&quot;, average_marks)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>41</td><td><code>print(&quot;Grade:&quot;, grade)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>42</td><td><code>print(&quot;Failed Subjects:&quot;, failed_subjects)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>43</td><td><code>print(&quot;Promoted:&quot;, promoted)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
<tr><td>44</td><td><code>print(&quot;Scholarship Eligible:&quot;, scholarship_eligible)</code></td><td>Ye output line hai. <code>print()</code> function screen par message ya variable ki value show karta hai. Double quotes ke andar jo text hai wo label ki tarah print hota hai, aur comma ke baad variable ki current value show hoti hai. Student result project me final report readable format me dikhane ke liye print lines use hoti hain. Is line se learner ko program ka final answer clearly screen par milta hai.</td></tr>
</tbody></table>

<hr class="sep">
<h2 id="mixed-project" class="topic">Final Mixed Practice Project - Smart Student Result Analyzer</h2>
<section class="card"><p>Ab jitna bhi practice hua hai, usko ek final mixed project me combine karte hain. Is project ka purpose ye hai ki learner ko clearly samajh aaye ki operators, conditions aur loops alag-alag topics nahi hain; real project me ye sab ek saath kaam karte hain. Yahan student ka naam, roll number, subjects, marks, attendance, target subject, grade, promotion, scholarship eligibility aur top subject sab ek report me generate honge.</p><p>Is project me arithmetic operators total, percentage aur average nikalenge. Relational operators pass, grade aur highest marks compare karenge. Logical operators promotion aur scholarship rules banayenge. Membership operator target subject check karega. Identity operator missing remark handle karega. for loop repeated subject report banayega. continue invalid marks skip karega. break top subject milne ke baad search stop karega. Range function subjects aur marks ko index ke through connect karega. Pattern printing output ko professional report jaisa banayegi.</p></section>
<div class="box use"><span class="tag">Real World Use</span>Is type ka program school ERP, college result portal, coaching batch report, scholarship eligibility checker, attendance based result system aur basic analytics dashboard ka foundation ban sakta hai.</div>
<div class="box project"><span class="tag">What This Final Project Covers</span>Arithmetic Operators, Relational Operators, Logical Operators, Assignment Operators, Membership Operators, Identity Operators, Operator Precedence, Expression Evaluation, if, if-else, if-elif-else, Nested Style Decisions, for Loop, break, continue, Range Function, Pattern-Based Output aur Complete Result Report.</div>
<h3 class="example-title">Mixed Project Code - All Concepts Together</h3>
<div class="run-loc">Python Code</div>
<pre><code>student_name = &quot;Rahul&quot;
roll_number = 101
subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;, &quot;Computer&quot;, &quot;Hindi&quot;]
marks_list = [88, 76, 91, 95, 80]
attendance = 82
target_subject = &quot;Science&quot;
optional_remark = None

print(&quot;=&quot; * 45)
print(&quot;MIXED PRACTICE RESULT PROJECT&quot;)
print(&quot;=&quot; * 45)

if target_subject in subjects:
    print(&quot;Target Subject Available:&quot;, target_subject)
else:
    print(&quot;Target Subject Not Found&quot;)

total_marks = 0
failed_subjects = 0
top_subject = &quot;&quot;
top_marks = 0

for index in range(len(subjects)):
    subject = subjects[index]
    marks = marks_list[index]

    if marks &lt; 0 or marks &gt; 100:
        continue

    print(subject, &quot;Marks:&quot;, marks)
    total_marks += marks

    if marks &lt; 35:
        failed_subjects += 1

    if marks &gt; top_marks:
        top_marks = marks
        top_subject = subject

maximum_marks = len(subjects) * 100
percentage = (total_marks / maximum_marks) * 100
average_marks = total_marks / len(subjects)

if percentage &gt;= 90:
    grade = &quot;A+&quot;
elif percentage &gt;= 75:
    grade = &quot;A&quot;
elif percentage &gt;= 60:
    grade = &quot;B&quot;
elif percentage &gt;= 35:
    grade = &quot;C&quot;
else:
    grade = &quot;Fail&quot;

promoted = percentage &gt;= 35 and failed_subjects == 0
scholarship_eligible = percentage &gt;= 85 and attendance &gt;= 75

if optional_remark is None:
    optional_remark = &quot;No remark added&quot;

for subject in subjects:
    if subject == top_subject:
        print(&quot;Top Subject Found:&quot;, subject)
        break

print(&quot;=&quot; * 45)
print(&quot;Name:&quot;, student_name)
print(&quot;Roll Number:&quot;, roll_number)
print(&quot;Total Marks:&quot;, total_marks)
print(&quot;Percentage:&quot;, percentage)
print(&quot;Average Marks:&quot;, average_marks)
print(&quot;Grade:&quot;, grade)
print(&quot;Top Subject:&quot;, top_subject)
print(&quot;Top Marks:&quot;, top_marks)
print(&quot;Failed Subjects:&quot;, failed_subjects)
print(&quot;Promoted:&quot;, promoted)
print(&quot;Scholarship Eligible:&quot;, scholarship_eligible)
print(&quot;Remark:&quot;, optional_remark)
print(&quot;=&quot; * 45)</code></pre>
<div class="run-loc">Output</div>
<pre><code>=============================================
MIXED PRACTICE RESULT PROJECT
=============================================
Target Subject Available: Science
Maths Marks: 88
English Marks: 76
Science Marks: 91
Computer Marks: 95
Hindi Marks: 80
Top Subject Found: Computer
=============================================
Name: Rahul
Roll Number: 101
Total Marks: 430
Percentage: 86.0
Average Marks: 86.0
Grade: A
Top Subject: Computer
Top Marks: 95
Failed Subjects: 0
Promoted: True
Scholarship Eligible: True
Remark: No remark added
=============================================</code></pre>
<h3 class="subtopic">Detailed Code Explanation</h3><table><thead><tr><th>Line</th><th>Code</th><th>Explanation</th></tr></thead><tbody>
<tr><td>1</td><td><code>student_name = &quot;Rahul&quot;</code></td><td>Is line me student ka naam variable me store ho raha hai. <code>student_name</code> ek meaningful variable name hai, isliye code padhte hi samajh aa jata hai ki isme learner ka naam rakha gaya hai. String value double quotes ke andar likhi gayi hai. Real project me ye value user input ya database se bhi aa sakti hai.</td></tr><tr><td>2</td><td><code>roll_number = 101</code></td><td>Is line me roll number store ho raha hai. Roll number ek integer value hai, isliye quotes nahi lagaye gaye. Is value ko final report me student identify karne ke liye use kiya jayega. Real school system me roll number se record search, update ya attendance connect ki ja sakti hai.</td></tr><tr><td>3</td><td><code>subjects = [&quot;Maths&quot;, &quot;English&quot;, &quot;Science&quot;, &quot;Computer&quot;, &quot;Hindi&quot;]</code></td><td>Yahan subjects ki list ban rahi hai. List square brackets <code>[]</code> ke andar multiple values store karti hai. Har subject ek string hai, aur comma se separate kiya gaya hai. Project me ye list loop ke through one by one subject report print karne ke kaam aayegi.</td></tr><tr><td>4</td><td><code>marks_list = [88, 76, 91, 95, 80]</code></td><td>Yahan har subject ke marks ek list me store ho rahe hain. Marks ka order subjects list ke order ke saath match kar raha hai, jaise Maths ka marks 88, English ka 76. Is tarah two lists ko index ke through connect karke report generate ki ja sakti hai. Ye practical approach tab useful hoti hai jab repeated data handle karna ho.</td></tr><tr><td>5</td><td><code>attendance = 82</code></td><td>Attendance percentage store ki gayi hai. Iska use scholarship eligibility check karne me hoga. Sirf marks high hona enough nahi hai, attendance bhi rule ke according honi chahiye. Real college systems me attendance aur marks dono ko combine karke eligibility decide hoti hai.</td></tr><tr><td>6</td><td><code>target_subject = &quot;Science&quot;</code></td><td>Target subject woh subject hai jise hum list me search karna chahte hain. Is line ke through membership operator ka practical use ready hota hai. Agar teacher ya learner kisi subject ka availability check karna chahe, to ye variable help karega. Value change karke different subjects test kiye ja sakte hain.</td></tr><tr><td>7</td><td><code>optional_remark = None</code></td><td>Yahan <code>None</code> use hua hai, jiska matlab hai abhi remark available nahi hai. Python me <code>None</code> missing ya empty value ko represent karta hai. Is line se identity operator <code>is</code> ka practical use samjhenge. Report me blank remark dikhane ke bajay default message set karna better practice hai.</td></tr><tr><td>8</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>9</td><td><code>print(&quot;=&quot; * 45)</code></td><td>Ye line report ke liye separator print karti hai. String <code>&quot;=&quot;</code> ko 45 times repeat kiya gaya hai using multiplication operator. Isse output clean aur professional lagta hai. Console based reports me aise separators heading aur final summary ko visually clear banate hain.</td></tr><tr><td>10</td><td><code>print(&quot;MIXED PRACTICE RESULT PROJECT&quot;)</code></td><td>Ye heading print karti hai taaki output dekhte hi samajh aaye ki ye final mixed practice project ka report hai. <code>print()</code> function screen par text show karta hai. Heading se learner ko code ka purpose clear hota hai. Ye classroom demo me output ko organized banata hai.</td></tr><tr><td>11</td><td><code>print(&quot;=&quot; * 45)</code></td><td>Ye line report ke liye separator print karti hai. String <code>&quot;=&quot;</code> ko 45 times repeat kiya gaya hai using multiplication operator. Isse output clean aur professional lagta hai. Console based reports me aise separators heading aur final summary ko visually clear banate hain.</td></tr><tr><td>12</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>13</td><td><code>if target_subject in subjects:</code></td><td>Ye membership operator ka use hai. <code>in</code> check karta hai ki target subject subjects list ke andar present hai ya nahi. Agar subject list me mil jata hai to condition True hoti hai. Real project me ye validation ke liye useful hai, jaise invalid subject name par report generate nahi karna.</td></tr><tr><td>14</td><td><code>    print(&quot;Target Subject Available:&quot;, target_subject)</code></td><td>Agar target subject list me mil gaya, to ye line success message print karti hai. Comma ke baad <code>target_subject</code> likhne se actual subject name bhi output me show hota hai. Isse user ko clear confirmation milta hai. Ye validation feedback ka simple example hai.</td></tr><tr><td>15</td><td><code>else:</code></td><td><code>else</code> default case handle karta hai. Jab upar wali condition False hoti hai, tab else block run hota hai. Iska use program ko complete decision flow dene ke liye hota hai. Student project me fail case, invalid input, ya not found message ke liye else useful hai.</td></tr><tr><td>16</td><td><code>    print(&quot;Target Subject Not Found&quot;)</code></td><td>Ye line tab chalegi jab target subject list me nahi milega. Isse user ko clear message milta hai ki subject available nahi hai. Without this message user confused ho sakta hai ki program ne kuch output kyu nahi diya. Proper feedback project ko user-friendly banata hai.</td></tr><tr><td>17</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>18</td><td><code>total_marks = 0</code></td><td>Yahan total marks ko zero se initialize kiya gaya hai. Loop ke andar har subject ke marks is variable me add honge. Agar starting value zero nahi rakhenge to running total calculate karna clear nahi rahega. Is pattern ko accumulator pattern bol sakte hain, jahan value step by step build hoti hai.</td></tr><tr><td>19</td><td><code>failed_subjects = 0</code></td><td>Yahan failed subjects ka counter zero se start ho raha hai. Jab bhi kisi subject me marks 35 se kam milenge, counter increase hoga. Counter ka use counting problems me hota hai. Result system me is value se decide hoga ki student promoted hai ya nahi.</td></tr><tr><td>20</td><td><code>top_subject = &quot;&quot;</code></td><td>Yahan top subject ke liye empty string rakhi gayi hai. Loop ke andar jab highest marks milenge, tab yahi variable update hoga. Empty string starting placeholder ki tarah kaam karti hai. End me report me best subject show karne ke liye ye variable use hoga.</td></tr><tr><td>21</td><td><code>top_marks = 0</code></td><td>Yahan top marks ko zero se start kiya gaya hai. Loop me har subject ke marks compare honge, aur jo marks current top se zyada honge wo top marks ban jayenge. Is pattern se maximum value find karna easy hota hai. Real result systems me topper subject ya highest score nikalne ke liye ye logic useful hai.</td></tr><tr><td>22</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>23</td><td><code>for index in range(len(subjects)):</code></td><td>Ye for loop index based loop hai. <code>len(subjects)</code> subjects ki total count deta hai, aur <code>range()</code> 0 se last index tak numbers generate karta hai. Index ke through hum subjects list aur marks list dono se matching values nikal sakte hain. Jab two related lists ko saath me process karna ho, tab ye approach helpful hoti hai.</td></tr><tr><td>24</td><td><code>    subject = subjects[index]</code></td><td>Is line me current index ka subject nikala ja raha hai. Agar index 0 hai to Maths milega, index 1 hai to English milega. Loop ke har round me subject change hota rahega. Isse report me subject name ke saath marks print karna possible hota hai.</td></tr><tr><td>25</td><td><code>    marks = marks_list[index]</code></td><td>Is line me same index se marks nikale ja rahe hain. Kyunki subjects aur marks_list ka order same hai, isliye current subject ke correct marks milte hain. Example: index 2 par subject Science hai aur marks 91 hai. Ye list coordination ka practical example hai.</td></tr><tr><td>26</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>27</td><td><code>    if marks &lt; 0 or marks &gt; 100:</code></td><td>Ye validation condition hai. Marks 0 se kam ya 100 se zyada nahi hone chahiye. <code>or</code> ka matlab hai dono me se koi bhi condition True hui to invalid case maanenge. Real systems me invalid data skip ya correct karna important hota hai.</td></tr><tr><td>28</td><td><code>        continue</code></td><td><code>continue</code> loop ke current round ko skip karta hai. Agar marks invalid milte hain, to niche ka calculation run nahi hoga aur loop next subject par chala jayega. Isse wrong data total marks me add nahi hota. Data validation projects me continue ka use clean processing ke liye hota hai.</td></tr><tr><td>29</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>30</td><td><code>    print(subject, &quot;Marks:&quot;, marks)</code></td><td>Ye line current subject ka naam aur marks print karti hai. Loop ke har round me subject aur marks ki value change hoti hai, isliye output me har subject alag line me aata hai. Report generation me loop + print ka combination bahut useful hota hai. Isse manual print lines likhne ki need kam ho jaati hai.</td></tr><tr><td>31</td><td><code>    total_marks += marks</code></td><td>Ye assignment operator ka shortcut use hai. <code>+=</code> ka matlab hai old total_marks me current marks add karo aur result wapas total_marks me store karo. Loop ke har round me total build hota rahega. Ye running total nikalne ka clean aur professional tareeka hai.</td></tr><tr><td>32</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>33</td><td><code>    if marks &lt; 35:</code></td><td>Ye condition check karti hai ki current subject me marks passing marks se kam hain ya nahi. Agar marks 35 se kam hain to student us subject me fail maana jayega. Ye relational operator ka direct use hai. Result project me subject-wise fail count nikalne ke liye ye zaroori logic hai.</td></tr><tr><td>34</td><td><code>        failed_subjects += 1</code></td><td>Ye counter update line hai. Jab fail condition True hoti hai, failed_subjects me 1 add hota hai. Isse pata chalta hai student kitne subjects me fail hua. Later promotion decision isi value ke basis par banega.</td></tr><tr><td>35</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>36</td><td><code>    if marks &gt; top_marks:</code></td><td>Ye line current marks ko ab tak ke highest marks se compare karti hai. Agar current marks top_marks se zyada hain, to current subject new top subject ban jayega. Ye maximum value find karne ka basic algorithm hai. Real reports me topper, best subject ya highest sale find karne me ye same concept use hota hai.</td></tr><tr><td>37</td><td><code>        top_marks = marks</code></td><td>Jab current marks highest milte hain, to ye line <code>top_marks</code> ko current marks se update karti hai. Ab next comparison isi updated highest value ke saath hoga. Isse program step by step best score remember karta hai. Real result report me highest marks identify karne ke liye ye important update line hai.</td></tr><tr><td>38</td><td><code>        top_subject = subject</code></td><td>Ye line highest marks wale subject ka naam update karti hai. Jab bhi new highest marks milte hain, current subject ko <code>top_subject</code> me save kar diya jata hai. Isse final report me sirf marks nahi, balki best subject ka naam bhi show hota hai. Ye highest score ke saath related label store karne ka practical तरीका hai.</td></tr><tr><td>39</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>40</td><td><code>maximum_marks = len(subjects) * 100</code></td><td>Yahan maximum marks automatically calculate ho rahe hain. <code>len(subjects)</code> total subjects count deta hai, aur har subject 100 marks ka maana gaya hai. Agar future me subject add hoga, maximum marks automatically update ho jayega. Ye hard-coded values kam karne ka better practice hai.</td></tr><tr><td>41</td><td><code>percentage = (total_marks / maximum_marks) * 100</code></td><td>Ye line final percentage calculate karti hai. Formula me total marks ko maximum marks se divide karke 100 se multiply kiya gaya hai. Brackets calculation order ko clear banate hain. Percentage grade aur scholarship decisions ke liye main value hai.</td></tr><tr><td>42</td><td><code>average_marks = total_marks / len(subjects)</code></td><td>Ye line average marks calculate karti hai. Total marks ko subjects ki count se divide kiya gaya hai. <code>len(subjects)</code> use karne se average automatically correct rahega even if subjects increase. Average learner performance ka general level show karta hai.</td></tr><tr><td>43</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>44</td><td><code>if percentage &gt;= 90:</code></td><td>Ye grade decision ka first condition hai. Python top se checking start karta hai, isliye sabse high grade condition pehle likhna best hai. Agar percentage 90 ya usse zyada hai to A+ milega. Grade systems me condition order bahut important hota hai.</td></tr><tr><td>45</td><td><code>    grade = &quot;A+&quot;</code></td><td>Is line me final grade value set ho rahi hai. Grade ek string hai, jaise A+, A, B, C ya Fail. Jo condition True hogi, uske andar wali grade assignment run hogi. Final report me ye grade directly print hoga.</td></tr><tr><td>46</td><td><code>elif percentage &gt;= 75:</code></td><td><code>elif</code> ka meaning hota hai else-if. Agar upar wali condition False hoti hai tab Python is condition ko check karta hai. Multiple percentage ranges handle karne ke liye elif clean structure deta hai. Isse grade system readable aur maintainable ban jata hai.</td></tr><tr><td>47</td><td><code>    grade = &quot;A&quot;</code></td><td>Is line me final grade value set ho rahi hai. Grade ek string hai, jaise A+, A, B, C ya Fail. Jo condition True hogi, uske andar wali grade assignment run hogi. Final report me ye grade directly print hoga.</td></tr><tr><td>48</td><td><code>elif percentage &gt;= 60:</code></td><td><code>elif</code> ka meaning hota hai else-if. Agar upar wali condition False hoti hai tab Python is condition ko check karta hai. Multiple percentage ranges handle karne ke liye elif clean structure deta hai. Isse grade system readable aur maintainable ban jata hai.</td></tr><tr><td>49</td><td><code>    grade = &quot;B&quot;</code></td><td>Is line me final grade value set ho rahi hai. Grade ek string hai, jaise A+, A, B, C ya Fail. Jo condition True hogi, uske andar wali grade assignment run hogi. Final report me ye grade directly print hoga.</td></tr><tr><td>50</td><td><code>elif percentage &gt;= 35:</code></td><td><code>elif</code> ka meaning hota hai else-if. Agar upar wali condition False hoti hai tab Python is condition ko check karta hai. Multiple percentage ranges handle karne ke liye elif clean structure deta hai. Isse grade system readable aur maintainable ban jata hai.</td></tr><tr><td>51</td><td><code>    grade = &quot;C&quot;</code></td><td>Is line me final grade value set ho rahi hai. Grade ek string hai, jaise A+, A, B, C ya Fail. Jo condition True hogi, uske andar wali grade assignment run hogi. Final report me ye grade directly print hoga.</td></tr><tr><td>52</td><td><code>else:</code></td><td><code>else</code> default case handle karta hai. Jab upar wali condition False hoti hai, tab else block run hota hai. Iska use program ko complete decision flow dene ke liye hota hai. Student project me fail case, invalid input, ya not found message ke liye else useful hai.</td></tr><tr><td>53</td><td><code>    grade = &quot;Fail&quot;</code></td><td>Is line me final grade value set ho rahi hai. Grade ek string hai, jaise A+, A, B, C ya Fail. Jo condition True hogi, uske andar wali grade assignment run hogi. Final report me ye grade directly print hoga.</td></tr><tr><td>54</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>55</td><td><code>promoted = percentage &gt;= 35 and failed_subjects == 0</code></td><td>Ye logical operator ka practical use hai. Student promoted tabhi hoga jab percentage at least 35 ho aur failed_subjects zero ho. <code>and</code> ka matlab dono conditions True honi chahiye. Is one line me promotion ka complete rule store ho gaya.</td></tr><tr><td>56</td><td><code>scholarship_eligible = percentage &gt;= 85 and attendance &gt;= 75</code></td><td>Ye line scholarship eligibility decide karti hai. Student ko scholarship tab milegi jab percentage 85 ya usse zyada ho aur attendance 75 ya usse zyada ho. Yahan bhi <code>and</code> use hua hai because dono requirements zaroori hain. Real scholarship portals me aise combined rules use hote hain.</td></tr><tr><td>57</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>58</td><td><code>if optional_remark is None:</code></td><td>Ye identity operator ka use hai. <code>is None</code> check karta hai ki optional_remark sach me missing value hai ya nahi. None compare karne ke liye <code>is</code> recommended style hai. Agar remark missing hai to default message set karke report ko clean banaya jayega.</td></tr><tr><td>59</td><td><code>    optional_remark = &quot;No remark added&quot;</code></td><td>Agar remark missing tha, to ye line default text set karti hai. Isse final report me blank ya confusing output nahi aata. User ko clearly dikhta hai ki koi extra remark add nahi kiya gaya. Data presentation me default values project ko clean aur professional banati hain.</td></tr><tr><td>60</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>61</td><td><code>for subject in subjects:</code></td><td>Ye simple for loop subjects list par one by one run hota hai. Is loop ka purpose top subject ko list ke andar find karna hai. Jab target subject mil jayega, loop break ho jayega. Ye searching ka basic practical example hai.</td></tr><tr><td>62</td><td><code>    if subject == top_subject:</code></td><td>Ye equality comparison hai. Current subject ko top_subject ke saath compare kiya ja raha hai. Agar dono same hain, iska matlab top subject list me found ho gaya. <code>==</code> value comparison ke liye use hota hai.</td></tr><tr><td>63</td><td><code>        print(&quot;Top Subject Found:&quot;, subject)</code></td><td>Ye line top subject milne par confirmation print karti hai. Is output se user ko clear ho jata hai ki program ne best subject identify kar liya. Debugging aur teaching dono me aise confirmation messages helpful hote hain. Ye output loop ke andar matching case me hi print hota hai.</td></tr><tr><td>64</td><td><code>        break</code></td><td><code>break</code> loop ko immediately stop kar deta hai. Jab top subject mil gaya, to baaki subjects check karne ki need nahi hai. Isse unnecessary iterations avoid hoti hain. Searching problems me break program ko faster aur cleaner banata hai.</td></tr><tr><td>65</td><td><code>blank line</code></td><td>Ye blank line code ko readable banati hai. Python is line ko execute nahi karta, lekin project ke sections visually separate ho jate hain. Jab code bada hota hai to blank line se input section, calculation section, condition section aur output section easily samajh aate hain. Teaching ke time learner ko flow samjhane me ye simple formatting bahut help karti hai.</td></tr><tr><td>66</td><td><code>print(&quot;=&quot; * 45)</code></td><td>Ye line report ke liye separator print karti hai. String <code>&quot;=&quot;</code> ko 45 times repeat kiya gaya hai using multiplication operator. Isse output clean aur professional lagta hai. Console based reports me aise separators heading aur final summary ko visually clear banate hain.</td></tr><tr><td>67</td><td><code>print(&quot;Name:&quot;, student_name)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>68</td><td><code>print(&quot;Roll Number:&quot;, roll_number)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>69</td><td><code>print(&quot;Total Marks:&quot;, total_marks)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>70</td><td><code>print(&quot;Percentage:&quot;, percentage)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>71</td><td><code>print(&quot;Average Marks:&quot;, average_marks)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>72</td><td><code>print(&quot;Grade:&quot;, grade)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>73</td><td><code>print(&quot;Top Subject:&quot;, top_subject)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>74</td><td><code>print(&quot;Top Marks:&quot;, top_marks)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>75</td><td><code>print(&quot;Failed Subjects:&quot;, failed_subjects)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>76</td><td><code>print(&quot;Promoted:&quot;, promoted)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>77</td><td><code>print(&quot;Scholarship Eligible:&quot;, scholarship_eligible)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>78</td><td><code>print(&quot;Remark:&quot;, optional_remark)</code></td><td>Ye final output line hai. <code>print()</code> function report ke labels aur values screen par show karta hai. Label double quotes ke andar hai, aur comma ke baad variable ki current value print hoti hai. Final project me print lines report ko readable format me convert karti hain.</td></tr><tr><td>79</td><td><code>print(&quot;=&quot; * 45)</code></td><td>Ye line report ke liye separator print karti hai. String <code>&quot;=&quot;</code> ko 45 times repeat kiya gaya hai using multiplication operator. Isse output clean aur professional lagta hai. Console based reports me aise separators heading aur final summary ko visually clear banate hain.</td></tr>
</tbody></table>
<hr class="sep">
<h2 id="practice-tasks" class="topic">5 Learner Practice Tasks</h2>
<section class="card"><p>In tasks ka purpose ye hai ki learner final mixed project ko sirf read na kare, balki khud modify karke confidence build kare. Har task same project ke upar based hai, isliye learner ko real project editing ka experience milega.</p><ol>
<li><strong>Task 1:</strong> Subjects list me ek new subject <code>"SST"</code> add karo aur marks_list me uske marks add karo. Program run karke check karo ki total marks, maximum marks, percentage aur average automatically update ho rahe hain ya nahi.</li>
<li><strong>Task 2:</strong> Attendance value ko 70, 75 aur 90 karke run karo. Observe karo ki <code>scholarship_eligible</code> kab True aur kab False hota hai. Isse logical operator <code>and</code> ka practical behavior clear hoga.</li>
<li><strong>Task 3:</strong> marks_list me kisi ek marks ko 120 ya -5 kar do. Program run karke dekho ki <code>continue</code> invalid marks ko skip karta hai ya nahi. Phir valid marks add karke output compare karo.</li>
<li><strong>Task 4:</strong> Ek new counter <code>distinction_subjects</code> banao. Loop ke andar condition lagao: agar marks 75 ya usse zyada hain to counter increase karo. Final report me distinction subjects ka count print karo.</li>
<li><strong>Task 5:</strong> Final report me ek custom message add karo. Agar <code>promoted</code> True hai to print karo <code>"Ready for next class"</code>, warna print karo <code>"Needs improvement plan"</code>. Is task se if-else ka final project use clear hoga.</li>
</ol></section>
<h2 id="student-notes" class="topic">Student Notes Summary</h2><section class="card"><p>Day 3 me operators, conditional statements aur loops ko Student Marks Management System ke through samjha gaya. Arithmetic operators ne total, percentage aur average calculate kiya. Relational operators ne pass marks aur benchmarks compare kiye. Logical operators ne scholarship aur promotion jaise combined checks banaye. Assignment operators ne values ko store aur update kiya. Membership operators ne valid subjects aur absent students check kiye. Identity operators ne missing data handle kiya. Conditions ne result, grade aur category decide ki. Loops ne repeated report work automate kiya.</p><p>End tak learner ek complete result report project samajh sakta hai jisme calculation, decision making, validation, loops, formatted output, final mixed practice project aur learner tasks sab included hain.</p></section>
