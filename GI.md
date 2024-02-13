Enter passcode: <input id='password' type='text'  />
<a href="https://akiwakamiowo.carrd.co/" onclick="javascript:return validatePass()">ວധວ</a>
<script>
function validatePass(){
    if(document.getElementById('password').value == 'floof'){
        return true;
    }else{
        alert('passcode not recognized.');
        return false;
    }
}
</script>
