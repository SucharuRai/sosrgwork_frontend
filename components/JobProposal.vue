<template>
  <div class="container-fluid register">
    <div class="row">
      <div class="col-md-3 register-left">
        <img src="https://image.ibb.co/n7oTvU/logo_white.png" alt=""/>
        <h3>Welcome</h3>
        <p>You are just a few minutes away from earning your own money!</p>
      </div>
      <div class="col-md-9 register-right">
        <ul class="nav nav-tabs nav-justified" id="myTab" role="tablist">
          <li class="nav-item">
            <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-selected="true">Employee</a>
          </li>
        </ul>
        <div class="tab-content" id="myTabContent">
          <div id="home" role="tabpanel" aria-labelledby="home-tab">
            <h3 class="register-heading">Apply as an Employee</h3>
            <div class="row register-form">
              <div class="col-md-12 row-m">
                <div class="form-group">
                  <textarea rows="4" type="text" class="form-control" placeholder="Why should we hire you for the job*" value="" />
                </div>
                <div class="form-group">
                  <textarea rows="4" type="text" class="form-control" placeholder="Tell your Experience*" value="" />
                </div>
                <div class="form-tab">
                  <input type="submit" class="btnUploadRes"  value="UploadResume"/>
                </div>
                <input type="submit" class="btnRegister"  value="Register"/>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
/*Contact sectiom*/
.register{
    background: -webkit-linear-gradient(left, #3931af, #00c6ff);
    padding: 3%;
    height: 100vh;
}
.register-left{
    text-align: center;
    color: #fff;
    margin-top: 4%;
}
.register-left input{
    border: none;
    border-radius: 1.5rem;
    padding: 2%;
    width: 60%;
    background: #f8f9fa;
    font-weight: bold;
    color: #383d41;
    margin-top: 30%;
    margin-bottom: 3%;
    cursor: pointer;
}
.register-right{
    background: #f8f9fa;
    border-top-left-radius: 10% 50%;
    border-bottom-left-radius: 10% 50%;
}
.register-left img{
    margin-top: 15%;
    margin-bottom: 5%;
    width: 25%;
    -webkit-animation: mover 2s infinite  alternate;
    animation: mover 1s infinite  alternate;
}
@-webkit-keyframes mover {
    0% { transform: translateY(0); }
    100% { transform: translateY(-20px); }
}
@keyframes mover {
    0% { transform: translateY(0); }
    100% { transform: translateY(-20px); }
}
.register-left p{
    font-weight: lighter;
    font-size: 16px;
    padding: 12%;
    margin-top: -9%;
    color: #ffffff;
}
.register .register-form{
    padding: 10%;
    margin-top: 10%;
}
.btnRegister{
    float: right;
    margin-top: 10%;
    border: none;
    border-radius: 1.5rem;
    padding: 2%;
    background: #0062cc;
    color: #fff;
    font-weight: 600;
    width: 50%;
    cursor: pointer;
}
.btnUploadRes{
    padding: 2%;
    background: rgba(62, 45, 218, 0.986);
    color: white;
    font-weight: 400;

}
.register .nav-tabs{
    margin-top: 3%;
    border: none;
    background: #0062cc;
    border-radius: 1.5rem;
    width: 28%;
    float: right;
}
.register .nav-tabs .nav-link{
    padding: 2%;
    height: 34px;
    font-weight: 600;
    color: #fff;
    border-top-right-radius: 1.5rem;
    border-bottom-right-radius: 1.5rem;
}
.register .nav-tabs .nav-link:hover{
    border: none;
}
.register .nav-tabs .nav-link.active{
    width: 100px;
    font-size: 16px;
    color: #0062cc;
    border: 2px solid #0062cc;
    border-top-left-radius: 1.5rem;
    border-bottom-left-radius: 1.5rem;
}
.register-heading{
    text-align: center;
    margin-top: 8%;
    margin-bottom: -15%;
    color: #395057;
    font-size: 24px;
}
.row {
  height: 100%;
}
textarea {
  font-size: 14px;
}
</style>