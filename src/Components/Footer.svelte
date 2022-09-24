<script>
import luck from "../images/Lock.png";
import lamb from "../images/Half.png";

</script>
<div class="footer">
    <div class="name">
<p class="hello">Hello</p>
<h1 class="gab">Gabriel</h1></div>
<div class="color">
<div class="gra">
<div class="gray">
<div class="noir"><img src={luck} alt="" class="lock"></div>
</div>
</div>
</div>
<p class="para">Unlock your car now </p>
<img src={lamb} alt="" class="lam">
</div>
<style>
.footer{
  text-align: center;  
  padding-top: 40px;
 
}
.hello{
    margin-top:2px;
}
.name{
    line-height:5px; 
}
.color{
    margin-left: 30px; 
}
.para{
    color: #000000;
    font-family: 'Prompt';  
    font-weight:2;
font-size: 12px;
padding-top: 90px;
}
.gab{
  font-family: 'Prompt';  
color: #000000;
}
.noir{
   position: absolute;
    width: 60px;
height: 60px;
border-radius: 50%;
background: #000000;
text-align: center;
transform: translate(5px,5px);
}
.lock{
text-align: center;
padding-top: 16px;
}
.gray{
   
    position: absolute;
    width: 70px;
height: 70px;
transform: translate(6px,5px);
border-radius: 50%;
background: rgba(0, 0, 0, 0.17);
/* text-align: center; */
}
.gra{
    position: absolute;
    margin: 0px 0px 0px 100px;
    width: 80px;
height: 80px;
border-radius: 50%;
background: rgba(0, 0, 0, 0.12);
text-align: center;
margin-left: 60px;  
/* transform: translate(10px,1px); */

}
.lam{
    width:270px;
margin-right: 20px;
    height: 300px;
}

</style>