# Script-
<script>

function validateForm()

{

var x = 1 document.registration.name.value; var y = 1 document.registration.pincode.value; if ( x ==1 null || x == "")

{

alert("Please enter the Name"); document.registration.name.focus(); return false;

}

if ( y ==^ prime prime n )

{

alert("please enter the pincode properly"); document.registration.pincode.focus();

return false;

}

if (isNaN (y) )

{

alert("please enter a number"); document.registration.pincode.focus();s

return false;

}

If (y.length>6 || y.length<6)

{

alert("please enter a six digits");

document.js2.pincode.focus();

return false;

}

}

</script>
