# sean1

<!DOCTYPE html> 
<html>
  
  <h1> Details</h1>
<label>
  Name:<br>
  <input id="name"><br>
  </label>
  <label>
    <br>Grade:<br>
    <input id="grade" type="range" min="1" max="7"><br>
  </label>
  <label>
  <br>Favorite Subject:<br>
   
  </label>
  <select id="subject">
    <option value="Star Platinum">Science </option>
    <option value="Crazy Diamond">Math </option>
    <option value="Gold Experience"> English</option><br>
    
  <br></select>
  <br>
  <br><label>
    Traits:
  </label>
  <br><select id="trait">
    <option value="It is good to see learning on your stand">Smartass </option>
  <option value="You could be able to defeat <em>DIO</em> with your stand"> Confident</option>
    <option value="You can of course get better at using your stand by training">Hard Worker</option>
  </select>

  <h1> Message From Jotaro Kujo </h1>
  
  <p> Good Grief,</p><br>
  
  <p><span id="cname"> </span>,for <span id="cgrade"> </span> years now, you have mastered your stand,<span id="csubject"> </span>.. Which is Great!</p>
<p><span id="ctrait"> </span> </p>

  
  <p> Till Next Time, <br>
  Jotaro Kujo
  </p>
  
  <script>
    function inputAction(){
     cname.textContent = name.value; 
      csubject.textContent = subject.value;
      cgrade.textContent = grade.value;
      ctrait.textContent = trait.value;
    }
    name.oninput = inputAction;
    subject.onchange = inputAction;
    grade.onchange = inputAction;
    trait.onchange = inputAction;
  </script>
  
</html>
