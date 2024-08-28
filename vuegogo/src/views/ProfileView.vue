<template>
    <div class="profile">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="d-flex align-items-center">
              <div class="flex-shrink-0">
                <img src="../assets/logoname.jpg" class="user-pic mr-3">
              </div>
              <div class="flex-grow-1 ms-3 text-left">
                <h5>Mahda Ilma</h5>
                <p>This is some content from a media component. You can replace this with any content and adjust it as needed.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  import 'bootstrap/dist/css/bootstrap.css'
  
  export default {
    name: 'profileView',
    components: {
    }
  }
  </script>

  <style scoped>
  .user-pic {
    border-radius: 200%;
    height: 80px;
    width: 80px;
  }
  .text-left {
    text-align: left;
  }
  </style>
  