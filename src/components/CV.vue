<template>
  <div>
    <div class="container" style="margin-top:30px">
        <div class="row">
            <div class="col-sm-4">
            <!-- <h2>About Me</h2> -->
            
            <img :src="image" width="200" height="240"/>
            <!-- <h5>Photo of me:</h5> -->
            <!-- <div>Fake Image</div> -->
                <h4 class="text-primary">-:- PERSONAL DETAILS -:-</h4>
                <p><b>Date of Birth:</b> November 26, 1989</p>
                <p><b>Height:</b> 280 Centimeters</p>
                <p><b>Weight:</b> 72 kilograms</p>
                <p><b>Religion:</b> Buddhism</p>
                <p><b>Mailitary Status:</b> Exampted</p>
                <br>
                <h4 class="text-primary">-:- PUBLISHING PROJECT -:-</h4>
                <p>Kosriporn, T., Suwannik, W., and Maleewong, M. Lattice Boltzmann Method for Two-Dimensional Incompressible Navier-Stokes Equation with CUDA. IEEE TENCON 2014, October 22-25.</p>
                <hr class="d-sm-none">
            </div>
            <div class="col-sm-8">
                <h2>Mr.Treenath Kosriporn</h2>
                <h5>Master’s Degree</h5>
                <p>2011 – 2015</p>
                <p class="text-secondary">- Master of Science, Faculty of Science, Kasetsart University GPA: 3.42</p>
                <h5>Bachelor's Degree</h5>
                <p>2007 – 2010</p>
                <p class="text-secondary">- Bachelor of Science, Faculty Information Technology, Rangsit University
GPA: 2.88</p>
                
                <br>
                <h4 class="text-primary">-:- WORK EXPERIENCES -:-</h4>
                <h6>Krung Thai Bank Public Co.,Ltd.</h6>
                <p>May 2019 to Present</p>
                <p class="text-secondary">- Skill: Vue.js, iView, Java, Spring Boot, PL/SQL, GitLab</p>

                <h6>NTT DATA (Thailand) Co., Ltd.</h6>
                <p>March 2016 to March 2019</p>
                <p class="text-secondary">- Skill: Java, JSP Servlets, Spring Batch, Hibernate, MSSQL, Store Procedured, SVN, HP Fortify</p>

                <h6>Advanced Info Service (AIS)</h6>
                <p>March 2015 to March 2016</p>
                <p class="text-secondary">- Skill: JSF, PrimeFaces, HighCharts, Unix Script, Oracle, CVS</p>

                <h6>Accellence (Thailand) Ltd.</h6>
                <p>August 2013 to February 2015</p>
                <p class="text-secondary">- Skill: Java, JSP Servlets, MSSQL, Document Spec, TortoiseSVN</p>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
import image from "@/assets/pic.png"

export default {
  name: 'cv',
  data () {
    return {
      image: image
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
</style>
