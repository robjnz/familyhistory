<template>

<script>
function passWord() {
var testV = 1;
var pass1 = prompt('Please Enter Your Password','');
while (testV < 3) {
if (!pass1)
history.go(-1);
if (pass1.toLowerCase() == "r150b255s325r121n235") {
window.open('/family/boj766584sztriv/');
break;
}
                                                                                                                                                                                                                                                testV += 1;
                                                                                                                                                                                                                                            var pass1  = 
prompt('Access Denied - Password Incorrect, Please Try Again.','');
}
if (pass1.toLowerCase()!="password" & testV ==3)
history.go(-1);
return " ";
}
</script>

</template>


