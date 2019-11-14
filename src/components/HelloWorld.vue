<template>
   <div>
      <div class="myBanner bg-primary"></div>

      <hr />
      <div class="container">
         <div class="myBanner bg-primary"></div>
      </div>

      <hr />
      <div class="container-fluid">
         <div class="myBanner bg-primary"></div>
      </div>

      <hr />
      <div class="container">
         <dir class="row row-custom">
            <div class="myCell col bg-success"></div>
            <div class="myCell col bg-warning"></div>
            <div class="myCell col bg-danger"></div>
         </dir>
         <dir class="row row-custom">
            <div class="myCell col bg-primary"></div>
            <div class="myCell col bg-info"></div>
         </dir>
      </div>

      <div class="myDiv" id="red">Hello Bootsrap</div>
      <div class="myDiv" id="green">Hello Bootsrap</div>

      <hr />
      <div class="myDiv bg-primary">Hello Bootsrap</div>
      <div class="myDiv bg-secondary">Hello Bootsrap</div>
      <div class="myDiv bg-success">Hello Bootsrap</div>
      <div class="myDiv bg-danger">Hello Bootsrap</div>
      <div class="myDiv bg-warning">Hello Bootsrap</div>

      <hr />
      <div class="myDiv bg-info">Hello Bootsrap</div>
      <div class="myDiv bg-light text-dark">Hello Bootsrap</div>
      <div class="myDiv bg-dark">Hello Bootsrap</div>
      <div class="myDiv bg-white text-dark">Hello Bootsrap</div>
      <div class="myDiv bg-transparent text-dark">Hello Bootsrap</div>
   </div>
</template>

<script>
export default {
   name: "HelloWorld",
   props: {
      msg: String
   }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.myBanner {
   width: 100%;
   height: 200px;
   background: url("/img/header.jpg") no-repeat center center;
   background-size: cover;
}
.myCell {
   width: 100%;
   height: 100px;
}
.row-custom {
  margin-block-start: 0px;
  margin-block-end: 0px;
}

.myDiv {
   width: 200px;
   height: 200px;
   margin: 20px 10px;
   padding: 20px;
   color: white;
   display: inline-block;
}

#red {
   background-color: red;
}
#green {
   background-color: green;
}
</style>
