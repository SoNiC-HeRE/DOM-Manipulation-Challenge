# DOM-Manipulation-Challenge<br>
<b>To change the last element of the list without actually modifying the html file</b><br>
<b>Solution:</b><br>
var dummy = document.lastElementChild.lastElementChild.lastElementChild.lastElementChild;<br>
dummy.innerHTML = "OK Tested"
