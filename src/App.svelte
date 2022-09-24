<script>
import Header from "./Components/Header.svelte";
import Footer from "./Components/Footer.svelte";
import Header2 from "./Components/Header2.svelte";
import Footer2 from "./Components/Footer2.svelte";

</script>
<main> 
  <div class="section">
<Header/>
<Footer/>
</div>
<div class="section2">
  <Header2/>
  <Footer2/>
    </div>
  </main>
<style>
main{
 max-width:
2000px;
 background: #1D0404;
height: 1000px;
}
.section{
  width: 250px;
height: 575px;
  background:white;
  opacity: 10;
margin-left: 400px;
margin-top: 100px; 
margin-bottom: 300px;
}
.section2{
  width: 250px;
height: 575px;
  background:white;
  opacity: 10;
margin-left: 900px;
margin-top: 100px; 
/* margin-bottom: 300px; */
}
</style>