<template>
<section>
  <b-container>

      <div>
        <b-card bg-variant="danger" text-variant="white" header="Private family History Pages" class="text-center">



<input type="button" value="Enter Protected Page" onClick="passWord()">
<!-- Start Bravenet.com Service Code -->
<div style="text-align: right; width:210px; padding:5px;font: normal 13px arial;">
  <form action="https://pub30.bravenet.com/passwd/show.php" method="post" target="_top">
    <input type="hidden" name="usernum" value="2539049398">
    <h3 style="text-align:center;margin:5px;">Login for Access</h3>
    <div style="padding:5px;">Username: <input type="text" name="uname" size="15" maxlength="30" style="width: 100px;padding:5px;border-radius:5px;border:1px solid #ccc;"></div>
    <div style="padding:5px;">Password: <input type="password" name="passwd" size="15" maxlength="30" style="width: 100px;padding:5px;border-radius:5px;border:1px solid #ccc;"></div>
    <div style="padding:5px;"><a style="color:#00b" href="https://pub30.bravenet.com/passwd/requestpwd.php?usernum=2539049398" target="_top">Request an Account</a> &nbsp; <input type="submit" name="submit" value="Login" style="border-radius:5px;padding:5px 10px;background:#000;border:0;color:#fff;"></div>
    <div style="padding:5px; font-size:11px;"><a href="https://www.bravenet.com" style="color:#00b;">Powered by Bravenet</a></div>
  </form>
</div>
<!-- End Bravenet.com Service Code -->
</b-card>
<button style="border-radius:5px;padding:5px 10px;background:#000;border:0;color:#fff;" onclick="top.location.href = 'https://pub30.bravenet.com/passwd/logout.php?usernum=2539049398';" target="_top">Logout</button>
      </div>
  </b-container>
</section>

</template>

<script>



export default {

  components: {

}
}
</script>
