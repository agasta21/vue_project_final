<template>
    <div>   
        <!-- Header -->
        <app-header></app-header>
        
        <!-- Menu -->
        <app-menu></app-menu>
        
        <!-- Body -->
        <div class="content-wrapper">
          <section class="content-header">
            <div class="container-fluid">
              <div class="row mb-2">
                <!-- Header -->
                <div class="col-sm-6">
                  <h1>Leave Request Add</h1>
                </div>
              </div>
            </div>
          </section>

          <!-- Main content -->
          <section class="content ml-3 mr-4">
            <app-form-add-leave-request></app-form-add-leave-request>
          </section>
          <!-- /.content -->
        </div>
        <!-- Footer -->
        <app-footer></app-footer>
    </div>
    
</template>
<script>
import AppHeader from './../components/header/Header.vue'
import AppMenu from './../components/menu/Menu.vue'
import AppFormAddLeaveRequest from './../components/body/FormAddLeaveRequest.vue'
import AppFooter from './../components/footer/Footer.vue'
export default {
  components:{
      AppHeader,
      AppMenu,
      AppFormAddLeaveRequest,
      AppFooter
  }
}
</script>