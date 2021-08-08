<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"> </script>

<script>  
    $.get("https://ipinfo.io", function(response) {  
            alert(response.ip);  
    }, "json")  
</script> 
