<div>
  <input id="date" type="date"/>
  <button id="button">send</button>
  <div id="message"></div>
</div>

<script>
  const button = document.querySelector('#button');
  button.addEventListener("click", function(){
    const date = document.querySelector('#date').value;
    const message = document.querySelector('#message');
    
    if (date != ""){
    	const userDate = new Date(date);
      const actualDate = new Date();
      const result = actualDate.getFullYear() - userDate.getFullYear();
      
      message.innerHTML= `Masz ${result} lat`;
    } else {
    message.innerHTML = "Nie podano daty!";
    }
  })
  
</script>
