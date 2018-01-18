<template>
  <div id="app">
    <button v-b-modal.modalUpload>Open modal</button>
    <b-modal
            class="modal-upload"
            id="modalUpload"
            title="Upload Units"
            ok-title="Close"
            ok-only
            hide-header-close
            size="lg"
    >
      <div style="padding:200px">
        <div>
          <b-dropdown text="Dropdown Button" class="m-md-2">
            <b-dropdown-item>First Action</b-dropdown-item>
            <b-dropdown-item>Second Action</b-dropdown-item>
            <b-dropdown-item>Third Action</b-dropdown-item>
          </b-dropdown>
        </div>
      </div>
    </b-modal>

    <b-dropdown text="Dropdown Button" class="m-md-2">
      <b-dropdown-item>First Action</b-dropdown-item>
      <b-dropdown-item>Second Action</b-dropdown-item>
      <b-dropdown-item>Third Action</b-dropdown-item>
    </b-dropdown>
  </div>
</template>

<script>
import Vue from 'vue';
import BootstrapVue from 'bootstrap-vue';
Vue.use(BootstrapVue);

import '../node_modules/bootstrap/dist/css/bootstrap.css';
import 'bootstrap-vue/dist/bootstrap-vue.css';

export default {
  name: 'App',
  components: {

  }
}
</script>